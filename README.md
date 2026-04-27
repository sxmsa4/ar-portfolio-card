# AR Portfolio Card

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)
![A-Frame](https://img.shields.io/badge/A--Frame-000000?logo=aframe\&logoColor=white)
![AR.js](https://img.shields.io/badge/AR.js-FF2D20?logo=augmented-reality\&logoColor=white)
![WebAR](https://img.shields.io/badge/WebAR-Mobile-blue)
![Deployment](https://img.shields.io/badge/Deployment-Netlify-00C7B7?logo=netlify\&logoColor=white)

A lightweight **WebAR portfolio experience** designed to showcase a developer profile through an interactive **augmented reality business card**.

This project allows recruiters to discover a portfolio in **3D directly from a smartphone browser**, without installing any application.

---

# Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Architecture](#architecture)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [Usage](#usage)
* [Development](#development)
* [Roadmap](#roadmap)
* [Constraints](#constraints)
* [Contributing](#contributing)
* [License](#license)

---

# Overview

**AR Portfolio Card** is a WebAR project that enhances personal branding by transforming a traditional business card into an interactive digital experience.

The application demonstrates:

* integration of **WebAR technologies** into a standard website
* a **mobile-first experience**
* a simple and intuitive **user journey**
* the use of **marker-based augmented reality**

The goal is to create a memorable and innovative way to present a developer portfolio.

---

# Features

## Web Experience

* Multi-page website (Home, AR Experience, About)
* Mobile-first responsive design
* Simple and clear navigation

## Augmented Reality

* Marker-based AR detection
* 3D avatar display
* Interactive elements (clickable objects)
* Text overlays for guidance

## Interaction

* Links to GitHub and portfolio
* User interaction via touch
* Visual feedback

## User Experience

* Camera permission handling
* Clear instructions for AR usage
* Loading indicators

---

# Tech Stack

## Frontend

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla)**

## AR Technologies

* **A-Frame**
* **AR.js**

## Deployment

* **Netlify (HTTPS required)**

---

# Architecture

The project follows a simple front-end architecture focused on performance and clarity.

### Structure

| Layer      | Responsibility         |
| ---------- | ---------------------- |
| HTML       | Page structure         |
| CSS        | Styling and layout     |
| JavaScript | Interactions and logic |
| A-Frame    | 3D rendering           |
| AR.js      | Marker detection       |

---

# Project Structure

```
/
├── index.html        # Home page
├── ar.html           # AR experience
├── about.html        # About page
├── /assets           # 3D models, images, marker
├── /css              # Stylesheets
├── /js               # Scripts
└── README.md
```

---

# Getting Started

These instructions will help you run the project locally.

---

# Installation

Clone the repository:

git clone https://github.com/your-username/ar-portfolio-card.git

cd ar-portfolio-card

Run a local server (recommended):

* VS Code Live Server
* Python HTTP server

---

# Usage

Typical user flow:

1. Scan the QR code on the business card
2. Open the website on a smartphone
3. Navigate to the AR page
4. Allow camera access
5. Point the camera at the AR marker
6. Interact with the 3D portfolio

---

# Development

## Requirements

* Modern web browser (Chrome / Safari)
* Smartphone for AR testing
* Git

## Development workflow

* Build UI pages (HTML/CSS)
* Integrate AR scene (A-Frame + AR.js)
* Add interactions with JavaScript
* Test on real mobile devices

---

# Roadmap

Planned improvements:

* Improved 3D animations
* Enhanced UI interactions
* Better marker design
* Performance optimization
* Additional portfolio elements

---

# Constraints

* Total AR page size < 5 MB
* Optimized 3D models (< 2 MB each)
* HTTPS required for camera access
* Mobile compatibility mandatory

---

# Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

git checkout -b feature/my-feature

3. Commit your changes

git commit -m "Add new feature"

4. Push to your fork

git push origin feature/my-feature

5. Open a Pull Request

---

# License

This project is for educational purposes.

---

# Author

* Your Name – Web Developer Student
