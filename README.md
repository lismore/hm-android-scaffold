# Overview

This app provides a simple scaffold to start building an app with HMKit on Android. These things have been done:

1. New Gradle project created in Android Studio
1. SDK imported and added to dependencies
1. SDK initialised with snippet from the Developer Center
1. One example included to send a telematics command to the car
1. One example included to send a Bluetooth command to the car

# Configuration

Before running the app, make sure to configure the following in `MainActivity.java`:

1. Initialise HMKit with a valid `Device Certiticate` from the Developer Center https://developers.high-mobility.com/
2. Follow the introduction and setup https://high-mobility.com/learn/tutorials/sdk/android/#introduction-and-setup
2. Create an `Access Token` in the car emulator and paste in the source code to download an `Access Certificate` from the server

    ![IOTA Mobility](https://i.ibb.co/Vjnb3k5/iotamobility.png)


# Run the app

Run the app on your phone or the Android emulator to try out sending a few commands to the car. Note that Bluetooth only works on a real device.
