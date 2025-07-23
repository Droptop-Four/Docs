# BarModifier

## Making special changes to your app's icon

By default, your app is designed to open a dropdown menu containing your app or just be a simple button in the bar, but depending on how you want your app to work, you might want your app button in the Top Bar to have multiple icons, each with their own unique action when clicked, or display text, change color, or even change the settings of the bar itself, or any combination of these and more.

`BarModifier.inc` will allow you to make modification to the code of the top bar, including the button of your app and how it behaves. In your app folder, you will have a folder called `BarModifier`. Inside, you will find `BarModifier.inc`.

To make more advanced changes to BarModifier, it's recommended you take a look at some other apps other users have already made, copy the code to your BarModifier file, and make any adjustments you choose from there. For example, if you want to have an app that displays multiple icons in the bar, see the `BarModifier.inc` file for the [`Functions` app](https://www.droptopfour.com/community-apps/?id=41).&#x20;

If you selected `"App is just a button"` when making your app, the action for what will happen when your app is clicked in found in BarModifier. Enter any bangs you would like clicking the app icon to perform on line `LeftMouseDownAction=`.

Tip: For meters/measures in BarModifier.inc that need to be updated every second or longer invervals, just add the following to the respective meters/measures:\
\
Every 1 Second: `Group=UpdateMeter1S` or `Group=UpdateMeasure1S`\
Every 10 Seconds: `Group=UpdateMeter10S` or `Group=UpdateMeasure10S`\
Every 5 Minutes: `Group=UpdateMeter5M` or `Group=UpdateMeasure5M`\
Every 20 Minutes: `Group=UpdateMeter20M` or `Group=UpdateMeasure20M`\
Every 1 Hour: `Group=UpdateMeter1H` or `Group=UpdateMeasure1H`\
Every 3 Hours: `Group=UpdateMeter3H` or `Group=UpdateMeasure3H`\
Every 1 Day: `Group=UpdateMeter1D` or `Group=UpdateMeasure1D`
