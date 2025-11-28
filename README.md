A Flutter implementation of a cryptocurrency portfolio management interface, based on a design concept from Uplabs.

## Overview

This Flutter project demonstrates a clean, modern UI for tracking cryptocurrency portfolios with support for both light and dark themes.

## Features

- **Dual Theme Support**: Seamlessly switch between light and dark modes
- **Responsive Design**: Optimized for various screen sizes
- **Portfolio Tracking**: Visual representation of cryptocurrency holdings
- **Performance Charts**: Display asset performance over time


## Getting Started

### Prerequisites

- Flutter SDK (latest stable version recommended)
- IDE with Flutter support (Android Studio, VS Code, or IntelliJ)
- Basic understanding of Dart and Flutter

### Installation

1. Clone the repository:
```bash
git clone https://github.com/hearclin/cryptocurrency-flutter-ui.git
```

2. Navigate to the project directory:
```bash
cd cryptocurrency-portfolio-ui
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the application:
```bash
flutter run
```

## Theme Configuration

To switch between themes, modify the `isDark` variable in `lib/main.dart`:

```dart
bool isDark = true; // For dark theme
bool isDark = false; // For light theme
```

## Project Structure

```
lib/
├── main.dart          # Application entry point
├── models/            # Data models
├── screens/           # Main application screens
├── widgets/           # Reusable UI components
├── theme/             # Theme configuration
└── utils/             # Utility functions
```

## Assets

- Application icons and images located in `assets/` directory
- Screenshots in `ss/` directory

## Contributing

Contributions are welcome. Please feel free to submit pull requests or open issues for discussion.

## Development

This project was developed using:
- Flutter framework
- Dart programming language
- Material Design components

