Notes App
Welcome to the Notes App! This app is built using Flutter, incorporating Cubit for state management and Hive for local storage. The Notes App is designed to help you efficiently create, organize, and manage your notes. Whether you need to jot down quick thoughts, create to-do lists, or save important information, this app provides a simple yet powerful interface to keep everything at your fingertips.
 Key Features
- Create and Edit Notes: Quickly add new notes and make edits to existing ones.
- Local Storage: All notes are stored locally using Hive, ensuring fast and reliable access without requiring internet connectivity.

Why Use Flutter with Cubit and Hive?
Flutter: Provides a rich set of pre-designed widgets, ensuring a smooth and attractive user interface across both Android and iOS platforms.
Cubit: A lightweight and intuitive state management solution that ensures your app’s state is managed efficiently and predictably.
Hive: A fast and lightweight key-value database optimized for Flutter, providing efficient local storage without the need for complex setup or configuration.

Project Structure
The project follows a structured directory layout to keep the code organized and maintainable:
notes-app/
|- android/
|- ios/
|- assets/
|- lib/
|  |- cubit/
|  |  |- note_cubit.dart
|  |  |- note_state.dart
|  |- models/
|  |- views/
|  |- widgets/
|  |- main.dart
|- test/
|- pubspec.yaml
|- README.md

cubit/: Contains the Cubit classes for state management.
models/: Contains data models used in the app.
views/: Contains the UI screens of the app.
widgets/: Contains reusable widgets.
main.dart: The entry point of the app.


Dependencies
The project utilizes several Flutter packages to enhance functionality and maintain performance:

flutter_bloc: For state management using Cubit.
hive: Lightweight and fast key-value database.
hive_flutter: Hive integration for Flutter.

