# Md Rakibul Hassan - Professional Profile Card

## Project Overview

A modern, responsive, and interactive profile card website showcasing professional information, social links, and contact functionality. Designed with a clean, minimalist interface featuring dark/light mode toggling, smooth animations, and integrated QR code access to the full portfolio.

---

## Live Demo

[Add your GitHub Pages or Vercel deployment link here]

---

## Features

- Fully responsive layout for all screen sizes
- Dark/Light mode toggle with smooth transitions
- Professionally designed contact form with validation
- Integrated Formspree backend for message delivery
- Social media links with hover effects
- QR code integration for portfolio access
- Graceful handling of missing images with fallback placeholders
- Clean animations and transitions for enhanced UX

---

## Technologies Used

- **HTML5** – Semantic and structured markup
- **CSS3** – Custom properties, flexbox, and animations
- **JavaScript (ES6+)** – Interactivity and event handling
- **Font Awesome 6** – Icon library for social and UI elements
- **Formspree API** – For contact form submissions

---

## File Structure

```
Profile_Card/
│
├── index.html
├── images/
│   ├── Md_Rakibul_Hassan.jpg
│   ├── profile_qr.PNG
│   ├── profile_qr.png
│   └── profile_qr.jpg
└── README.md
```

---

## Setup Instructions

1. **Download or Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Profile_Card.git
   ```

2. **Add Your Assets**

   - Place your professional photo as `Md_Rakibul_Hassan.jpg` in the `images/` folder.
   - Add a QR code image named `profile_qr.png` (or `.PNG` / `.jpg`) linking to your portfolio.

3. **Run Locally**

   - Open `index.html` directly in your browser or serve it via a local server.

---

## Contact Form Setup

The contact form is configured with **Formspree** for secure and simple message handling.

1. Visit [https://formspree.io](https://formspree.io) and create a free account.
2. Create a new form and obtain your unique Formspree endpoint.
3. Replace the form `action` URL in `index.html` with your endpoint.
4. Test the form to confirm messages are being sent correctly.

---

## Customization Guide

### 1. Personal Information

- Edit your name, title, and bio directly in the HTML file.
- Update social media links with your own profiles.
- Adjust contact details as necessary.

### 2. Visual Styling

- Modify color themes using CSS variables defined in the `:root` selector.
- Update gradients or dark-mode color values within the `.dark-mode` selector.
- Adjust font sizes, spacing, and layout properties as desired.

### 3. Content and Media

- Replace the profile photo and QR code with your personalized assets.
- Update “Download CV” and “Hire Me” buttons to link to your preferred destinations.
- Adjust animation durations or easing functions if desired.

---

## How It Works

1. Open `index.html` in a modern browser.
2. The theme toggle button switches between light and dark modes smoothly.
3. The “Hire Me” button opens a contact form modal handled via Formspree.
4. The QR section detects and displays the first available QR image:

   - If the QR image loads successfully, clicking it redirects to the portfolio.
   - If not, a simulated QR scanner animation appears before redirecting.

---

## Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Edge (Latest)
- Safari (Latest)

---

## Deployment

This project can be hosted easily on:

- **GitHub Pages**
- **Vercel**
- **Netlify**
- **Any static web hosting service**

Simply upload the `index.html` file and `images/` folder.

---

## Portfolio

Visit the full portfolio at:
[https://portfolio-rouge-eight-22.vercel.app/](https://portfolio-rouge-eight-22.vercel.app/)

---

## Author

**Md Rakibul Hassan**
Backend Specialist | Robotics & IoT Enthusiast

- Email: [rakibulhassanmiyaji27@gmail.com](mailto:rakibulhassanmiyaji27@gmail.com)
- Portfolio: [https://portfolio-rouge-eight-22.vercel.app/](https://portfolio-rouge-eight-22.vercel.app/)
- LinkedIn: [linkedin.com/in/mdrakibulhassanmiyaji](http://www.linkedin.com/in/mdrakibulhassanmiyaji)
- GitHub: [github.com/RR0327](https://github.com/RR0327)
- Twitter (X): [x.com/Rakibul79904](https://x.com/Rakibul79904?t=6IacHqN16j2OF_Ium6VEIw&s=08)

---

## License

This project is open source and available under the **MIT License**.
Attribution is appreciated if you use or adapt this design.

---

_Designed and developed for professional presentation, simplicity, and performance._
