# General ALSP

Each section of this document covers some technique, pattern or guidelines chosen to be used in the project. A section should contain the following:

* Description of the technique (if not invented or modified this is probably just a link)
* Why this technique was chosen.
* Links to learning resources


## [Xamarin Forms](https://developer.xamarin.com/guides/xamarin-forms/)

### Why?
Xamarin.Forms is code once deploy alla solution which many people is sceptical about. Most complaines are about


## [MVVM](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)

MVVM anses av många vara best practice för att utveckla WPF-appar, och eftersom WPF och Xamarin.Forms har stora likheter, verkar det som ett rimligt förslag att nyttja detta mönster vid utvecklandet av Xamarin.Forms-appar. Ytterliggare incitament är att den officiella [Xamarin.Forms-boken][21] har ett [kapitel][22] dedikerat till MVVM.

MVVM har funnits länge och används fortfarande, även om MVC/MVVM-liknande har börjat få [konkurens][23] av [flux][24]-liknande arkitekturiska mönster, så är ersättarna i många fall [fortfarande under utvärdering][25] och kan därmed inte enkelt implementeras med säkert resultat i Xamarin. MVVM kanske inte är bäst, men some practice is better than no practice då det innebär att det finns gedigna resurser att tillgå när man som nytillkommen utvecklare vill förstå hur våra appar är uppbyggda.

För bli insatt i fördelar och nackdelar med MVVM kan följande disskussioner var till hjäl:git

[21]: https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/
[22]: https://xamarin.azureedge.net/developer/xamarin-forms-book/XamarinFormsBook-Ch18-Apr2016.pdf
[23]: http://www.michaelridland.com/xamarin/mvvm-mvc-is-dead-is-unidirectional-a-mvvm-mvc-killer/
[24]: http://blog.andrewray.me/flux-for-stupid-people/
[25]: https://medium.com/hacking-and-gonzo/flux-vs-mvc-design-patterns-57b28c0f71b7


## [Prism](https://github.com/PrismLibrary/Prism)
För att förenkla implementationen av MVVM använder vi oss av Prism som är ett bibliotek som finns till både Xamarin och WPF. Det finns flera bibliotek som tillhandahåller denna funktionalitet, men det faktum att Prism för Xamarin är lättvikt och har en enkel [dokumentation](http://prismlibrary.readthedocs.io/en/latest/Xamarin-Forms/1-Getting-Started/) som man kan ta till sig på en timme eller två, gör det till ett bra val. Att Prism fick en egen [session] (https://www.youtube.com/watch?v=DYRLcqG2BAY) under den officiella [Xamarin-konferencen](https://evolve.xamarin.com/) är en god indikation på att biblioteket har potential och tas på allvar.