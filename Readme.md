# Project name
## Typing training.

# Description 
### This project will allow you to regularly train your typing speed. This skill is quite justified and can be used in practice, so this application will be very useful for you. Here, you will be asked to type a random text at a time, the application will record: the total number of your workouts, your best result, as well as your average typing speed.

# Installation
### You can create a debug build with all assets preloaded. This is pretty much what you are looking for. This way, even if your app is not connected to the metro bundler, it will work as expected and display all images, etc. Run the following commands from the project root:
#### Copy assets:
##### react-native bundle --dev true --platform android --entry-file index.js --bundle-output ./android/app/build/intermediates/assets/debug/index.android.bundle --assets-dest ./android/app/build/intermediates/res/merged/debug
#### Debug build generation:
##### cd android && ./gradlew assembleDebug
### Find the generated debug build in this folder android/app/build/outputs/apk/debug/

# Usage
### Once you've launched the app, tap start workout, then enter the text above as quickly as you can.

# Contributing
## Author №1: Pavel Zhukouski, main director, invented and created an application.
## Author №2: Ilya Salei, creative director, worked with all the ins and outs.
