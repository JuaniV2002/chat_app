# Chat app

This Chat app will allow users to sign up or login through an authentication screen and then chat with other users. This app is channel-based and with push notifications enabled (pleas read [here]()).
## Important note

Since this app uses external packages like an image picker, Firebase and Firestore, depending on your target platform, you should do some extra steps to make it work. Visit this links to know more:
- [Image picker package](https://pub.dev/packages/image_picker#ios)
- [Firebase SDK for Flutter](https://firebase.google.com/docs/flutter/setup?platform=ios)
- [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/flutter/client)

## Screenshots

<table>
    <tr>
        <td>
            <img src="/assets/images/auth_screen.jpg" width="300">
        </td>
        <td>
            <img src="/assets/images/chat_screen.jpg" width="300">
        </td>
    </tr>
</table>

## Try my app!

The attached files **DO NOT** work as a standalone project, they are just the code I wrote (lib folder), pubspecs (dependencies) and assets (fonts to add style to the app).  

To give the app a try:
-  [Download the Flutter SDK and Android Studio or Xcode](https://docs.flutter.dev/get-started/install).
-  Start a virtual device in Android Studio or Xcode.
-  Clone my repository and move to that location in your terminal.
-  Run `flutter create .` in the terminal. (this will create all the app dependencies).
-  Run `flutter run`. The virtual device will open the app automatically.
-  That's it!