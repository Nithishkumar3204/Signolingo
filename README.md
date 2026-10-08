# 🤟 Signolingo

### Learn Sign Language. Practice with Your Camera. Improve Through Interaction.

**Signolingo** is a desktop-based sign language learning application designed to make learning more interactive and engaging. It uses the user's camera to detect hand movements and provides a simple, game-like learning experience inspired by modern language-learning platforms.

The goal of Signolingo is to make sign language learning more accessible, interactive, and enjoyable through technology.

---

## Key Features

*  **Camera-Based Learning**
  Uses the device camera to allow users to practice sign language interactively.

*  **Hand Detection**
  Uses hand-tracking technology to detect and analyze hand movements.

*  **Interactive Learning Experience**
  Provides a game-inspired learning environment instead of traditional passive learning.

*  **Progress-Based Learning**
  Allows learners to practice and improve their sign language skills through repeated interaction.

*  **Desktop Application**
  Built as a standalone Electron application for desktop platforms.

*  **Privacy-Focused Camera Access**
  The application requests camera access only when required for sign detection.

*  **Offline-Friendly Architecture**
  Core application assets and hand-tracking resources are bundled with the application.

---

##  Problem We Address

Learning sign language can be difficult when learners do not have continuous access to instructors or practical opportunities to practice.

Traditional learning methods often rely heavily on videos, images, or classroom instruction. These methods may not provide immediate interaction while the learner is practicing.

**Signolingo aims to bridge this gap by turning sign language practice into an interactive experience where the learner can use their own camera and practice directly with the application.**

---

##  Our Solution

Signolingo combines:

* Computer vision
* Hand tracking
* Interactive learning
* Gamification
* Desktop application technology

to create a more engaging environment for sign language practice.

The learner can interact with the application using hand gestures rather than simply watching instructional content.

---

##  Technology Stack

| Technology             | Purpose                                     |
| ---------------------- | ------------------------------------------- |
| **Electron**           | Desktop application framework               |
| **HTML5**              | Application interface                       |
| **CSS3**               | User interface styling                      |
| **JavaScript**         | Application logic                           |
| **MediaPipe Hands**    | Hand tracking and landmark detection        |
| **WebAssembly (WASM)** | High-performance hand-processing components |
| **Electron Builder**   | Application packaging and distribution      |

---

##  Project Structure

```text
Signolingo/
│
├── build/
│   ├── icon.png
│   └── icon.ico
│
├── src/
│   ├── index.html
│   ├── fonts/
│   └── vendor/
│       └── hands/
│
├── main.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Signolingo.git
```

### 2. Navigate to the Project

```bash
cd Signolingo
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Application

```bash
npm start
```

The Signolingo desktop application will launch.

---

##  Building the Application

### Windows

```bash
npm run dist:win
```

This creates a Windows installer.

### macOS

```bash
npm run dist:mac
```

### Linux

```bash
npm run dist:linux
```

---

##  Camera Permission

Signolingo requires access to the device camera for hand-tracking functionality.

The application is configured to request **media/camera permission** when required.

No additional system permissions are required for the core application.

---

##  Privacy

Signolingo is designed with a privacy-focused architecture.

The application only requests camera access because it is required for the hand-tracking functionality. The project does not require an external server for its core learning functionality.

Users should still review the application's implementation and permissions before deploying it in production environments.

---

##  Why Signolingo?

Sign language is an important form of communication, but learning it can be challenging without regular opportunities for practice.

Signolingo explores how computer vision and interactive software can make sign language learning more accessible and engaging.

Instead of only **watching and memorizing signs**, users can **practice signs through interaction with the application**.

---

##  Future Improvements

Potential future improvements include:

* Support for a larger sign language vocabulary
* More advanced gesture recognition
* Personalized learning paths
* Difficulty levels
* Achievement and reward systems
* Learning analytics
* User profiles and progress synchronization
* Support for multiple sign languages
* Improved gesture accuracy
* Mobile and web versions
* AI-assisted feedback for sign execution

---

##  Developer

**P V Giridhar**
**Nitishkumar**
**X Arockia Nithesh**
**T K Vedhavarsan**

Signolingo was developed as an interactive technology project exploring the use of computer vision and desktop application development for sign language learning.

---

## 📄 License

This project is currently provided for educational and demonstration purposes.

---

## ⭐ Project Vision

> **Making sign language learning more interactive, accessible, and engaging through technology.**

If you find the project interesting, consider ⭐ starring the repository.
