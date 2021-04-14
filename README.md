# School Management System
 
### State Management: [Provider](https://pub.dev/packages/provider) + [Get_it](https://pub.dev/packages/get_it)

### MVVM(Model-View-(View)Model) Architecture

### Note: This app is not fully developed, it still has a lot of bugs and I'm still working on it (For now all the login data for parent, teacher and student are added manually in firestore)

### [Web Portal](https://github.com/3mdikram/School-Management-System-App) is under development.

#### There are backend firebase functions too written in Typescript for some automation and some functions to make them work with web based project(future proof)

 School Management System is the app build for iOS and Android using Flutter.

It uses Firebase FireStore as Database and Firebase Storage.

## FeatureS

|  UI  | Logic | Feature |
| ------ | ------ | ------|
| ✔ | ✔ | Teacher Login
| ✔ | ✔ | Student Login
| ✔ | ✔ | Parent Login
| ✔ | ✔ | Multiple Child Profile View
| ✔ | ✔ | Chat between teacher and parent
| ✔ | ✔ | Intro Screens.
| ✔ | ✔ | Post photo or notice on Standard post section(Only Teacher)
| ✔ | ✔ | Post photo or notice on global post section(Only Teacher)
| ✔ | ✔ | Dark Mode
| ✔ | ✔ | Profile Setup
| ✔ | ✔ | Forget Password
| ✔ |  | TimeTable
### and many more......

## Screenshots

![Screenshot_1](https://user-images.githubusercontent.com/54524364/114696580-6f8b5b80-9d3a-11eb-8e7c-f0e402438285.png)

![Screenshot_2](https://user-images.githubusercontent.com/54524364/114696618-7ade8700-9d3a-11eb-9ee1-9d903c55f595.png)

## Database

Database structure snapshot are [here](https://github.com/3mdikram/School-Management-System-App/tree/main/DB%20Structure)

A full database documentation will be created soon..

## Server.dart 

You need to create this and put in /core/ folder. \
This File is necessary in order to make Cloud Functions work.

```dart
class Server {
  static String baseUrl =
      YOUR-CLOUD-FUNCTION-URL;
  static String webApi = 'webApi/';
  static String profileUpdate = 'profileupdate';
  static String getProfileData = 'userdata';
  static String postAnnouncement = 'postAnnouncement';
  static String addAssignment = 'addAssignment';
}
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
