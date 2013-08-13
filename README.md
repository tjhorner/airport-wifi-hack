Airport WiFi hack Chrome extension
=

How it works
-

Airports do not usually redirect images on their WiFi networks so that web browsers can fetch the images to show on their registration page. Taking advantage of this, this adds ?.jpg to the end of every URL.

Well, how does ?.jpg help?
-

?.jpg helps by making the website think you are just making a PHP query of .jpg. The airport's firewall usually takes every URL without .jpg at the end of it as not an image. Since this adds that extension into it, the network thinks you are just looking at an image.

License
-

This is licensed under an Apache v2 license.
