Css Device mockup
=================

For testing the app running in different size of devices, we can run it with Ripple emulator. Problem is we cannot run same app in different emulators. Also, it is ... hmm .. buggy.

#Simple
You can see, all my stuff are simple. Few lines of code, straigh forward CSS, Javascript. This one is not an exception. I make a simple mockup with CSS for Iphone, Galaxy. You can make it to any device that fit on your browser. Since I only test with these two devices, then here they are.
The structure is
1-device wrappup, this is the appearance of the device, plenty of room for improvement, the important figures are width and height. For example, you can make an Iphone4 by changing to 320x480. Ip5 320x580 and so on. Your app must either use Media query -big css- or apply the script to adjust the size -i go for this one for faster performance on Android devices-.
2-Some buttons to reset the app. You can change them to whatever, my case, I dont use them so no code there.
3- The iframe that wrap your app. Change the source src to your app and that is it.

#Notes
- you can run all mockups same time, my case, I run Ipad, Iphone, Galaxy in same browser to check my script adjusting the size of the elements and the like.
- The src is pointing to one of my app, you can see the different looks there.
