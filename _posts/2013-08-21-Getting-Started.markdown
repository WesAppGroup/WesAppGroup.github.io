---
layout: post
title:  "Getting Started With Cordova and JQuery Mobile"
date:   2013-08-21 18:15:04
categories: jekyll update
---

Here are some helpful links for getting started. I have been using 2.9.0 but we can revaluate whent the schoolyear starts.

[Cordova Download] (http://cordova.apache.org/)



The platform guide explains everything from setting up the development environment to deploying the app on an emulator/phone.

[Android Platform Guide] (http://docs.phonegap.com/en/2.9.0/guide_getting-started_android_index.md.html#Android%20Platform%20Guide)


To use JQuery Mobile you will also need JQuery. Do not use the CDN version for any of the js libraries. Either the compressed or uncompressed versions are fine.

[JQuery 2.0.3] (http://jquery.com/download/)



When downloading JQuery Mobile, download the zip file. It contains an images folder that you need to place inside the css folder of your app.

[JQuery Mobile 1.3] (http://jquerymobile.com/download/)

This is what your file structure should look like:

assets/www/

---- css/

....---- images/

....---- index.css

....---- jquery.mobile-1.3.1.min.css


---- js/

....---- index.js

....---- jquery-2.0.3.min.js

....---- jquery.mobile-1.3.1.min.js

....---- img/

---- index.html


For an example on how to use JQuery Mobile and Cordova together, look at the example apps on the WesAppGroup github page.

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
