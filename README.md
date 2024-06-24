# MY NOTES - Task Management App

## Overview
My Notes is a dynamic task management mobile application developed using Android Studio and Kotlin. The app demonstrates key components of Android development, including SQLite databases with Room library, Kotlin Coroutines, RecyclerView, and ViewModel architecture. This project aims to provide a user-friendly interface for managing tasks, allowing users to add, delete, update, and view tasks efficiently.

## Objectives
The primary objective of this project is to develop a mobile application that:
  * Implements an intuitive user interface for task management.
  * Utilizes SQLite databases for local data storage using Room library.
  * Performs asynchronous database operations using Kotlin Coroutines.
  * Adopts ViewModel architecture for efficient data management and UI separation.

## Requirements
1. Task Management Interface
   * User Interface: Design and implement an intuitive UI for managing tasks.
       * Options to add new tasks, view existing tasks, update task details, and delete tasks.
       * Use RecyclerView to display a list of tasks in a scrollable format.
    
2. SQLite Database Integration
   * Room Library: Implement SQLite database using Room library for local storage.
       * Define an Entity for tasks with properties like task name, description, and priority.
       * Set up a Data Access Object (DAO) for performing CRUD operations on the task database.
    
3. Kotlin Coroutines
   * Asynchronous Operations: Utilize Kotlin Coroutines for database operations.
       * Implement Coroutines for inserting, updating, deleting, and querying tasks.
       * Ensure long-running operations are executed off the main UI thread to maintain responsiveness.
    
4. ViewModel Architecture
   * Separation of Concerns: Implement ViewModel architecture to separate UI-related data from UI logic.
       * Create a ViewModel class to encapsulate UI data and business logic related to task management.
       * Use LiveData or Flow to observe changes in task data and update the UI accordingly.
    
5. User Interaction
   * Functionalities: Implement user interaction functionalities.
       * Adding new tasks with details such as name, description, and priority.
       * Viewing the list of tasks with options to sort or filter based on priority
       * Updating task details such as name, description, or priority.
       * Deleting tasks from the list.

## Getting Started
### Prerequisites
* Android Studio installed
* Basic knowledge of Android development

### Installation
1. Clone the repository:
   ```
   https://github.com/kavindya-pabasara/Task-Management-App.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Build and run the app on an Android device or emulator.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any enhancements, bug fixes, or new features.
