# Task Manager App

A simple task management application built with React Native and Expo, allowing users to manage their daily tasks efficiently.

## Features

- Add new tasks with descriptions
- Mark tasks as complete/incomplete with visual feedback
- Delete tasks from the list
- Clean and intuitive user interface
- Real-time task list updates

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Alinapanyue/TaskManager.git
   cd TaskManager
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npx expo start
   ```

4. Run the app:
   - Scan the QR code with Expo Go app (iOS/Android)
   - Press 'i' for iOS simulator
   - Press 'a' for Android emulator

## Usage Guide

- **Adding Tasks**: Enter your task in the input field at the top and press "Add"
- **Completing Tasks**: Tap the circle next to a task to mark it as complete/incomplete
- **Deleting Tasks**: Tap the "✖" button on the right of any task to remove it
- **Task Status**: Completed tasks are shown with a filled circle and strikethrough text

## Technologies Used

- React Native - Core framework for building the mobile app
- Expo - Development platform and build tools
- TypeScript - For type-safe JavaScript code
- React Hooks - For state management (useState)

## Project Structure

- `app/(tabs)/index.tsx`: Main application component containing task management logic
- Uses React Native's built-in components for a native UI experience
- Implements local state management using useState for task data
- Follows TypeScript best practices for type safety
