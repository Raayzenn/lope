
# Love draw - alay

A beautiful heart drawing animation created using
HTML5 Canvas and JavaScript. This project
demonstrates how to generate and animate heart-shaped
points using mathematical equations.

[! Live demo ]
(https://lovedraw.vercel.app/)

## ✨ Features

- 💖 Generates heart shape using parametric equations
- 🎨 Smooth animation drawing each point sequentially
- 📱 Responsive design with Tailwind CSS
- 🌸 Clean, minimalist aesthetic with pink color scheme
- ⚡ Lightweight (only 1.5KB JavaScript)

## 🧠 How It Works

The heart shape is generated using these parametric equations:

```javascript
x = 16 * sin³(θ)
y = 13 * cos(θ) - 5 * cos(2θ) - 2 * cos(3θ) - cos(4θ)
```

Where θ ranges from 0 to 2π radians (0° to 360°). The points are then scaled and drawn sequentially on an HTML5 Canvas to create the animation effect.

## 🛠️ Technologies Used

![Tech Stack](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tech Stack](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tech Stack](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🚀 Installation

No installation required! Simply:

1. Clone this repository or download the HTML file
2. Open `index.html` in any modern web browser

```bash
git clone https://github.com/your-username/heart-drawing.git
cd heart-drawing
open index.html
```

## 🎨 Customization

You can easily customize the animation:

```javascript
// Change heart size
const scale = 10; // ← Adjust this value

// Change heart color
ctx.fillStyle = '#ec4899'; // ← Try '#ff0000' for red

// Change point size
ctx.arc(x, y, 2, 0, Math.PI * 2); // ← Change the radius (2)
```

## 🌟 Try It Live!

[![Open in CodePen](https://img.shields.io/badge/CodePen-000000?style=for-the-badge&logo=codepen&logoColor=white)](https://codepen.io)
[![Open in JSFiddle](https://img.shields.io/badge/JSFiddle-0084FF?style=for-the-badge&logo=jsfiddle&logoColor=white)](https://jsfiddle.net/)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by Harry 
