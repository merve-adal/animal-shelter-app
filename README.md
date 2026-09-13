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

### 🔐 Authentication & Interactive Onboarding
**Role Selection & Authentication**
<img width="100%" src="https://github.com/user-attachments/assets/26423be1-fadf-41b6-b382-b39166b89d1a" />

**Interactive Onboarding Process**
<img width="100%" src="https://github.com/user-attachments/assets/2e043147-7391-4296-915c-ee1419c66a21" />

---

### 📱 Animal Discovery & User Experience
**Home Page & Animal Discovery Feed**
<img width="100%" src="https://github.com/user-attachments/assets/24aae878-c3ab-4750-b83f-197653cdcfad" />

**Animal Detail Page & Health History**
<img width="100%" src="https://github.com/user-attachments/assets/d88320c6-d971-4b71-adc9-cde454ea1ab0" />

---

### 💖 Smart Donation & Community Transparency
**Itemized Smart Donation Panel**
<img width="100%" src="https://github.com/user-attachments/assets/cd7e1ee5-fe23-42c7-b297-3c506fa53c1c" />

| Donation Gamification | Community Transparency Feed |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8df49456-68b8-4895-85d9-e60a794e811c" width="300"/> | <img src="https://github.com/user-attachments/assets/8cfcc364-b3d2-46e2-978c-9f998f205602" width="300"/> |

---

### 🏢 Shelter Administration & Dashboard
**Shelter Dashboard & Analytics**
<img width="100%" src="https://github.com/user-attachments/assets/d101f67d-0fcb-4925-af78-44bfda9f4226" />

| Dynamic Price Management | Adoption Request Management |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/ed266149-bb3b-4434-a88a-68db6972e318" width="300"/> | <img src="https://github.com/user-attachments/assets/60ec206c-b0fd-4271-8543-a62731855097" width="300"/> |

---

### 👤 Profile & Account Management
**Role-based Profile Management**
<img width="100%" src="https://github.com/user-attachments/assets/f85bfba1-5cc3-4207-8d31-d9cccef49bba" />

**Personal Donation Ledger (History)**
<br>
<img src="https://github.com/user-attachments/assets/c0a2743c-a164-4462-81d6-20cb0f0163a2" width="300"/>


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


