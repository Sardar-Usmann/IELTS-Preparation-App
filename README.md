# AI-Powered IELTS Preparation App

An AI-powered IELTS preparation application built with **Flutter and Dart**, designed to help students practice English and prepare for the IELTS examination through interactive exercises, AI-assisted evaluation, and performance tracking.

The application brings together Reading, Writing, Listening, and Speaking practice in one cross-platform learning platform.

## Developed By

**Sardar Muhammad Usman**

- **GitHub:** [Sardar-Usmann](https://github.com/Sardar-Usmann)
- **Project Repository:** [IELTS Preparation App](https://github.com/Sardar-Usmann/IELTS-Preparation-App)

## Project Overview

The AI-Powered IELTS Preparation App provides a structured learning environment for students preparing for the IELTS examination. It combines interactive practice modules, artificial intelligence capabilities, Firebase integration, and progress-tracking features to support independent learning.

The project focuses on making IELTS preparation more accessible, interactive, and organized through a modern application interface.

## Features

### 1. IELTS Reading
- Reading practice and test interfaces
- Multiple reading tests
- Structured questions and navigation
- Reading comprehension practice

### 2. IELTS Writing
- Writing practice and test interfaces
- AI-assisted essay evaluation
- Writing feedback and result screens
- Tools to help students identify areas for improvement

### 3. IELTS Listening
- Listening practice tests
- Audio-based learning functionality
- Interactive test navigation
- Listening comprehension practice

### 4. IELTS Speaking
- Voice recording and speaking practice
- Speech-to-text functionality
- Text-to-speech support
- AI-assisted speaking analysis

### 5. AI-Powered Assessment
- AI-assisted writing evaluation
- Generative AI integration
- Automated response analysis
- Intelligent learning assistance

### 6. Authentication and User Accounts
- User registration and login
- Firebase Authentication integration
- User session management
- Account-related functionality

### 7. Dashboard and Progress Tracking
- Centralized learning dashboard
- Access to IELTS modules and quizzes
- Test results and statistics
- User profile and progress information

### 8. Quizzes and Gamification
- Interactive quizzes
- Score tracking
- Achievement-oriented learning features
- Gamification functionality to encourage consistent practice

## Application Screenshots

Explore the application's interface and learning experience.

<p align="center">
  <img src="https://github.com/user-attachments/assets/80e91914-650e-4134-b9b3-0d0e01d55e3c" alt="IELTS App Screenshot 1" width="300" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/33233d0d-d3dc-4e91-b53c-c703843c60a4" alt="IELTS App Screenshot 2" width="300" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c0bcd05a-b0cd-4baa-aa03-b41b85ff000c" alt="IELTS App Screenshot 3" width="300" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/aa89bd95-9273-4e4f-9dd7-ea0d38916de4" alt="IELTS App Screenshot 4" width="300" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/51f68cfa-6396-4876-ad48-11c2c7fc39d4" alt="IELTS App Screenshot 5" width="300" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/e0e13f46-b619-4df8-8c90-ad21faf923fb" alt="IELTS App Screenshot 6" width="300" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6dae2e03-63a5-4f24-954e-f5f50d3b6999" alt="IELTS App Screenshot 7" width="300" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/ec4c3fb5-578a-4bc8-86fa-d9d9582607d3" alt="IELTS App Screenshot 8" width="300" />
</p>

## Technology Stack

| Category | Technologies |
|---|---|
| Application Development | Flutter, Dart |
| Artificial Intelligence | Google Generative AI |
| Backend Services | Firebase |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| State Management | GetX |
| Local Storage | Shared Preferences |
| Speech and Audio | Speech-to-Text, Text-to-Speech, Audio Recording |
| UI and Animations | Material Design, Google Fonts, Flutter Animate |

## Application Architecture

The application uses a modular architecture that separates the user interface, application logic, data models, and supporting services.

```text
User Interface
      |
      v
Screens and Widgets
      |
      v
Controllers and Application Logic
      |
      v
Models, Services and Utilities
      |
      v
Firebase, AI Services and Local Storage
```

This structure helps organize application functionality and supports future maintenance and development.

## Project Structure

```text
IELTS-Preparation-App/
├── android/          # Android platform configuration
├── ios/              # iOS platform configuration
├── linux/            # Linux platform configuration
├── macos/            # macOS platform configuration
├── web/              # Web platform configuration
├── windows/          # Windows platform configuration
├── assets/           # Application assets and icons
├── lib/
│   ├── constants/    # Application constants and test data
│   ├── controllers/  # Application controllers
│   ├── models/       # Data models
│   ├── screens/      # Application screens
│   ├── services/     # Application services
│   ├── utils/        # Utility functions
│   ├── widgets/      # Reusable UI components
│   ├── main.dart     # Application entry point
│   └── firebase_options.dart
├── test/             # Flutter tests
├── firebase.json
├── pubspec.yaml
├── pubspec.lock
└── README.md
```

## Installation and Setup

### Prerequisites

Install the following tools before running the application:

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) or Visual Studio Code
- Git
- Android SDK or an appropriate device/emulator

Verify your Flutter installation:

```bash
flutter --version
flutter doctor
```

### Clone the Repository

```bash
git clone https://github.com/Sardar-Usmann/IELTS-Preparation-App.git
```

Navigate to the project directory:

```bash
cd IELTS-Preparation-App
```

### Install Dependencies

```bash
flutter pub get
```

### Run the Application

Check available devices:

```bash
flutter devices
```

Run the application:

```bash
flutter run
```

**Configuration note:** Firebase must be configured for your environment. AI-powered features also require valid API credentials. Never publish private credentials in source code or commit history.

## Firebase Integration

Firebase is used for backend functionality, including:

- Firebase Core initialization
- User authentication
- Cloud Firestore integration
- User-related data management

Firebase security rules and API restrictions should be configured appropriately before deployment.

## Future Enhancements

Potential improvements include:

- More comprehensive IELTS mock examinations
- Enhanced writing assessment and grammar feedback
- Pronunciation and fluency analysis
- Personalized study plans
- Detailed performance reports
- Improved learning analytics
- Additional practice content
- Cloud-based progress synchronization
- Notifications and study reminders

## Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```

4. Push the branch:

   ```bash
   git push origin feature/your-feature
   ```

5. Open a Pull Request.

## License

Review the repository's license before redistributing or using this project commercially. If no license has been added, all rights are generally reserved by the copyright holder.

---

<p align="center">

**Developed by Sardar Muhammad Usman**

*Building practical software solutions with Flutter, AI, and modern application technologies.*

[GitHub Profile](https://github.com/Sardar-Usmann) · [Project Repository](https://github.com/Sardar-Usmann/IELTS-Preparation-App)

</p>
