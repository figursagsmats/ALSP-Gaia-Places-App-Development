# General ALSP

Each section of this document covers some technique, pattern or guidelines chosen to be used in the project. A section should contain the following:

* Description of the technique (if not invented or modified this is probably just a link)
* Why this technique was chosen
* Links to learning resources


## Xamarin Forms

The main framwork used when building Gaia Places Apps is Xamrin Forms. 

### Why?

What things you need to install the software and how to install them

```
Give examples
```

### Learning

En bra introduktion till Xamarin Forms kan fås med denna kurs (inlogg kan fås av GLA):
[Xamarin Forms: Build Native Cross-platform Apps with C#](https://www.udemy.com/xamarin-forms-course/learn/v4/overview)

Vidare så finns en välskriven gratis bok utgiven digitalt av Microsoft och skriven av en av Xamarin Forms skapare:
[Creating Mobile Apps with Xamarin.Forms ](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/)

## MVVM

## Why?
MVVM har funnits länge och används fortfarande, även om mycket tyder på att MVC/MVVM-liknande patters kanske är påväg att [erättas](xhttp://www.michaelridland.com/xamarin/mvvm-mvc-is-dead-is-unidirectional-a-mvvm-mvc-killer/) så är ersättarna inte tillräckligt mogna för att enkelt kunna implementeras i Xamarin. MVVM är utformat för WPF vilket har stora likheter med Xamarin Forms. MVVM kanske inte är bäst, men some practice is better than no practice.

### Learning
För att underlätta så har jag i helgen tittat igenom flertalet kurser i ämnet och konstaterat att denna är bäst:
[WPF MVVM In Depth](https://www.pluralsight.com/courses/wpf-mvvm-in-depth)

Som ni kommer märka så avser kursen MVVM i WPF och inte Xamarin Forms. Men frukta icke! Jag har även tagit mig igenom en hel kurs i WPF och kan meddela att Xamarin Forms och WPF är väldigt lika! Nästan alla koncept som finns Xamarin Forms har en motsvarighet i WPF. Namnen är ibland olika vilket kan vara förvirrande, men för att förstå grundkoncepten i MVVM så funkar kursen mycket bra. /GLA