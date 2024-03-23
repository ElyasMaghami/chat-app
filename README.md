# Flutter Chat Application

A real-time chat application built with Flutter and Firebase. This application allows users to send and receive text messages, images, and other multimedia content in real-time.

## Features

- User authentication: Users can sign up, sign in, and sign out securely using Firebase Authentication.
- Real-time messaging: Users can send and receive messages instantly using Firebase Cloud Firestore.
- Image sharing: Users can share images from their device's gallery using the Image Picker plugin.
- Push notifications: Users receive push notifications for new messages using Firebase Cloud Messaging.
- Cloud storage: Images shared in the chat are stored securely in Firebase Cloud Storage.


## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Set up a Firebase project and add the necessary configuration files to your Flutter project.
3. Ensure that you have the Flutter SDK installed on your machine.
4. Run `flutter pub get` to install the required dependencies.
5. Run the app using `flutter run`.

## Dependencies

- [cupertino_icons](https://pub.dev/packages/cupertino_icons): Icons used in the Cupertino style.
- [firebase_core](https://pub.dev/packages/firebase_core): Flutter plugin for Firebase Core, enabling connecting to multiple Firebase apps.
- [firebase_auth](https://pub.dev/packages/firebase_auth): Flutter plugin for Firebase Authentication.
- [firebase_storage](https://pub.dev/packages/firebase_storage): Flutter plugin for Firebase Cloud Storage, used for storing images.
- [image_picker](https://pub.dev/packages/image_picker): Flutter plugin for selecting images from the device's gallery.
- [cloud_firestore](https://pub.dev/packages/cloud_firestore): Flutter plugin for Firebase Cloud Firestore, used for real-time database functionality.
- [firebase_messaging](https://pub.dev/packages/firebase_messaging): Flutter plugin for Firebase Cloud Messaging, used for push notifications.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
