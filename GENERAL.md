# General ALSP

Each section of this document covers some technique, pattern or guidelines chosen to be used in the project. A section should contain the following:

* Description of the technique (if not invented or modified this is probably just a link)
* Why this technique was chosen
* Links to learning resources


## [Xamarin Forms](https://developer.xamarin.com/guides/xamarin-forms/)

### Why?
Xamarin.Forms is code once deploy alla solution which many people is sceptical about. Most complaines are about


## MVVM

## Why?
MVVM anses av många vara best practice för att utveckla WPF-appar, och eftersom WPF och Xamarin.Forms har stora likheter, verkar det som ett rimligt förslag att nyttja detta mönster vid utvecklandet av Xamarin.Forms-appar. Ytterliggare incitament är att den officiella [Xamarin.Forms-boken](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/) har ett [kapitel](https://xamarin.azureedge.net/developer/xamarin-forms-book/XamarinFormsBook-Ch18-Apr2016.pdf) dedikerat till MVVM.

MVVM har funnits länge och används fortfarande, även om en del tyder på att MVC/MVVM-liknande patters kanske är påväg att [erättas](xhttp://www.michaelridland.com/xamarin/mvvm-mvc-is-dead-is-unidirectional-a-mvvm-mvc-killer/) av [flux](http://blog.andrewray.me/flux-for-stupid-people/)-liknande arkitekturiska mönster, så är ersättarna i många fall [fortfarande under utvärdering](https://medium.com/hacking-and-gonzo/flux-vs-mvc-design-patterns-57b28c0f71b7) och kan därmed inte enkelt implementeras med säkert resultat i Xamarin. MVVM kanske inte är bäst, men some practice is better than no practice.

## Prism