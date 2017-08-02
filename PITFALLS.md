# Pitfalls
Här fyller vi på med så kallade pitfalls som vi upptäcker under utvecklandets gång. Pitfalls innebär i detta fall scenarion som innebär mycket mer svårigheter än vad man först kan ana.


## Async exits UI-thread

Tobbe kommer här förklara varför det ibland är farligt att använda await

Some code

```
Give the example
```

And repeat

```
until finished
```

## Bindings and preformance

Try to minimize the number of bindings, e.g. never use bindings for static content: https://developer.xamarin.com/guides/xamarin-forms/deployment-testing/performance/#Reduce_Unnecessary_Bindings 

## Apps running in the background with platform dependent code
A app that can run in the background which has not been started by a user, e.g. like the GMail app which syncs mail after a reboot. A app like that cannot use Xamarins DependencyService for running platform dependent code, as Xamarin has to be initlized (in MainApplication, Android och AppDelegate, iOS) to enable DependencyService and Xamarin is not initilized when when the app is running in the background. Which is why an other depedency injection framework should be used, such as Unity.

## Another pitfall

Explain what what

```
Give an example
```
