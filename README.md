Mitzuli [BETA]
==============

Simple, clean, yet powerful translator app for Android.

For more information, visit [www.mitzuli.com](http://www.mitzuli.com/).


Features
--------

- Over 50 translation directions, powered by Apertium
- OCR (camera input), powered by Tesseract (OCR engine) + Leptonica and OpenCV (preprocessing)
- TTS (voice output)
- Full offline mode with lightweight package downloads (about 5MB)
- Intuitive card-based Holo user interface


Screenshots
-----------

![Screenshots](http://i40.tinypic.com/t7h739.jpg)


Building
--------

- Set the path to your NDK installation in gradle.properties
- (Optional) Set your API keys for ACRA and Apertium web service in com.mitzuli.Keys
- Either import the project in Android Studio or run './gradlew assemble'


License
-------

Copyright (C) 2014, Mikel Artetxe

Licensed under the terms of the GNU General Public License, either version 2 or (at your option) any later version. A full copy of the license can be found in LICENSE.txt.

This project includes third party libraries; please see libraries/ for copyright details pertaining to them.
