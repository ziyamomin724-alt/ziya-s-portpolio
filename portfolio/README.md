# Ziya Samir Momin - Personal Portfolio

A premium, modern, fully responsive personal portfolio website built for an AI & ML Engineering student. It features a Black + Dark Pink theme, glassmorphism UI, smooth scroll animations, a particle background, and a dynamic typing text effect.

## Tech Stack
- **Backend:** Node.js, Express.js
- **Templating:** EJS
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Libraries:** FontAwesome (Icons), Particles.js (Background Animation)

## Features
- **Modern Theme:** Deep Black (`#0A0A0A`) and Dark Pink (`#FF1493`) neon glow aesthetic.
- **Glassmorphism:** Premium frosted-glass style cards.
- **Animations:** Custom CSS keyframes, scroll-based fade-ins using Intersection Observer, and a typing text effect.
- **Responsive:** Fully responsive across mobile phones, tablets, and desktops.
- **Sections Included:** Hero, About, Education Timeline, Animated Skills, Achievements, Projects, and Contact Form.

## Project Structure
```text
portfolio/
├── server.js           # Express server entry point
├── package.json        # Node dependencies
├── README.md           # Project documentation
├── views/
│   └── index.ejs       # Main layout and HTML structure
└── public/
    ├── css/
    │   └── style.css   # All styles and animations
    ├── js/
    │   └── script.js   # Client-side interactive logic
    └── images/         # Directory for placeholder/profile images
```

## How to Install and Run

### Prerequisites
You need to have **Node.js** installed on your system.
Download it from: [nodejs.org](https://nodejs.org/)

### 1. Install Dependencies
Open a terminal in the `portfolio` folder and run:
```bash
npm install
```

### 2. Start the Server
Start the development server by running:
```bash
node server.js
```
Alternatively, you can run:
```bash
npm start
```

### 3. View the Website
Open your browser and navigate to:
```
http://localhost:3000
```

## Future Improvements
- **Connect Contact Form:** Integrate with a service like EmailJS or Nodemailer to make the contact form fully functional.
- **Add Real Images:** Replace the icon placeholders with actual project screenshots and a professional profile picture in the `public/images/` folder.
- **Dynamic Content:** Connect the Express server to a database (like MongoDB) to fetch skills, projects, and achievements dynamically.
- **Dark/Light Mode:** Implement a toggle switch to invert the theme from dark to light mode.

---
*Designed and built for Ziya Samir Momin.*
