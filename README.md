# E4link Empatica Project

## Introduction

This sample project gives you the boilerplate code you need to connect to an Empatica E4 device and start streaming data.

The sample application implemented in the project has very simple functionalities:

- It initializes the E4link library with your API key.
- If the previous step is successful, it starts scanning for Empatica devices, till it finds one that can be used with the API key you inserted in the code.
- When such a device has been found, the app connects to the devices and streams data for 10 seconds, then it disconnects.

## Setup

- Clone / download this repository.
- Open the sample project in Android Studio.
- Make sure you have a valid API key. You can request one for your Empatica Connect account from our [Developer Area][1].
- Edit `MainActivity.java` and assign your API key to the `EMPATICA_API_KEY` constant .
- Download the Android E4 link 1.0 or newer SDK from our [Developer Area][1].
- Unzip the archive you've downloaded and copy the `.aar` file you'll find inside into the `libs` folder contained in the sample project.
- Build and run the project.
- If a device is in range and its light is blinking green, but the app doesn't connect, please check that the discovered device can be used with your API key. If the `allowed` parameter is always false, the device is not linked to your API key. Please check your [Developer Area][1].

If you need any additional information about the Empatica API for Android, please check the [official documentation][2].

[1]: https://www.empatica.com/connect/developer.php
[2]: http://developer.empatica.com



![Screenshot_20231110-112531 (1)](https://github.com/shivshankar2996/Empatica/assets/112530146/cebcba0d-5196-4011-b09a-8eb2d1814965)
![Screenshot_20231110-112431](https://github.com/shivshankar2996/Empatica/assets/112530146/1485fc7f-60ae-4134-8efc-c65f26b6d617)
![Screenshot_20231107-151641](https://github.com/shivshankar2996/Empatica/assets/112530146/704732b2-8842-495b-a747-e551bfcb7a9b)
![E4](https://github.com/shivshankar2996/Empatica/assets/112530146/e40a2203-1ee6-426c-b3d1-3ab3411eda55)



