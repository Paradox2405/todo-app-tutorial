# Flutter To-Do App

A Flutter to-do list backed by Firebase, built while following a tutorial. Each user signs up, then adds, edits, completes and deletes their own tasks, which sync in real time through Cloud Firestore.

## Features

- Sign up and login with Firebase Authentication
- Add tasks with a title, subtitle and image tag
- Edit tasks, mark them done and delete them
- Real-time task list with a Firestore stream

## Tech stack

Flutter (Dart), Firebase Authentication, Cloud Firestore, `uuid`

## Project structure

```
lib/
  auth/       auth page and auth state switch
  data/       auth and Firestore operations
  model/      note model
  screen/     home, login, sign up, add and edit task
  widgets/    task tile, task stream
images/       task images
```

## Getting started

```bash
flutterfire configure     # writes lib/firebase_options.dart for your project
flutter pub get
flutter run
```
