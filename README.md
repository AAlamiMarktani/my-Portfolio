<div align="center">

# 🏎️ Ali Alami Marktani — Interactive 3D Portfolio

**Drive through Monte-Carlo. Stop at each rest area. Discover my journey.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ali-alami-marktani.vercel.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#-tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#-tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-tech-stack)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](#-tech-stack)

</div>

---

## 🔗 Quick Links

| | |
|---|---|
| 🌍 **Live demo** | https://ali-alami-marktani.vercel.app/ |
| 📦 **Repository** | https://github.com/2y8bqw7stk-source/my-Portfolio |

---

## ✨ About the project

This portfolio centralizes my academic work, presents my technical identity, and gives an interactive window into my software development projects.

Instead of a classic scrolling page, it is a small **3D driving game**: you take the wheel of a car on the streets of Monaco, pass through a toll gate announcing *"C'est le parcours de Ali Alami Marktani"*, and each section of my journey is a **rest area** along the road. Pull in or keep driving, it's your choice.

## 🗺️ The route

| Stop | What you will find |
|---|---|
| 🎟️ **Toll gate** | Welcome and start of the journey |
| 🅿️ **À propos** | Who I am: software engineering student at ESISA, Fès |
| 🅿️ **Expérience** | Internships, leadership roles and student clubs |
| 🅿️ **Projets** | Fès Connect, RoomBook, chess engine in C++/Qt, academic management system |
| 🅿️ **Compétences** | Languages, systems, mathematics, soft skills |
| 🅿️ **Contact** | Emails, phone, LinkedIn, GitHub (with copy buttons) |
| 🏁 **Finish line** | End of the journey, stats, and a button to drive it again |

## 🎮 Features

- **Real driving feel:** the car steers, leans in corners, and the camera follows behind it
- **Rest areas on your terms:** info cards appear as you approach, you decide whether to pull in
- **Turbo boost** with a gauge, refilled in rest areas
- **3 camera views** (chase, high, hood) and a **day / night mode**
- **Garage:** choose your car color on the welcome screen
- **Progress tracking:** timer, unlocked stops, progress bar with stop markers
- **Optional engine sound**, horn, and confetti at the finish line
- **Responsive:** keyboard on desktop, touch controls on mobile

## ⌨️ Controls

| Action | Desktop | Mobile |
|---|---|---|
| Accelerate | `↑` / `W` | Hold your finger |
| Brake / reverse | `↓` / `S` / `Space` | — |
| Steer | `←` `→` / `A` `D` | Slide left or right |
| Turbo | `Shift` | 🔥 button |
| Change camera | `C` | 📷 button |
| Day / night | `N` | 🌙 button |
| Horn | `H` | — |
| Sound on / off | `M` | 🔊 button |

The buttons at the top of the screen also drive you automatically to any stop.

## 🛠️ Tech Stack

- **Languages:** HTML, CSS, JavaScript
- **3D engine:** [Three.js](https://threejs.org/) (r128, loaded from cdnjs)
- **Audio:** Web Audio API (engine and effects, no audio files)
- **Deployment:** Vercel

## 📂 Project Structure

```
my-Portfolio/
├── index.html   # Page structure and HUD
├── style.css    # Design, cards, HUD and responsive rules
└── script.js    # 3D scene, car, driving physics, game logic and content
```

> The profile photo is embedded in `script.js`, so no extra assets folder is needed.

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/2y8bqw7stk-source/my-Portfolio.git
cd my-Portfolio
```

Then open `index.html` in your browser. An internet connection is required to load Three.js.

To run it on a local server instead:

```bash
npx serve
```

## 🚀 Deployment

The site is deployed on **Vercel**. Any push to the main branch redeploys it automatically.

## 📬 Contact

- ✉️ a.alami.marktani@esisa.ac.ma
- 💼 [LinkedIn](https://www.linkedin.com/in/ali-alami-marktani-a8bb6932a)
- 🐙 [GitHub](https://github.com/2y8bqw7stk-source)

---

<div align="center">
</div>
