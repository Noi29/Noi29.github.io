# Noa Rosales | Portfolio

Personal portfolio of Noa Rosales, an aspiring Full Stack Developer.

**Live site:** https://noi29.github.io
**Play the game:** https://noi29.github.io/cafe.html

## What is in this repository

| File | What it is |
| --- | --- |
| `index.html` | The portfolio: about me, skills, languages, projects and contact |
| `cafe.html` | Cafe Web, a visual café game that runs in the browser |
| `images/portada.jpg` | Background image of the portfolio header |

## Built with

- HTML and CSS (layout, responsive design, animations)
- JavaScript (the game logic and the canvas drawing)
- Google Fonts (DM Sans and Sora)
- GitHub Pages for hosting

No frameworks and no build step: everything is plain files.

## Cafe Web

A game where you run a café for 5 days.

**How to play**

1. Each customer arrives with an order in a speech bubble and a timer bar above their head.
2. Click the food and drinks they ordered, then press **Serve**.
3. Reach the money goal of each day and keep your reputation above zero.

**Rules**

- Customers have three urgency levels: in a hurry (30 s), normal (45 s) and no rush (60 s).
- If time runs out, or you send a customer away, you lose one reputation point.
- If a customer brings a dog, you must give it a free croqueta. Forget it and you are paid half and lose reputation. Remember it and you get a tip.
- The menu is based on 2026 food trends: pistachio croissant, Japanese egg sando, sesame sweet toast, hot honey toast, miso caramel cookie, coffee and matcha.

**How it works**

The game draws everything on an HTML canvas and redraws it about 60 times per second in a loop. The state of the game (day, cash, reputation) lives in one object, and each customer is another object with its order, timer and mood.

## Run it locally

No installation needed. Download the repository and open `index.html` or `cafe.html` in any browser.

## Customize the game

Open `cafe.html` and edit:

- `MENU` to change products and prices
- `URG` to change how many seconds each type of customer waits
- `Math.random() < 0.3` in `nextC()` to change how often a dog appears

## Related project

- [Cafe Java](https://github.com/Noi29/coffeshop.java): the console version of the same game, written in Java.

## Notes

Designed by me. Built with AI assistance (Claude Code, ChatGPT and similar tools), then studied, tested and modified by me.

## Contact

- LinkedIn: https://www.linkedin.com/in/noa-rosales-rodriguez-74b333449/
- GitHub: https://github.com/Noi29
