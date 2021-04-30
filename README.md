# Agora Group Video Calling

Quickstart for 1-1 video call with stats in Flutter using Agora SDK. Use this guide to quickly start a multiple user group call. 

## Prerequisites

- '>= Flutter 1.0.0'
- Agora [Developer Account](https://console.agora.io/)

## Create an Account and Obtain an App ID

To build and run the sample application, first obtain an app ID:

1. Create a developer account at agora.io. Once you finish the sign-up process, you are redirected to the dashboard.
2. Navigate in the dashboard tree on the left to Projects > Project List.
3. Copy the app ID that you obtain from the dashboard into a text file. You will use this when you launch the app.

## Update and Run the Sample Application

1. Open the main.dart file and replace the app ID and token.

```const appId = "";
const token = "";
```

2. Install all the dependencies

```flutter pub get```

3. Once the build is complete, use the below given command to run the app. 

```flutter run```

## Resources

- You can find the complete API Documentation over [here](https://docs.agora.io/en/Video/API%20Reference/flutter/index.html).
- You can refer this [blog](https://medium.com/@tadaspetra/building-a-flutter-video-call-app-with-in-call-stats-bfb1e02abc0e) where I will walk you through the process of building a group video calling application.
