<div align="center">
  <!-- Use your icon URL -->
  <img src="https://i.postimg.cc/MTM0vQRF/image.png" alt="Invitation Emblem" width="120" />
  <h1>Digital Wedding Invitation</h1>
  <p>
    A beautiful, animated, and personalized single-page web invitation for the wedding of Rakshit & Seem.
  </p>
  
  <!-- GitHub badges -->
  <p>
    <a href="https://github.com/suyogsontakke/Wedding-Invitation/releases"><img src="https://img.shields.io/github/v/release/suyogsontakke/Wedding-Invitation?label=Latest%20release&style=flat-square" alt="Latest release"/></a>
    <a href="https://github.com/suyogsontakke/Wedding-Invitation/stargazers"><img src="https://img.shields.io/github/stars/suyogsontakke/Wedding-Invitation?style=flat-square" alt="Stars"/></a>
    <a href="https://github.com/suyogsontakke/Wedding-Invitation/forks"><img src="https://img.shields.io/github/forks/suyogsontakke/Wedding-Invitation?style=flat-square" alt="Fork"/></a>
    <a href="https://github.com/suyogsontakke/Wedding-Invitation/blob/main/LICENSE"><img src="https://img.shields.io/github/license/suyogsontakke/Wedding-Invitation?style=flat-square&color=blue" alt="License"/></a>
    <img src="https://img.shields.io/github/languages/top/suyogsontakke/Wedding-Invitation?style=flat-square&logo=html5&logoColor=white&color=E34F26" alt="Top Language: HTML"/>
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs welcome"/>
  </p>
  
  <strong>Live Demo: <a href="https://virat-weds-anushka.vercel.app/">WEBSITE</a></strong>
</div>

<!-- Add a high-quality screenshot of your invitation -->
<div align="center">
  <img src="https://i.postimg.cc/ncwWWvkW/image.png" alt="Wedding Invitation Screenshot">
</div>

---

## 📖 Table of Contents

<details><summary>Table of Contents</summary>

* [🚀 About This Project](#-about-this-project)
* [✨ Key Features](#-key-features)
* [🛠️ Technologies Used](#️-technologies-used)
* [🧰 Getting Started](#-getting-started)
  * [📋 Prerequisites](#-prerequisites)
  * [⚙️ How to Customize](#️-how-to-customize)
  * [▶️ Run Locally](#️-run-locally)
* [🚀 Deployment](#-deployment)
* [🤝 Contributing](#-contributing)
* [📄 License](#-license)
* [💎 Acknowledgements](#-acknowledgements)

</details>

---

## 🚀 About This Project

This repository contains a beautiful, single-page digital wedding invitation for **Rakshit & Seem**. It's designed to provide an elegant and modern experience for guests, complete with personalization, animations, and all the event details in one place.

The project is built with **pure, dependency-free Vanilla JavaScript, HTML5, and CSS3**. It demonstrates advanced CSS techniques for animation (keyframes, transforms), scroll-based animations (Intersection Observer), and DOM manipulation for personalization.

The invitation starts with a "splash" page that asks for the guest's name, which is then dynamically inserted into the invitation card for a personal touch.

---

## ✨ Key Features

* **Personalized Welcome:** Greets guests by name after they enter it on the initial screen.
* **Elegant, Royal Theme:** Uses a classic royal blue and gold color palette (`#272872`, `#FFD700`) with traditional script fonts (`Great Vibes`, `EB Garamond`).
* **Multi-Page Feel (Single Page):** A fade transition moves from the name input screen to the main invitation card.
* **Advanced CSS Animations:**
    * **Floating Particles:** A subtle, looping particle animation in the background.
    * **Shimmering Gradient:** The main card background has a slow, shimmering gradient animation.
    * **Character Reveal:** The couple's names animate in, letter by letter.
    * **SVG Line Drawing:** The section dividers "draw" themselves as the user scrolls.
* **Scroll-Based Animations:** Content sections (like event details, photos) gracefully fade in and slide up as they enter the viewport using the **Intersection Observer API**.
* **Fully Responsive:** The design is optimized for both mobile phones and desktop browsers.
* **Self-Contained:** The entire application is a single `index.html` file, making it extremely lightweight, portable, and easy to deploy.

---

## 🛠️ Technologies Used

<details><summary>This project was built from scratch using only core web technologies:</summary>

* [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5): For the semantic structure of the invitation.
* [**CSS3 (Custom Properties & Animations)**](https://developer.mozilla.org/en-US/docs/Web/CSS): For all styling, layout (Flexbox), and complex animations (Keyframes, Transitions, Transforms).
* [**Vanilla JavaScript (ES6+)**](https://developer.mozilla.org/en-US/docs/Web/JavaScript): For all interactivity:
    * DOM Manipulation (getting guest name, updating text).
    * Event Listeners (click, keypress).
    * `IntersectionObserver` API for scroll animations.
    * `setTimeout` for sequenced animations.

</details>

[![Technologies Used](https://skillicons.dev/icons?i=html,css,js)](https://skillicons.dev)

---

## 🧰 Getting Started

To customize this invitation for your own use, follow these steps.

### 📋 Prerequisites

* A code editor (like [VS Code](https://code.visualstudio.com/)).
* A web browser.
* (Optional) [Git](https://git-scm.com/downloads) for version control.
* (Optional) [Node.js](https://nodejs.org/en/) for using `live-server`.

### ⚙️ How to Customize

1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/suyogsontakke/Wedding-Invitation.git
    ```
    ```bash
    cd Wedding-Invitation
    ```
2.  **Open `index.html`:** All the content is in this one file.
3.  **Replace Images:**
    * **Couple Photo:** Find the `.couple-photo` CSS rule and replace the `background-image: url(...)` with a URL to your photo.
    * **Emblem/Icon:** Replace the `favicon` links and the `<img>` tag for the `.buddha-icon` with your own icon URLs.
4.  **Edit Event Details (HTML):**
    * Change the names `Rakshit` and `Seem`.
    * Update the `p` tags with the correct parents' names and family details.
    * Update the `<h2>` and `<p>` tags inside each `.event-section` with your event (e.g., Haldi, Wedding, Reception), dates, times, and venue addresses.
    * Update the "With Best Compliments From" section.
5.  **Adjust Fonts & Colors (CSS):**
    * All colors are defined in the `:root` section at the top of the `<style>` tag. You can change `--bg-blue-dark`, `--gold-text`, etc., to match your theme.
    * Fonts are imported from Google Fonts in the `<head>`. You can change these, but be sure to update the `font-family` rules in the CSS.

### ▶️ Run Locally

* **Simple Method:** Just double-click the `index.html` file to open it directly in your web browser.
* **Recommended Method (using a local server):**
    ```bash
    # Make sure you are in the project directory
    npx live-server
    # OR if installed globally:
    # live-server
    ```
    This opens the site on a local URL (e.g., `http://127.0.0.1:8080`).

---

## 🚀 Deployment

This is a fully static site and can be deployed for free on any static web hosting provider.

* **Vercel:** Drag-and-drop your project folder or connect your GitHub repo.
* **Netlify:** Drag-and-drop your project folder or connect your GitHub repo.
* **Firebase Hosting:**
    ```bash
    # Example Firebase Deployment
    firebase deploy --only hosting
    ```
* **GitHub Pages:** A perfect choice for a project like this.

---

## 🤝 Contributing

This is a personal project, but if you have suggestions for improving the code or animations, feel free to fork the repo and submit a pull request!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/NewAnimation`)
3.  Commit your Changes (`git commit -m 'Add NewAnimation'`)
4.  Push to the Branch (`git push origin feature/NewAnimation`)
5.  Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 💎 Acknowledgements

* **Google Fonts** for the beautiful `Great Vibes` & `EB Garamond` typefaces.
* Inspiration from traditional royal wedding card designs.
