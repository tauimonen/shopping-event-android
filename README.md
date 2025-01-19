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

