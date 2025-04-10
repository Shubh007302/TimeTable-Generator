# School Timetable Generator

A Flutter application for generating and managing school timetables. This app allows educational institutions to create customized timetables for multiple classes with configurable subjects, periods, and time slots.



## Features

- Configure days (1-7) and periods per day (1-12)
- Manage multiple classes simultaneously
- Define subjects with custom colors and lecture requirements
- Set specific time slots for periods
- Configure lunch breaks
- Export timetables as PDF (per class or all classes)
- Share generated timetables


## Dependencies

- [Flutter](https://flutter.dev/) - UI toolkit
- [pdf](https://pub.dev/packages/pdf) - PDF generation
- [path_provider](https://pub.dev/packages/path_provider) - File system access
- [share_plus](https://pub.dev/packages/share_plus) - Content sharing
- [flutter_colorpicker](https://pub.dev/packages/flutter_colorpicker) - Color selection

## How It Works

1. **Initial Setup**: Configure the number of working days, periods per day, subjects, and classes
2. **Subject Configuration**: Define subjects with names, colors, and required lecture count
3. **Class Setup**: Add class details including name
4. **Time Settings**: Configure period timings and lunch break (optional)
5. **Timetable Generation**: The app automatically generates a timetable based on inputs
6. **Export**: Export the timetable as PDF for individual classes or all classes

## Development

The app is structured as follows:

- `lib/models/` - Data models
- `lib/screens/` - UI screens
- `lib/utils/` - Utility functions and generators
- `lib/widgets/` - Reusable UI components



