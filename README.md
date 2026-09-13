# BiYuva (Animal Shelter App)

BiYuva is a feature-rich, cross-platform mobile application developed as a Computer Engineering Senior Graduation Project. Built with Flutter and Dart, the application serves as a modern animal shelter ecosystem that bridges the gap between stray animals, shelters, and animal lovers. It facilitates pet adoptions, securely manages donation systems, and helps track animal health records.

---

## 👩‍💻 My Contributions
As a core developer of this graduation project, my primary focus was on the backend architecture, with supportive contributions to the frontend:

*   **Backend & Database Architecture (Primary Role):** Designing and implementing the entire cloud backend infrastructure using **Supabase** and PostgreSQL, including structuring the database schemas.
*   **Security & Data Logic:** Writing custom database functions, API integrations, and configuring strict Row Level Security (RLS) policies to ensure safe user authentication and data privacy.
*   **Frontend Integration:** Collaborating on the Flutter frontend by assisting with specific UI components and ensuring smooth data binding between the application interface and the Supabase backend.
---

## 📸 Screenshots

### 📱 User Experience & Modules
| Home Feed | Adoption Module | Donation Page |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/aac0f554-0af1-481d-af87-caec3035bbc2" width="250"/> | <img src="https://github.com/user-attachments/assets/e89c0ca8-5d91-467f-beb0-dbdbdda51075" width="250"/> | <img src="https://github.com/user-attachments/assets/d9959396-d7d5-4b7c-adf8-0519cb2d4753" width="250"/> |

### 🔐 Auth & Profiles
| Authentication | Animal Profiles | User Profile |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/05b65206-f196-4e61-9cda-74081a763add" width="250"/> | <img src="https://github.com/user-attachments/assets/606c120c-95a3-4a22-a20b-bbbfc6da8976" width="250"/> | <img src="https://github.com/user-attachments/assets/020007d0-2cba-4cbb-9c19-1b7a5bff4f70" width="250"/> |
---

## 🚀 Key Features

* **🔐 Secure Authentication:** Seamless user onboarding with clean login and registration layouts.
* **🐾 Adoption Module:** Instantly view profiles of animals looking for a home, filter by status, and track adoption processes natively.
* **💳 Secure Donation System:** Modulated donation system where users can contribute financially to individual animals or specific shelters.
* **🩺 Health Record Tracking:** Keep a close eye on vaccination status, medical histories, and health logs directly from the profile views.
* **✨ Fluid UI/UX & Animations:** Enhanced with micro-interactions, custom themes, and beautiful vector animations using Lottie.

---

## 🛠️ Tech Stack

* **Framework:** Flutter (Multi-platform UI Toolkit)
* **Language:** Dart
* **Backend & Database:** Supabase (Real-time BaaS integration)
* **Animations:** Lottie Framework (`.json` vector-based assets)
* **State Management & Routing:** Modular Custom Routing Engine

---

## 📂 Project Structure

The project strictly follows clean code standards and a structured design architecture:
```markdown
animal-shelter-app/ (Repository Root)
├── android/, ios/, web/, windows/  # Native platform wrappers
├── lib/                             # Core Flutter source code
│   ├── assets/                      # Local design resources
│   │   ├── animations/              # Lottie JSON animations (e.g., happy_dog.json)
│   │   └── images/                  # Textures, backgrounds, and custom fonts
│   ├── core/                        # Global Application Configuration
│   │   ├── constants/               # System styling guidelines (app_colors.dart)
│   │   └── theme/                   # Explicit styling setups (app_theme.dart)
│   ├── models/                      # Strongly-typed Data Frameworks
│   │   ├── adoption_model.dart      # Adoption mapping and schemas
│   │   ├── animal_model.dart        # Animal database objects
│   │   ├── donation_model.dart      # Transaction data models
│   │   ├── health_record_model.dart # Medical logs and tracking
│   │   └── profile_model.dart       # User/Shelter configurations
│   ├── routes/                      # Deep-linking and Navigations
│   │   └── app_routes.dart          # Named application screen configurations
│   ├── screens/                     # Modular UI View Controllers
│   │   ├── adoption/                # Screens tracking pet matchings
│   │   ├── auth/                    # Sign In / Sign Up structures
│   │   ├── donation/                # Interactive support panels
│   │   ├── home/                    # Global activity stream dashboard
│   │   ├── profile/                 # Personalized user profiles
│   │   └── shelter/                 # Managed center details
│   ├── services/                    # Cloud storage & API communication brokers
│   ├── widgets/                     # Globally decoupled UI components
│   └── main.dart                    # Application bootstrap and initialization entry point
└── pubspec.yaml                     # Application package & asset definitions

```

---

## 🛫 Getting Started

Follow these steps to run the application locally on your machine or emulator:

### Prerequisites

* Ensure you have **Flutter SDK** installed (Stable channel recommended).
* Set up an Android/iOS emulator or have a physical device connected in developer mode.

### 1. Clone the Repository

```bash
git clone https://github.com/merve-adal/animal-shelter-app.git
cd animal-shelter-app

```

### 2. Install Project Dependencies

Fetch all necessary packages and platform-specific engines listed in `pubspec.yaml`:

```bash
flutter pub get

```

### 3. Setup Environment Configuration

Ensure your Supabase backend parameters are correctly initialized inside your app settings or service parameters before bootstrapping the environment.

### 4. Deploy to Device

Launch the application target in debug mode:

```bash
flutter run

```

---


## 🎓 Credits

This project was developed by **Merve Adalı** and **Ümran** as a Senior Graduation Project (Bitirme Projesi) at **Aydın Adnan Menderes University**.


