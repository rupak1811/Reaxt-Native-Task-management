# My Tasks - React Native Task Management App

A beautiful and functional task management app built with React Native and Expo, featuring smooth animations and a modern UI. This app helps you stay organized and productive with an intuitive interface and powerful features.

<div align="center">
  <img src="https://github.com/user-attachments/assets/a3bbef5e-4439-4420-a488-468aa3857444" alt="Screenshot 1" width="150"/>
  <img src="https://github.com/user-attachments/assets/0693559f-0d2a-4ed9-b4ef-1755756641ec" alt="Screenshot 2" width="150"/>
  <img src="https://github.com/user-attachments/assets/22666105-54e8-4c01-9b21-ead8ebb987bb" alt="Screenshot 3" width="150"/>
  <img src="https://github.com/user-attachments/assets/038fdee9-5e8b-4859-b3dc-1e3af0a26fb0" alt="Screenshot 4" width="150"/>
  <img src="https://github.com/user-attachments/assets/5f411479-965c-4214-8148-90517e3851f5" alt="Screenshot 5" width="150"/>
  <img src="https://github.com/user-attachments/assets/1f8a64d9-dbd5-4189-83f4-490861cafc3a" alt="Screenshot 6" width="150"/>
</div>

### Screenshot Explanations

- **Screenshot 1**: The initial empty state of the task list, ready for new tasks to be added.
- **Screenshot 2**: A task has been added ("Project work"), showing the option to edit or delete it, along with the keyboard for input.
- **Screenshot 3**: The "Edit Task" modal, allowing the user to modify the task name and set its priority (High, Medium, Low).
- **Screenshot 4**: Another task ("Chat application") has been added, and a notification for "Chat application" is visible at the top, demonstrating the reminder feature.
- **Screenshot 5**: The "Project work" task has been marked as complete, indicated by the checkmark icon.
- **Screenshot 6**: The "Project work" task has been successfully deleted from the list, leaving only "Chat application" remaining.

---

## Features

### Core Functionality
- Beautiful and modern UI with smooth animations
- Add, complete, and delete tasks
- Local notifications for task reminders
- Persistent storage using AsyncStorage
- Cross-platform support (iOS & Android)

### Task Management
- Create new tasks with a simple tap
- Mark tasks as complete with a satisfying animation
- Delete tasks with a swipe gesture
- View all your tasks in a clean, organized list
- Tasks persist between app sessions

### Notifications
- Smart notification system for task reminders
- Customizable notification timing
- Automatic notification cancellation for completed tasks
- Permission management for notifications

### User Experience
- Smooth animations for all interactions
- Intuitive gesture controls
- Clean and modern design
- Responsive layout for all screen sizes
- Dark mode support

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or newer)
- npm or yarn package manager
- Expo CLI (`npm install -g expo-cli`)
- iOS Simulator (for Mac users) or Android Emulator
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd my-tasks
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Run on your preferred platform**
   - Press `i` to open in iOS simulator
   - Press `a` to open in Android emulator
   - Scan the QR code with Expo Go app on your physical device

---

## Usage Guide

### Adding Tasks
1. Open the app
2. Type your task in the input field at the bottom
3. Tap the + button or press Enter to add the task
4. A notification will be scheduled automatically

### Managing Tasks
- **Complete a task**: Tap the circle icon next to the task
- **Delete a task**: Tap the trash icon or swipe left
- **View completed tasks**: They appear with a strikethrough effect

### Notifications
- The app will request notification permissions on first launch
- Each new task triggers a reminder notification
- Notifications are automatically cancelled when a task is marked complete

## Technologies Used

- **React Native** - Core framework
- **Expo** - Development platform
- **Expo Notifications** - Push notification system
- **AsyncStorage** - Local data persistence
- **React Native Reanimated** - Advanced animations
- **React Native Gesture Handler** - Touch interactions

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m "Add some AmazingFeature"`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or suggestions, please open an issue in the repository.

---

Made with ❤️ using React Native and Expo
