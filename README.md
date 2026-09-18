# Assignment 7: Multi-Screen App with Forms
<img width="1470" height="956" alt="Screenshot 2026-09-18 at 5 50 17 PM" src="https://github.com/user-attachments/assets/cbc8f114-848a-469f-a351-d3f21b7dca19" />

<img width="1470" height="956" alt="Screenshot 2026-09-18 at 5 50 34 PM" src="https://github.com/user-attachments/assets/b07a4596-32f6-4cd5-85c0-5f5586e472da" />

<img width="1470" height="956" alt="Screenshot 2026-09-18 at 5 51 09 PM" src="https://github.com/user-attachments/assets/97ab919b-f7dd-4132-929e-75dbb42aa562" />

<img width="1470" height="956" alt="Screenshot 2026-09-18 at 5 51 26 PM" src="https://github.com/user-attachments/assets/ecf17132-8430-454a-9362-fe994be8afbf" />









A modern Flutter application demonstrating multi-screen navigation using named routes, state management for form handling, and user input validation. 

## 🚀 Features

* **Multi-Screen Navigation:** Seamless transitions between Home, Registration, and Detail screens using Flutter's Named Routes (`Navigator.pushNamed`).
* **Form Validation:** Comprehensive input validation for required fields, including:
  * Empty field checks.
  * Email format verification using regular expressions.
  * Minimum password length enforcement.
* **Data Passing:** Securely passes user-entered data from the form screen to the details screen using route arguments.
* **Modern UI/UX:** Built with Material 3 design principles, featuring custom theming, rounded input fields, card-based layouts, and responsive design.

## 📱 Screen Structure

1. **Home Screen (`/`):** The initial landing page with a call-to-action button to start the registration process.
2. **Form Screen (`/form`):** A registration form capturing the user's Full Name, Email Address, and Password with real-time validation.
3. **Detail Screen (`/detail`):** A success confirmation screen that retrieves and displays the submitted data, with an option to return to the root screen.

## 🛠️ Tech Stack

* **Framework:** [Flutter](https://flutter.dev/)
* **Language:** Dart
* **Design System:** Material 3

## ⚙️ Getting Started

### Prerequisites
* Flutter SDK (latest stable version)
* An IDE (VS Code, Android Studio, or IntelliJ)
* An iOS Simulator, Android Emulator, or a physical device connected.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/assignment7.git](https://github.com/your-username/assignment7.git)
