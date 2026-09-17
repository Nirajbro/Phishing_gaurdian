# 🛡️ PhishingGuardian

**PhishingGuardian** is an interactive **cybersecurity awareness and phishing education platform** designed to help users understand common cyber threats through **interactive scenarios, games, quizzes, awareness content, and visual learning**.

The project focuses on making cybersecurity education more engaging by combining traditional awareness material with game-based learning.

---

## 📌 Project Overview

PhishingGuardian is a web-based cybersecurity awareness project that allows users to learn about online threats through an interactive experience.

The platform includes multiple learning sections covering topics such as:

* 🎣 Phishing Awareness
* 🪪 Identity Theft Awareness
* 🐴 Trojan Horse Awareness
* 🎮 Cybersecurity Awareness Games
* ❓ Interactive Questions and Quizzes
* 💡 Hints and Learning Assistance
* 🏆 Awards / Badges
* 🎬 Security Awareness Videos
* 📊 Interactive learning and scoring elements

The objective is to help users recognize suspicious activities and develop safer cybersecurity habits through practical and interactive learning.

---

## 🎯 Objectives

The main objectives of PhishingGuardian are:

1. Increase cybersecurity awareness among users.
2. Teach users how to identify phishing and other suspicious activities.
3. Provide interactive security-learning scenarios.
4. Use games and quizzes to improve engagement.
5. Explain common cybersecurity threats in a simple and practical way.
6. Encourage users to develop safer online behavior.

---

## ✨ Features

### 🎣 Phishing Awareness

The phishing awareness section introduces users to phishing-related scenarios and provides interactive content to help identify suspicious messages, links, and online activities.

### 🪪 Identity Theft Awareness

Users can learn about identity theft through awareness content and an interactive game-based experience.

### 🐴 Trojan Horse Awareness

The project includes a dedicated Trojan Horse awareness section explaining the concept through an interactive learning experience and card-game style activity.

### 🎮 Cybersecurity Games

Interactive games are included to make cybersecurity awareness more engaging.

The project includes game-based activities such as:

* Hacker-related interaction/gameplay
* Question-based challenges
* Interactive card gameplay
* Pac-Man style awareness game

### ❓ Questions and Quizzes

Users can answer cybersecurity-related questions and interact with question-based learning modules.

### 💡 Hints

Hints are provided during selected activities to assist users when they require guidance.

### 🏆 Awards and Badges

The project contains an awards/badges section to represent user achievement after completing learning activities.

### 🎬 Awareness Videos

Security awareness videos are integrated into the project to provide visual learning.

---

## 🧰 Technologies Used

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript**

### Media / Assets

* Images
* SVG graphics
* Audio assets
* Video content
* Custom UI elements

### Development Tools

* Visual Studio Code
* Git
* GitHub
* Modern Web Browser

---

## 🏗️ Project Structure

```text
PhishGuardian/
│
├── index.html
│
├── css/
│   └── phishguard.css
│
├── images/
│   ├── award.png
│   ├── badge.png
│   ├── facebook.png
│   ├── favicon.png
│   ├── level_1.png
│   ├── level_2.png
│   ├── phishguard_mainlogo.webp
│   ├── phishing_report_1.webp
│   └── phishing_report_2.webp
│
├── award/
│   ├── badges.html
│   └── badges.css
│
├── identity_theft/
│   ├── identity_theft_awareness.html
│   ├── pacman.html
│   └── videos/
│       └── identity_theft_video.mp4
│
├── level_1/
│   ├── level_1.html
│   ├── amazon.html
│   ├── question.html
│   ├── hint.html
│   ├── hint_2.html
│   ├── gameover.html
│   ├── phishing_awareness.html
│   ├── phishing_animated_video.html
│   ├── sam_message.html
│   ├── sam_message_2.html
│   ├── sam_message_3.html
│   ├── sam_message_4.html
│   ├── save_game.html
│   │
│   ├── css/
│   │   ├── amazon.css
│   │   ├── game.css
│   │   ├── question.css
│   │   ├── sam.css
│   │   └── video.css
│   │
│   ├── js/
│   │   ├── eluminate.js
│   │   ├── end.js
│   │   ├── highscores.js
│   │   ├── main.js
│   │   ├── script.js
│   │   ├── system.js
│   │   └── video.js
│   │
│   └── game/
│       ├── wackthehacker.html
│       ├── css/
│       │   ├── style.css
│       │   ├── cog.svg
│       │   ├── icon.svg
│       │   ├── timer.svg
│       │   ├── velocity-mole.svg
│       │   └── volume.svg
│       │
│       └── js/
│           └── script.js
│
├── level_1_trojan/
│   ├── trojan_awareness.html
│   ├── trojanhorsecardgame.html
│   └── video/
│       └── trojan_horse.mp4
│
└── .vscode/
    └── settings.json
```

---

## 🔄 Application Flow

The general application flow is:

```text
                    ┌──────────────────┐
                    │    index.html    │
                    │   Main Page      │
                    └────────┬─────────┘
                             │
             ┌───────────────┼────────────────┐
             │               │                │
             ▼               ▼                ▼
       Identity Theft   Phishing Level   Trojan Awareness
             │               │                │
             ▼               ▼                ▼
          Pac-Man       Interactive       Card Game
             │            Scenarios
             │               │
             │         ┌─────┴─────┐
             │         ▼           ▼
             │      Questions     Games
             │         │
             │         ▼
             │       Result
             │
             └──────────────┬─────────────────
                            ▼
                       Awards / Badges
```

---

## 📂 Major Modules

### 1. Main Application

**Path:**

```text
/index.html
```

The main landing page provides access to the major cybersecurity awareness modules.

---

### 2. Identity Theft Module

**Path:**

```text
/identity_theft/identity_theft_awareness.html
```

Provides awareness content related to identity theft.

Interactive game:

```text
/identity_theft/pacman.html
```

Video:

```text
/identity_theft/videos/identity_theft_video.mp4
```

---

### 3. Phishing Awareness Module

The phishing learning experience is located under:

```text
/level_1/
```

Important pages include:

```text
/level_1/level_1.html
/level_1/phishing_awareness.html
/level_1/phishing_animated_video.html
/level_1/question.html
/level_1/hint.html
/level_1/hint_2.html
/level_1/gameover.html
```

Additional scenario pages include:

```text
/level_1/sam_message.html
/level_1/sam_message_2.html
/level_1/sam_message_3.html
/level_1/sam_message_4.html
/level_1/amazon.html
```

---

### 4. Phishing Game

Game page:

```text
/level_1/game/wackthehacker.html
```

Game styling:

```text
/level_1/game/css/style.css
```

Game logic:

```text
/level_1/game/js/script.js
```

---

### 5. Trojan Horse Module

Awareness page:

```text
/level_1_trojan/trojan_awareness.html
```

Interactive game:

```text
/level_1_trojan/trojanhorsecardgame.html
```

Awareness video:

```text
/level_1_trojan/video/trojan_horse.mp4
```

---

### 6. Awards and Badges

The awards module is located at:

```text
/award/badges.html
```

Styling:

```text
/award/badges.css
```

This section represents achievements obtained through the learning experience.

---

## 🎮 Game-Based Learning

PhishGuardian uses game-based learning to make cybersecurity education more interactive.

The project combines:

```text
Learning
   +
Interactive Scenarios
   +
Questions
   +
Games
   +
Hints
   +
Videos
   +
Achievements
```

This approach is intended to make security awareness more engaging than a traditional text-only training platform.

---

## 🖥️ How to Run the Project

PhishGuardian is a web-based project.

### Method 1 — Open Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/PhishGuardian.git
```

Move into the project:

```bash
cd PhishGuardian
```

Open:

```text
index.html
```

in a modern web browser.

---

### Method 2 — Using VS Code

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html`.
4. Use a local development server such as **Live Server**.
5. Open the generated local URL in your browser.

Using a local server is recommended when the project contains media or relative resource paths that may behave differently when opened directly from the filesystem.

---

## 🌐 Recommended Browser

The project can be tested using modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

---

## 📱 Responsive Design

The project uses HTML and CSS-based layouts designed for web interaction.

Responsive behavior may depend on the individual page and its CSS implementation.

---

## 🔐 Cybersecurity Focus

PhishGuardian is focused on **cybersecurity awareness and education**.

The project demonstrates awareness concepts related to:

* Phishing
* Social engineering awareness
* Identity theft
* Trojan horses
* Suspicious online activity
* Safe browsing practices
* Security decision-making

The purpose of the project is educational and awareness-oriented.

---

## 🧠 Learning Outcomes

After completing the modules, users should have a better understanding of:

* How phishing scenarios can appear.
* Why suspicious messages and links should be examined carefully.
* How identity theft can affect users.
* What Trojan horse malware represents.
* How interactive security awareness training can improve learning.
* Why cybersecurity hygiene is important in everyday digital activities.

---

## 🚀 Future Enhancements

Potential future improvements include:

* User authentication
* Database-backed user profiles
* Persistent scores and achievements
* Additional cybersecurity levels
* More phishing scenarios
* Leaderboards
* Progress tracking
* Admin dashboard
* Increased mobile optimization
* Additional threat-awareness modules
* Backend integration
* Analytics and reporting

---

## 📸 Screenshots

Screenshots of the application can be added here.

Example:

```markdown
![PhishGuardian Home Page](images/homepage.png)
![Phishing Awareness](images/phishing.png)
![Identity Theft Game](images/identity-theft.png)
![Trojan Horse Game](images/trojan.png)
```

---

## 👨‍💻 Project Type

**Cybersecurity Awareness / Educational Web Application**

---

## 📄 License

This project is intended for **educational and demonstration purposes**.

Add the appropriate license here if you decide to distribute the project under a specific open-source license.

---

## ⚠️ Disclaimer

PhishingGuardian is an educational cybersecurity awareness project.

It is designed to demonstrate security concepts and promote safer online behavior. It should not be used for unauthorized access, malicious activity, or testing systems without proper authorization.

---

## 👤 Author

**Niraj Chaudhari**

MCA Student | Cybersecurity Enthusiast

### 🔗 Connect

* GitHub: `https://github.com/Nirajbro/`
---

## ⭐ Support

If you find this project useful for learning cybersecurity awareness, consider giving the repository a ⭐ on GitHub.
