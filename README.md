# ExamIQ

ExamIQ is an AI-powered exam integrity platform designed to make online examinations more secure and reliable. It combines student authentication, face-based identity verification, exam monitoring, and teacher-side reporting into a single cross-platform application.

## Features

* Student registration and login using Firebase Authentication
* Face enrollment and identity verification before exams
* Exam monitoring and integrity checks
* Teacher dashboard for exam management
* Student performance and integrity reports
* Report generation and sharing after exam completion
* Cross-platform application using Flutter

## Tech Stack

* **Frontend:** Flutter
* **Backend & Authentication:** Firebase
* **Database:** Cloud Firestore
* **AI/Computer Vision:** Face recognition and verification

## Project Structure

```text
ExamIQ/
├── lib/
│   ├── screens/
│   ├── services/
│   ├── models/
│   └── widgets/
├── assets/
├── android/
├── ios/
├── web/
├── pubspec.yaml
└── README.md
```

## Getting Started

### Prerequisites

* Flutter SDK
* Dart SDK
* Firebase project
* Android Studio or VS Code

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd ExamIQ
```

3. Install dependencies:

```bash
flutter pub get
```

4. Configure Firebase for the project.

5. Run the application:

```bash
flutter run
```

## How It Works

1. **Student Authentication** – Students register and log in securely.
2. **Face Enrollment** – The student's face is registered for identity verification.
3. **Pre-Exam Verification** – The system verifies the student's identity before starting the exam.
4. **Exam Monitoring** – Integrity checks are performed during the examination.
5. **Exam Completion** – Exam results and monitoring information are recorded.
6. **Teacher Dashboard** – Teachers can review exam outcomes and generated reports.

## Purpose

ExamIQ aims to improve examination integrity by reducing identity fraud and enabling automated monitoring, while providing teachers with a centralized platform to review examination outcomes.

## License

This project is developed for educational and academic purposes.
