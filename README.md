# 🎂 A Birthday Surprise for Betu Di ❤️

An interactive birthday website created with love for my sister, **Betu Di**. It combines heartfelt birthday wishes, beautiful animations, floating balloons, confetti, background music, and an interactive candle-blowing experience to make her day extra special.

✨ **A little website, a lot of love, and a memory to cherish.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat&logo=greensock&logoColor=white)
![License](https://img.shields.io/badge/license-personal%20project-pink)

---

## 📖 Table of Contents

- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Customization](#-customization)
- [How Candle Blowing Works](#-how-candle-blowing-works)
- [Project Structure](#-project-structure)
- [Privacy Note](#-privacy-note)
- [Credits](#-credits)

---

## 🌟 Features

- 💌 **Interactive Opening Experience** — An animated introduction to the birthday surprise.
- 🎬 **Smooth Animations** — Beautiful, choreographed transitions powered by GSAP.
- 🎂 **Interactive Birthday Candles** — Blow into your microphone to extinguish the candles, with a click-based alternative.
- 🎉 **Celebration Effects** — Confetti, floating balloons, and festive visual effects.
- 🎵 **Background Music** — Music controls for a more personal birthday experience.
- 📸 **Personalized Memories** — A dedicated section featuring Betu Di's photo.
- 💖 **Heartfelt Birthday Wishes** — Personalized messages celebrating the bond between a brother and his sister.
- 📱 **Responsive Design** — Designed to work across desktop and mobile screens.
- 🔄 **Replay Experience** — Relive the birthday surprise from the beginning.

---

## 🛠️ Tech Stack

| Technology                    | Purpose                                |
| ----------------------------- | -------------------------------------- |
| HTML5                         | Page structure and content             |
| CSS3                          | Styling, layouts, and visual effects   |
| JavaScript                    | Interactions and application logic     |
| GSAP                          | Animations and timeline transitions    |
| Web Audio / Microphone APIs   | Candle-blowing interaction             |
| Google Fonts                  | Typography                             |

---

## 🚀 Getting Started

### Prerequisites

You only need a modern web browser. No backend server or package installation is required — this is a static HTML/CSS/JavaScript website.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/betu-di-birthday.git
cd betu-di-birthday
```

> Replace `YOUR_USERNAME` with your GitHub username.

### 2. Open the Project

Open the folder in Visual Studio Code:

```bash
code .
```

You can open `index.html` directly in your browser. Alternatively, use the **Live Server** extension in VS Code for a more reliable local development experience.

### 3. Enjoy the Experience

Open the website, follow the on-screen instructions, and interact with the birthday animations.

> **Tip:** Microphone-based candle blowing requires microphone permission and generally works on HTTPS websites or `localhost`. If microphone access is unavailable, use the on-screen click-based alternative.

---

## 🌐 Deployment

This is a simple static website, so it can be hosted without managing a backend server.

### Option 1: Netlify — Quickest Deployment

1. Push the project to your GitHub repository.
2. Visit [Netlify Drop](https://app.netlify.com/drop).
3. Drag and drop the project folder containing `index.html` and its required assets.
4. Wait for deployment to complete.
5. Open the generated public URL and test the website.

Alternatively, import the GitHub repository into [Netlify](https://www.netlify.com/) to connect deployments to future GitHub updates.

### Option 2: GitHub Pages

1. Open your GitHub repository.
2. Navigate to **Settings → Pages**.
3. Under build and deployment settings, select the appropriate branch (usually `main`) and the root folder.
4. Save the settings and wait for GitHub Pages to publish the website.

### Option 3: Vercel

Import the repository into [Vercel](https://vercel.com/). For a plain static website, configure the project according to its actual structure and deployment requirements.

> **Important:** After deployment, verify that images, music, animations, and interactive features work correctly. File paths and filename capitalization must match exactly.

---

## 🎨 Customization

You can personalize the website for another birthday or special occasion.

- **Birthday messages:** Edit the relevant text in `index.html`.
- **Recipient's name:** Replace the existing name with your preferred name.
- **Personal photograph:** Update the image path to point to your chosen photo.
- **Background music:** Replace the existing audio file with a song you have permission to use, and ensure its path matches the HTML.
- **Colors and styling:** Modify the CSS to change the theme, gradients, typography, and visual effects.
- **Animations:** Adjust the JavaScript and GSAP timeline to customize the experience.

> Actual filenames and locations may vary depending on the project version. Check the existing files before changing any paths.

---

## 🎤 How Candle Blowing Works

The website includes a microphone-based interaction intended to detect a blowing sound and trigger the candle animation.

1. The browser may request microphone permission.
2. If permission is granted, the website analyzes microphone input.
3. When the interaction detects a sufficient sound level, it triggers the candle-blowing effect.
4. If microphone access is unavailable, an on-screen click alternative can be used.

Microphone access depends on browser permissions and a secure context (HTTPS or `localhost`). Detection quality may vary with microphone sensitivity and background noise.

---

## 📁 Project Structure

The exact structure depends on the files included in the repository. A typical version may look like this:

```text
betu-di-birthday/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   ├── Shagun1.jpg
│   ├── hat.svg
│   ├── birthday-cake.png
│   └── birthday-candle.png
├── music/
│   └── hbd.mpeg
└── README.md
```

> **Note:** This is an illustrative structure, not a guarantee of the repository's actual files. Keep your existing filenames and folder structure unless you update all references accordingly.

---

## 🔒 Privacy Note

This website may contain a personal photograph and personalized messages. If you make the repository public, those files and messages may be visible to anyone who can access the repository.

You can keep the source repository **private** while hosting the website **publicly**. Review your repository contents before publishing.

---

## 🙏 Credits

This project uses web technologies and animation tools to create an interactive birthday experience.

- [GSAP](https://gsap.com/) — Animation library
- [Google Fonts](https://fonts.google.com/) — Typography
- HTML, CSS, and JavaScript — Core website technologies

If this project is based on an existing template or repository, please retain the original creator's attribution and comply with the original project's license.

---

### ❤️ Made with love for Betu Di

Some surprises are more meaningful when they're made just for someone special.

**Happy Birthday, Betu Di! 🎂💖**