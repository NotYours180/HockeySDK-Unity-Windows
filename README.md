HockeySDK for Unity (Windows)
=========

The official SDK for the HockeyApp service for Unity apps on Windows.

## Introduction

The HockeySDK for Windows allows users to send crash reports right from within the application.
When your app crashes, a file with basic information about the environment (device type, OS version, etc.), the reason and the stacktrace of the exception is created. 
The next time the user starts the app, he is asked to send the crash data to the developer. If he confirms the dialog, the crash log is sent to HockeyApp and then the file deleted from the device.

## Supported Platforms
As of now we support Unity WP8 builds, but we plan to add support for other Windows platforms soon.

This is an alpha version. Please report any bugs/feature requests as Github tickets. Thanks!

## Features & Installation

### Windows Phone 8

1. Close your Unity-Project
2. Copy the contents of the HockeyAppUnityWindowsAssets.zip file to your Assets directory.
3. ReOpen your Project in Unity Editor
4. Create a new empty GameObject
5. Add a ScriptComponent to the GameObject. Choose HockeyAppWP8Script
6. in the component view add your HockeyApp AppID and tick the relevant boxes.
7. Build your project for Windows Phone 8 in the Unity Editor

Have a look at the sample project in the ExampleProject folder.

## Support

If you have any questions, problems or suggestions, please contact us at [support@hockeyapp.net](mailto:support@hockeyapp.net).