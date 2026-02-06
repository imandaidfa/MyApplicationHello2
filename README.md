# MyApplicationHello2

A modern Android application built with Jetpack Compose and Material 3. This project demonstrates a standard entry-point setup with edge-to-edge UI support using the latest Android development tools.

## Build Requirements

This project is specifically configured to build with the following environment:

- **Android Studio**: Android Studio Otter 3 Feature Drop | 2025.2.3
  - Build #AI-252.28238.7.2523.14688667, built on January 9, 2026
- **Runtime Version**: 21.0.8+-14196175-b1038.72 amd64
- **VM**: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
- **Operating System**: Windows 10.0

## Tech Stack

| Component | Version / Detail |
| :--- | :--- |
| **Kotlin** | 2.0.21 |
| **Android Gradle Plugin** | 9.0.0 |
| **Jetpack Compose BOM** | 2024.09.00 |
| **Material Design** | Material 3 |
| **Minimum SDK** | 24 (Android 7.0) |
| **Target/Compile SDK** | 36 |

## Project Analysis (`app/build.gradle.kts`)

The application module is configured with the following key attributes:

- **Namespace**: `com.example.myapplicationhello2`
- **Application ID**: `com.example.myapplicationhello2`
- **Java Compatibility**: VERSION_11 (Source & Target)
- **Build Features**: Compose enabled
- **Key Dependencies**:
  - `androidx.core:core-ktx:1.10.1`
  - `androidx.activity:activity-compose:1.8.0`
  - `androidx.lifecycle:lifecycle-runtime-ktx:2.6.1`

## Architecture Overview

- **MainActivity**: Inherits from `ComponentActivity`, utilizing `enableEdgeToEdge()` for a modern immersive experience.
- **UI Layer**: Built entirely with Jetpack Compose, using a custom theme `MyApplicationHello2Theme`.
- **Styling**: Leverages Material 3 components like `Scaffold` for layout structure.

## Getting Started

1.  **Clone/Open**: Open the project folder in Android Studio Otter.
2.  **Sync**: Allow Gradle to sync and download dependencies.
3.  **Run**: Execute the `app` configuration on an emulator or device running API 24 or higher.
