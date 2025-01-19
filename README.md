# ShoppingEvent Project

Welcome to the ShoppingEvent project! This project is designed to demonstrate the integration of modern Android development technologies, including Room persistence library, Dependency Injection with HILT, Compose Navigation, and database CRUD operations with SQL queries.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)

---

## Introduction
ShoppingEvent is a sample Android application that leverages cutting-edge tools to manage events related to shopping lists. The application highlights the use of modern development practices like Dependency Injection, Jetpack Compose for UI, and Room for data persistence.

---

## Features
1. **Room Persistence Library**:
   - Manage local data storage.
   - Simplify database operations with DAO.
   - Support for SQL queries for custom operations.

2. **Dependency Injection with HILT**:
   - Easy setup and management of dependencies.
   - Enhance scalability and testability.

3. **Database CRUD Operations**:
   - Create, Read, Update, Delete operations for shopping events.
   - Efficient handling of local data.

4. **SQL Queries**:
   - Execute complex and custom queries to retrieve specific data.
   - Optimize database performance with indexed queries.

5. **Compose Navigation**:
   - Navigate between screens with Jetpack Compose.
   - Seamless and declarative UI transitions.

---

## Technologies Used
- **Programming Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Dependency Injection**: HILT
- **Database**: Room Persistence Library
- **Build Tool**: Gradle
- **Testing**: JUnit, Espresso

---
## Dependencies and Plugins

### Room Dependencies and Plugins
Room is a persistence library that provides an abstraction layer over SQLite to allow for more robust database access while harnessing the full power of SQLite.

**Dependencies:**
```gradle
implementation "androidx.room:room-runtime:2.6.1"
kapt "androidx.room:room-compiler:2.6.1"
implementation "androidx.room:room-ktx:2.6.1"
```

For more information, refer to the [official Room documentation](https://developer.android.com/training/data-storage/room).

### Kotlin Symbol Processing (KSP) Plugin
KSP is a Kotlin compiler plugin that provides a powerful, yet simple API to process Kotlin source files.

**Plugin:**
```gradle
id 'com.google.devtools.ksp' version '<latest_version>'
```

For more details, check the [KSP Quickstart guide](https://kotlinlang.org/docs/ksp-quickstart.html).

### Hilt Dependencies and Plugins
Hilt is a dependency injection library for Android that reduces the boilerplate of doing manual dependency injection in your project.

**Dependencies:**
```gradle
implementation "com.google.dagger:hilt-android:2.55"
kapt "com.google.dagger:hilt-compiler:2.55"
```

**Plugin:**
```gradle
id 'com.google.dagger.hilt.android'
```

For additional information, visit the [Hilt documentation](https://developer.android.com/training/dependency-injection/hilt).

### Navigation with Compose Dependencies
Navigation with Compose simplifies the implementation of navigation within a Jetpack Compose application.

**Dependencies:**
```gradle
implementation "androidx.navigation:navigation-compose:2.8.5"
implementation "androidx.hilt:hilt-navigation-compose:1.2.0"
```

For more information, see the [Compose Navigation documentation](https://developer.android.com/develop/ui/compose/navigation) and [Hilt Navigation Compose guide](https://developer.android.com/develop/ui/compose/libraries#hilt).

### Kotlinx Serialization Dependency
Kotlinx Serialization provides a simple and efficient way to serialize and deserialize data in Kotlin applications.

**Dependency:**
```gradle
implementation "org.jetbrains.kotlinx:kotlinx-serialization-json:1.8.0"
```

**Plugin:**
```gradle
id 'org.jetbrains.kotlin.plugin.serialization' version '<latest_version>'
```

For more information, refer to the [Kotlinx Serialization documentation](https://kotlinlang.org/docs/serialization.html#formats).



## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ShoppingEvent.git
   ```

2. Open the project in Android Studio.

3. Sync Gradle and install dependencies.

4. Build and run the application on an emulator or device.

---

## Usage
### Room Persistence
- Define entities for shopping events.
- Use DAO interfaces to perform database operations.

### Dependency Injection with HILT
- Annotate classes with `@Inject` and `@HiltViewModel`.
- Provide dependencies using `@Module` and `@Provides` annotations.

### SQL Queries
- Write custom SQL queries in DAO interfaces using `@Query` annotation.

### Compose Navigation
- Define navigation destinations with `NavHost`.
- Pass arguments between screens easily.



Thank you for checking out the ShoppingEvent project. Happy coding!

