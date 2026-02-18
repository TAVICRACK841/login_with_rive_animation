# 🐻 Animated Bear Login

Welcome to the **Animated Bear Login** project.

This is an interactive **Flutter** login screen featuring a reactive bear character that responds to user input in real time.  
The animation is powered by a **Rive State Machine** and integrated into Flutter using the official Rive runtime.

> 💼 Developed by **NOVA SOFT**

![Project Demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2Q.../placeholder.gif)

---

## ✨ Features

- 👀 **Eye Tracking:** The bear follows the cursor position while typing in the email field.
- 🙈 **Privacy Mode:** The bear covers its eyes when the password field is focused.
- 😄 **Success State:** The bear celebrates when login credentials are correct.
- 😢 **Fail State:** The bear reacts with a sad/surprised animation if login fails.
- 🎨 **Smooth Animations:** High-quality vector animations powered by Rive.

---

## 🏢 Developed By

**NOVA SOFT**  
Software Development & Interactive UI Solutions  

This project serves as a demonstration of interactive animation integration using Flutter and Rive technology.

---

## 🛠️ Technologies Used

- **Flutter 3.x** — UI Framework  
- **Dart 3.x** — Programming Language  
- **Rive Runtime** — Real-time animation engine  

---

## 📂 Project Structure

```text
lib/
├── main.dart                # Application entry point
└── screens/
    └── login_screen.dart    # UI and Rive State Machine logic
assets/
└── animated_login_bear.riv  # Rive animation file
```

### 📌 Directory Explanation

- **lib/screens/** → Contains modular UI screens.  
  `LoginScreen` manages the `StateMachineController` inputs:

  - `isChecking`
  - `isHandsUp`
  - `trigSuccess`
  - `trigFail`

- **assets/** → Stores the local `.riv` file used by `RiveAnimation.asset`.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/TAVICRACK841/login_with_rive_animation.git
```

### 2️⃣ Install dependencies

```bash
flutter pub get
```

### 3️⃣ Run the application

```bash
flutter run
```

---

## 🏫 Academic Information

- **Institution:** Instituto Tecnológico de Mérida  
- **Course:** Graficación (Computer Graphics)  
- **Professor:** Rodrigo Fidel Gaxiola Sosa  
- **Activity:** Activity 1 — Rive Integration  

---

## 👥 Team Members

- Gabriel Gustavo Lizama May  
- Eduardo Guadalupe Medina Canche  
- David Nicolás Rabiela Blandez  

---

## 🎨 Animation Credits & Attribution

This project uses the animation:

**"Remix of Login Machine"**  
Available at:  
https://rive.app/marketplace/3645-7621-remix-of-login-machine/

The animation was obtained from the **Rive Marketplace** and remains the intellectual property of its original creator.

This repository includes the `.riv` file strictly for educational and demonstration purposes under the terms provided by Rive and the original author.

If you plan to use this animation in a commercial product, please ensure you comply with the license terms specified on the Rive Marketplace page.

---

## ⚖️ Disclaimer

NOVA SOFT did not create the original bear animation.  
NOVA SOFT developed the Flutter integration, application logic, and interaction system built around the Rive animation.

---

## 📸 Demo Recommendation

For better presentation:

1. Record your emulator screen.
2. Convert the recording to GIF.
3. Upload the GIF to your repository.
4. Replace the demo image link above with your actual file.

Example:

```markdown
![Project Demo](assets/demo.gif)
```

---

## 📜 License

This project is for educational and demonstration purposes.  
Please review the Rive animation license before commercial redistribution.