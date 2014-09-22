Background Location Update Programming for iOS 7
==============

***********************************************************************************************
IMPORTANT:

you can only use this background mode if your app truly needs this information to provide value for the user. If you use this mode and Apple sees nothing the user will gain from it, your app will be rejected. Sometimes Apple will also require you to add a warning to your app’s description stating that your app will result in increased battery usage.
***********************************************************************************************

Most of the solutions before iOS 7 work well because during that time the system does not 
have multitasking and the system does not automatically move the app from background mode 
to suspended mode.

So, if your app needs consistent location update from the device, you will have to 
implement a solution that constantly refresh the app when it is in background mode so that 
it has a short period of time in executing the code and send the location to your server.

I have personally used a few weeks of time in testing various solutions that I found from 
StackOverFlow and also Apple Developer Forum but I didn't have much luck. 

I only managed to get the consistent location update on the background in iOS 7 by 
combining a few solutions together with my own tweaks.

The solution that I am provided might not be elegant but it is able to do what I need to
do. I am constantly looking for a better solution when I have time. 

I am glad that this solution helps some other iOS developers who are developing location 
based application. So far, this is the most popular post on my blog. If you have any 
question, you may join us for a discussion here: [Background Location Update Programming for iOS 7](http://mobileoop.com/background-location-update-programming-for-ios-7 "Background Location Update Programming for iOS 7").
