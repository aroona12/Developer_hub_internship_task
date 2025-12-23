# Developer Hub Flutter Tasks (Week 1–3)

## 📱 Project Overview
This Flutter project is developed as part of **Developer Hub tasks**, covering **Week 1 to Week 3** objectives.  
All weekly tasks are implemented within **a single Flutter project**, where each phase builds upon previously learned concepts, resulting in a **fully functional task management application** with clean and enhanced UI.

The project demonstrates practical understanding of Flutter fundamentals including UI design, navigation, state management, and local data persistence using `SharedPreferences`.

---

## 🗂 Project Structure
The project consists of multiple screens corresponding to each task phase:

lib/
├── main.dart
├── login_screen.dart
├── home_screen.dart
├── counter_app.dart
├── simple_todo.dart
├── main_screen.dart
├── task_screen.dart
└── completed_task_screen.dart
---

## 🟦 Week 1: Basic Flutter Development & UI Building

### 🔹 Learning Focus
- Flutter project structure
- UI development using core widgets
- Screen navigation
- Form validation

### 🔹 Implemented Features
- Login screen with:
  - Email and password input fields
  - Input validation
  - Login button
  - “Forgot Password?” text
- Navigation from Login Screen to Home Screen using `Navigator.push()`
- Responsive UI using:
  - `Column`, `Row`, `Container`, `Card`, `TextFormField`

---

## 🟦 Week 2: State Management & Persistent Storage

### 🔹 Learning Focus
- Widget state management using `setState`
- Local data persistence
- List rendering

### 🔹 Implemented Features
#### ✅ Counter App
- Increment and decrement counter
- Counter value stored using `SharedPreferences`
- Value persists after app restart

#### ✅ Simple To-Do App
- Add tasks
- Display tasks using `ListView`
- Store tasks locally using `SharedPreferences`

---

## 🟦 Week 3: Final Task Management Application

### 🔹 Learning Focus
- Integrating multiple Flutter concepts into one app
- Data persistence
- UI enhancement and navigation
- Testing and debugging

### 🔹 Final App Features
- **Main Task Screen**
  - Displays all tasks with title, date, and availability level
  - Dynamic task count shown in the AppBar
  - Checkbox to mark tasks as completed
  - Delete task with confirmation dialog

- **Add / Update Task Screen**
  - Add new tasks with:
    - Title
    - Date selection using DatePicker
    - Availability level (High, Medium, Low)
  - Update existing tasks
  - Input validation with Snackbar feedback

- **Completed Tasks Screen**
  - Separate screen to display completed tasks only
  - Completed tasks shown with strike-through text
  - Data retrieved from persistent storage

- **Data Persistence**
  - All task data stored locally using `SharedPreferences`
  - Task completion state maintained across app restarts

- **UI Enhancements**
  - Custom AppBar
  - Floating Action Button for adding tasks
  - Icons and cards for improved user experience

---

## 🛠 Technologies Used
- Flutter (Stable Channel)
- Dart
- SharedPreferences
- Material Design Widgets

---

## 🚀 How to Run the Project
1. Clone the repository
2. Run the following commands:
   ```bash
   flutter pub get
   flutter run
3. Ensure an Android device or emulator is connected