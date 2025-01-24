# Godot Mobile Plugin
Integrates Google Play &amp; iOS Plugins into your Godot Project!
Release on both platforms, or just one ~ 
Have your project already ready to target the other platform when you decide! 

## About
This plugin integrates Google Play Game Services, Google BillingClient, Apple GameKit, Apple StoreKit, Apple Push Notifications, and more!

No more needing to seperate concerns this plugin will help you target mobile, regardless if you're releasing on both platforms this plugin will fully integrate both platforms to be used. If youre not on on the platform the dependencies won't get loaded.

Both plugins have been combined into a super plugin called MobilePlugin, depending on platform this Singleton will call the correct methods.

So you don't need to call both apple, and google functions you can just call on MobilePlugin and it will handle the rest.

For example you can call `MobilePlugin.achievements_show()`
this will show achievements for either android or apple depending on which device you are using!

## Installing the plugins
