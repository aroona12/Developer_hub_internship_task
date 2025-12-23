---
# Developer Hub Flutter Tasks (Week 1–3)

## 📱 Project Overview
This Flutter project is developed as part of **Developer Hub tasks**, covering **Week 1 to Week 3** objectives.  
All tasks are implemented within **a single Flutter project**, where each week focuses on building upon the previous concepts, resulting in a **functional task management application** with clean and enhanced UI.

The project demonstrates fundamental to intermediate Flutter concepts including UI design, navigation, state management, and local data persistence.

---

## 🗂 Project Structure
The project contains multiple screens and modules corresponding to each week’s tasks:

```

lib/
├── main.dart
├── login_screen.dart
├── home_screen.dart
├── counter_app.dart
├── simple_todo.dart
└── final_task_app.dart

````

---

## 🟦 Week 1: Basic Flutter Development & UI Building

### 🔹 Learning Focus
- Flutter project structure
- UI building using core widgets
- Navigation between screens
- Form validation

### 🔹 Implemented Features
- Login screen with:
  - Email & password fields
  - Input validation
  - Login button
  - “Forgot Password?” text
- Navigation from Login Screen to Home Screen using `Navigator.push()`
- Clean and responsive UI using:
  - `Column`, `Row`, `Container`, `Card`, `TextFormField`

---

## 🟦 Week 2: State Management & Persistent Storage

### 🔹 Learning Focus
- Widget state management using `setState`
- Local data persistence
- Working with lists

### 🔹 Implemented Features
#### ✅ Counter App
- Increment & decrement counter
- Counter value saved using `SharedPreferences`
- Data persists even after app restart

#### ✅ Simple To-Do App
- Add tasks
- Display tasks using `ListView`
- Save and retrieve tasks using `SharedPreferences`

---

## 🟦 Week 3: Final Task Management App

### 🔹 Learning Focus
- Combining multiple Flutter concepts
- UI enhancement
- Debugging and testing

### 🔹 Final App Features
- Home screen displaying task list
- Add new tasks via dialog
- Mark tasks as complete
- Delete tasks
- Persistent storage using `SharedPreferences`
- Custom AppBar with action buttons
- Icons for better user experience

---

## 🛠 Technologies Used
- Flutter (Stable Channel)
- Dart
- SharedPreferences
- Material UI Widgets

---

## 🚀 How to Run the Project
1. Clone the repository
2. Run the following commands:
   ```bash
   flutter pub get
   flutter run
````


