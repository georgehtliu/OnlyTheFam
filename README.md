# OnlyTheFam

A modern family organization app that helps families stay connected, organized, and informed. Manage events, track todos, and keep important family information in one beautiful, easy-to-use place.

## Overview

OnlyTheFam was built to solve a personal need: keeping my family coordinated and in sync. Whether it's tracking upcoming events, managing shared todos, or having quick access to important family member information, this app brings everything together in a single, intuitive interface.

## Features

- **📅 Calendar & Events** - View and manage family events with a clean calendar interface
- **✅ Todos & Tasks** - Keep track of family todos and see what's coming up
- **👨‍👩‍👧‍👦 Family Profiles** - Store and access important family member information including health details, birthdays, and contact info
- **💬 Daily Reminders** - Get inspired with daily family-focused quotes and tips
- **📱 Modern UI** - Beautiful, responsive design built with Jetpack Compose
- **🔐 Secure** - Family data is protected with user authentication

## Tech Stack

### Mobile App
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: MVVM with Navigation Component
- **Networking**: Ktor Client with Kotlinx Serialization
- **Image Loading**: Coil

### Backend Server
- **Framework**: Ktor (Kotlin)
- **Database**: PostgreSQL
- **ORM**: Exposed
- **Serialization**: Kotlinx Serialization, Gson

## Project Structure

```
OnlyTheFam/
├── app/                    # Android mobile application
│   └── src/main/java/...   # Main app source code
└── server/                 # Backend server application
    └── src/main/kotlin/... # Server source code
```

## Getting Started

### Prerequisites

- Android Studio (latest version recommended)
- JDK 8 or higher
- PostgreSQL database
- Android device or emulator (API 21+)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/OnlyTheFam.git
   cd OnlyTheFam
   ```

2. **Configure the backend**
   - Set up a PostgreSQL database
   - Update database connection settings in the server configuration
   - Run the server:
     ```bash
     cd server
     ./gradlew run
     ```

3. **Configure the mobile app**
   - Update the server IP address in the app configuration
   - Open the project in Android Studio
   - Sync Gradle files and wait for dependencies to download
   - Run the app on an emulator or connected device

## Development

This project uses:
- Gradle for dependency management and building
- Kotlin Multiplatform for shared code (future)
- Modern Android development practices

## Contributing

This is a personal project, but suggestions and feedback are always welcome! Feel free to open an issue or submit a pull request.

## License

This project is open source and available for personal use and learning.

---

Built with ❤️ for keeping families connected
