During the last months, we have made some improvements to the [FormsPresenters plug-in](https://github.com/Cheesebaron/Cheesebaron.MvxPlugins/tree/master/FormsPresenters/WindowsPhone) taken from real-world projects we are working on with our customers, at Plain Concepts. Since we did not have some NuGet packages to make an easy install of the scaffolding needed, we dedicated some effort to add a small documentation to the GitHub repository it-self, so everyone can easily set-up MvvmCross on their Xamarin.Forms projects.

The first step is to clone the entire repo. locally, and build the MvvmCross [submodule](https://github.com/Cheesebaron/Cheesebaron.MvxPlugins/tree/master/submodules). Apart from here, the rest of the steps are done within the [FormsPresenters directory](https://github.com/Cheesebaron/Cheesebaron.MvxPlugins/tree/master/FormsPresenters). You will find four different projects inside: Core one, which handles the common logic among every supported platform (Android, iOS and Windows Phone); and one project per supported platform, which basically contains the final [Presenters](http://gregshackles.com/presenters-in-mvvmcross-a-primer/).

[Read the entire article...](http://blogs.plainconcepts.com/xamarinteam/2015/05/21/formspresenters-setting-up-mvvmcross-with-xamarin-forms/)