<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

A Flutter package for selecting date and time while excluding weekends (Saturdays and Sundays). This package ensures that users can only pick weekdays and prevents the selection of past dates.

## Features
Date picker that automatically skips weekends.
Integrated time picker.
Customizable and easy to integrate into your Flutter project.

## Getting started

Add samore_weekenddatetime_picker to your pubspec.yaml file:
dependencies:
  flutter:
    sdk: flutter
  samore_weekenddatetime_picker: ^1.0.0

Then, run:
flutter pub get

## Usage

Here's how to use the samore_weekenddatetime_picker package in your Flutter application.

Step 1: Add the Dependency
First, add samore_weekenddatetime_picker as a dependency in your pubspec.yaml file:

Step 2: Import the Package
In your Dart file, import the package:

Step 3: Use the DateTimePickerExample Widget
You can integrate the DateTimePickerExample widget into your Flutter app to allow users to select a date and time, excluding weekends (Saturday and Sunday).

Customizing the Picker
The DateTimePickerExample widget allows you to:

Select a date: The date picker excludes Saturdays and Sundays, ensuring users select valid weekdays.
Select a time: The time picker allows users to choose a specific time.
Display the selected date and time: The selected values are displayed in a user-friendly format (e.g., dd/MM/yyyy hh:mm a).


<!-- ```dart
const like = 'sample';
``` -->

## Additional information
Selectable Days: The date picker ensures that weekends (Saturday and Sunday) are not selectable. This feature is particularly useful in applications where certain operations or events cannot occur on weekends.

Customizable: While the current implementation excludes weekends, you can easily modify the selectableDayPredicate function to suit your specific requirements, such as excluding holidays or other specific dates.

State Management: The package uses StatefulWidget and StatefulBuilder to manage the internal state of the date and time pickers, making it easy to adapt the widget to more complex use cases.

Internationalization: The package leverages the intl package to format the date and time according to the user's locale, ensuring the widget is ready for international applications.

Platform Support: This package is designed to work seamlessly across Android, iOS, and other platforms supported by Flutter.
    

## Example Screenshot

![DateTime Picker Example](https://drive.google.com/file/d/1GFQUZQDKcpdImoTbDzAehg7OKWr3i7vZ/view?usp=sharing)

![DateTime Picker Example](https://drive.google.com/file/d/1LxoSe3Sss2K0WkpNnvKiH47LlqinMsiI/view?usp=sharing)# samore_weekenddatetime_picker
