<div align="center">

# 🐍 Neon Snake

### A glowing neon take on classic Snake. Play it right in your browser.

<a href="https://alhasanayon26.github.io/Neon-Snake/"><img src="https://img.shields.io/badge/Play_Now-Neon_Snake-ff2fb3?style=for-the-badge&logo=githubpages&logoColor=white" alt="Play Now"></a>
<a href="https://github.com/alhasanayon26"><img src="https://img.shields.io/badge/GitHub-alhasanayon26-30363d?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

![HTML5](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-30363d?style=flat-square&logo=githubpages&logoColor=white)

</div>

---

## About

Neon Snake is a single-page Snake game with glowing visuals, four difficulty levels, level progression, power-ups, and combo scoring. It runs fully in the browser on desktop and mobile, with no installs, no accounts, and no dependencies.

## Features

- **4 difficulties:** each with its own speed, obstacle count, theme color, and saved best score
- **Levels:** level up every 5 orbs, the snake gets faster, and obstacles appear from level 2
- **Power-ups:** gold stars and ice orbs that disappear if you wait too long
- **Combo scoring:** eat orbs quickly to build a multiplier up to x5
- **Neon visuals:** glowing board, gradient snake, particle bursts, and screen shake on game over
- **Sound effects:** with a mute button
- **Works everywhere:** keyboard, swipe, or on-screen buttons
- **Best scores saved:** stored on your own device, separately for each difficulty

## How to Play

Eat the glowing pink orbs to grow and score. Avoid the walls (on harder modes), the purple obstacle blocks, and your own tail.

### Controls

| Device | How to control |
| --- | --- |
| **Computer** | Arrow keys or **W A S D** to steer |
| **Phone / tablet** | Swipe on the screen, or use the on-screen arrow buttons |
| **Start / Pause / Resume** | **Space** on desktop, or the on-screen button |
| **Sound** | Speaker button next to the score |

### Difficulties

| Mode | Walls | Start speed | Obstacles added per level |
| --- | --- | --- | --- |
| **Easy** | Wrap around | Slowest | 1 |
| **Normal** | Deadly | Medium | 2 |
| **Hard** | Deadly | Fast | 3 |
| **Insane** | Deadly | Fastest | 4 |

### Power-ups

| Power-up | Effect | Duration |
| --- | --- | --- |
| ⭐ **Gold star** | +5 points and the snake grows by 2 | Disappears after 7 seconds |
| ❄️ **Ice orb** | Slow-motion for easier control | Slow-mo lasts 5 seconds, orb disappears after 7 seconds |

### Scoring

- Each orb is worth 1 point times your current combo (x1 up to x5).
- Eating another orb within about 3.5 seconds raises the combo.
- Every 5 orbs raises your level.

## Run Locally

This is a static game, so no build step or dependencies are needed.

```bash
git clone https://github.com/alhasanayon26/Neon-Snake.git
cd Neon-Snake
```

Then open `index.html` in any modern browser.

## Deploy on GitHub Pages

1. Make sure the game file is named `index.html` and sits in the repository root.
2. Push the files to a GitHub repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait a minute, then open the link GitHub shows.

## Project Structure

```text
Neon-Snake/
├── index.html   # the whole game: markup, styles, and logic
└── README.md
```

## Tech

HTML5 Canvas, CSS, and vanilla JavaScript, with sound effects from the Web Audio API and best scores saved in `localStorage`.

## Author

Made by **Rifaat Al Hasan Ayon**

<p>
<a href="https://github.com/alhasanayon26"><img src="https://img.shields.io/badge/GitHub-30363d?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/alhasanayon26"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:alhasanayon26@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://t.me/CNS_Ayon"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="https://www.instagram.com/_ayon_n"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

---

<div align="center">

© 2026 Rifaat Al Hasan Ayon

</div>
