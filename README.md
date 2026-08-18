# GitJira

An Android sample application built with **Jetpack Compose** and **Material3**, created as a practice project for Git and Jira workflow integration.

## Overview

GitJira is a modern Android app that demonstrates:
- Jetpack Compose UI with Material3 design
- Edge-to-edge display support
- Standard Android project structure following best practices

## Tech Stack

| Technology | Version |
|---|---|
| Android Gradle Plugin | 8.9.1 |
| Kotlin | 2.0.21 |
| Jetpack Compose BOM | 2024.09.00 |
| Material3 | Latest (via BOM) |
| Min SDK | 36 |
| Target SDK | 36 |
| Java | 11 |

## Key Dependencies

- **AndroidX Core KTX** 1.15.0
- **Lifecycle Runtime KTX** 2.8.7
- **Activity Compose** 1.13.0
- **Navigation Compose** 2.9.8
- **DataStore Preferences** 1.1.1
- **Kotlinx Serialization JSON** 1.6.3

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/gitjira/
│   │   │   ├── MainActivity.kt         # Entry point with Compose setup
│   │   │   └── ui/theme/               # Theme, colors, typography
│   │   ├── res/                        # Resources (drawables, layouts, values)
│   │   └── AndroidManifest.xml
│   ├── test/                           # Unit tests
│   └── androidTest/                    # Instrumented tests
└── build.gradle.kts
```

## Getting Started

### Prerequisites

- Android Studio Ladybug or later
- JDK 11+
- Android SDK 36

### Build & Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd GitJira
   ```

2. Open in Android Studio and let Gradle sync complete.

3. Run on an emulator or physical device:
   ```bash
   ./gradlew installDebug
   ```

### Run Tests

```bash
# Unit tests
./gradlew test

# Instrumented tests (requires connected device/emulator)
./gradlew connectedAndroidTest
```

## Build Variants

| Variant | Description |
|---|---|
| `debug` | Development build with full debug symbols |
| `release` | Optimized build with ProGuard configuration |

## Contributing

1. Create a feature branch from `main`
2. Make your changes
3. Submit a Pull Request with a clear description
4. Link the relevant Jira ticket in the PR description

## License

This project is for practice and learning purposes.
