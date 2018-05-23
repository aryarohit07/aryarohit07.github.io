---
layout: post
title: Face centering Android library build on top of Google Vision API
subtitle: Memory efficient Android image transformation library providing cropping above Face Detection
mediumUrl: https://medium.freecodecamp.org/face-centering-android-library-build-on-top-of-google-vision-api-f88661b97959
mediumImg: https://raw.githubusercontent.com/aryarohit07/aryarohit07.github.io/master/img/face_crop_poster.png
---

In our Android apps, when we crop photos to display them, we often encounter the problem of positioning faces properly.

This inspired me to create a tool that will locate faces and in an image (if there are any) and center the cropped image around them.

Here’s how I did it.

I started with Face Detection API of Google’s mobile vision. This API provides:
