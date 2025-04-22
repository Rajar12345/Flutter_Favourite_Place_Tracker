# Flutter_Favourite_Place_Tracker

# Great Places App

This Flutter application allows users to create and manage a list of their favorite places. Users can add new places with a title, image, and location. The app uses native device features to capture images and get the current location. Places are stored locally using SQLite.

## Features

* **Add a New Place:** Capture an image and get the current location of a new place.
* **View Place Details:** See the image, location, and other details of a place.
* **List of Places:** Browse all added places.
* **Local Storage:** Persist places on the device using SQLite.

## Technologies Used

* **Flutter:** The UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
* **Dart:** The programming language used to write Flutter apps.
* **SQLite:** A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
* **`image_picker`:** A Flutter plugin for picking images from the image library, or taking new pictures with the camera.
* **`location`:** A Flutter plugin to get location information.
* **`path_provider`:** A Flutter plugin for finding commonly used locations on the filesystem.
* **`sqflite`:** A Flutter plugin for SQLite database access.

## How to Run

1.  **Clone the repository:** `git clone <repository-url>`
2.  **Get dependencies:** Navigate to the project directory and run `flutter pub get`.
3.  **Run the app:** Connect a device or start an emulator and run `flutter run`.

## How to Contribute

1.  **Fork the repository.**
2.  **Create a new branch:** `git checkout -b feature/your-feature-name`
3.  **Make your changes.**
4.  **Commit your changes:** `git commit -m "Add some feature"`
5.  **Push to the branch:** `git push origin feature/your-feature-name`
6.  **Open a pull request.**
