# Mood Diary

Mood Diary is a mobile application developed with Flutter as a school project that allows users to track their mood in a visual format. The application enables users to record their mood by day and add optional notes. The data is stored locally on the device and displayed in weekly and monthly charts. The application was developed and tested using an Android emulator.

---

## Features

- Add mood entries by selecting an emoji
- Add notes to each entry
- View entries in weekly or monthly bar charts
- Calendar view for viewing entries for a selected day
- Delete entries from the calendar
- Switch between light and dark themes
- Reset all data
- Local data storage using the Hive database

---

## Technologies Used

- Flutter
- Hive – local database
- Hive_Flutter – Flutter integration for Hive
- ThemeProvider – theme management
- FL_Chart – charts
- table_calendar – calendar

---

## Installation and Setup

### 1. Requirements

- Flutter SDK (version 3.x or newer)
- Dart
- Android Studio / VS Code or another Flutter development environment
- Android/iOS emulator or physical device

### 2. Installation

```bash
git clone https://github.com/essigranath/mood_diary
cd mood_diary
flutter pub get
```

### 3. Verify That Flutter Is Working

```bash
flutter doctor
```

### 4. Start an Android Emulator

- Open Android Studio
- Go to More Actions > Device Manager
- Create a new virtual device if you do not already have one
- Select the emulator and click Start

### 5. Run the Application

```bash
flutter run
```
