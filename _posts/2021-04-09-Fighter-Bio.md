---
layout: post
title: Fighter's Bio
---
![_config.yml]({{ site.baseurl }}/images/mockup_1.png)

# Idea

So basically the idea was to practice knowledge in MVVM, Firebase, StoreKit, AVKit, Local notifications and UIKit. At the same time I wanted to face well-known issues with publishing Apps to App Store. The best way to do it - make something that you love. That's how Mortal Kombat themed application was born. 

## Development

![_config.yml]({{ site.baseurl }}/images/xcodeFiles.png)

JavaScript Object Notation file &#129299; is stored in Firebase realtime database. The .json file contains each fighter's name, description, weaknesses and strengths, URL's to images and videos ID's. Also app implemented with Firebase Remote config, Analytics and Crashlytics.
There is non-consumable purchase that disables in-app advertisement (provided by Google AdMob).
The biggest struggle was to enroll to Apple Developer program. Turns out that Apple is a bit too dangerous proceeding payments from CIS citizens. The challenge was to proof that your credit card has enough money and able to proceed payments, proof your identity and make a call to Apple Developer Programm Support.

That was a tip of a problem, because later i've met Apple App Store review team. After a week of battle, and continuously renaming the application, the App is finally published to App store.

The project was made in partnership with [Darya](https://www.linkedin.com/in/dkislaya/) - UX/UI designer.  &#128536;

![_config.yml]({{ site.baseurl }}/images/mockup_2.png)

![_config.yml]({{ site.baseurl }}/images/flow.png)

## Pods
* Firebase
* Kingfisher
* SwiftyGif
* youtube-ios-player-helper
* GoogleMobileAds


## [Check it out by yourself, it's free! &#128579;](https://apps.apple.com/us/app/fighters-bio/id1560835318)

![_config.yml]({{ site.baseurl }}/images/gifForMK.gif)
