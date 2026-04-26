# 🏥 Tena Clinic

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Bootstrap-5.3.7-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5.3.7">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/license-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Pages](#pages)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)
- [Author](#author)

---

## About

**Tena Clinic** is a modern, responsive healthcare website built to provide comprehensive medical information and services to patients in Addis Ababa, Ethiopia and beyond. The clinic combines modern medical expertise with compassionate, patient-centered care rooted in Ethiopian values.

With over **15 years of experience**, Tena Clinic has served more than **5,000 patients** with a team of **50+ medical experts** providing round-the-clock emergency care. The facility is accredited and maintains a stellar **4.9/5 patient rating**.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🏠 **Responsive Design** | Mobile-first design that looks stunning on all devices |
| 🎯 **Smooth Animations** | Elegant AOS (Animate On Scroll) animations for engaging user experience |
| 🖼️ **Lightbox Gallery** | GLightbox-powered image gallery with zoom and swipe gestures |
| 📊 **Stats Counter** | Animated PureCounter statistics display |
| 🏥 **Department Pages** | Comprehensive medical departments with detailed information |
| 👨‍⚕️ **Doctor Profiles** | Meet our expert medical professionals |
| 📅 **Online Booking** | Appointment scheduling system |
| ⭐ **Testimonials** | Patient reviews and success stories |
| ❓ **FAQ Section** | Frequently asked questions for quick reference |
| 📞 **Contact Forms** | Easy way to get in touch |
| 🔒 **Privacy & Terms** | Legal pages for user protection |
| 🌍 **SEO Optimized** | Search engine friendly with meta tags |

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) | Semantic markup structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) | Custom styling and responsiveness |
| ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white) v5.3.7 | CSS framework for rapid development |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | Interactive functionality |
| [AOS](https://michalsnik.github.io/aos/) | Animate On Scroll library |
| [GLightbox](https://biati.gitlab.io/glightbox/) | Pure JavaScript lightbox |
| [PureCounter](https://www.npmjs.com/package/purecounter) | Pure JS counter plugin |
| [Swiper](https://swiper.js.org/) | Mobile touch slider |
| [Font Awesome](https://fontawesome.com/) | Icon library |

---

## 📄 Pages

| Page | Description |
|------|-------------|
| 🏠 **Home** | Hero section, stats, services overview, team intro, CTA |
| 📖 **About** | Clinic history, mission, vision, values |
| 🏥 **Departments** | Medical departments listing |
| 🔬 **Department Details** | Individual department information |
| 🩺 **Services** | Medical services offered |
| 🔎 **Service Details** | Detailed service information |
| 👨‍⚕️ **Doctors** | Our medical professionals |
| 📅 **Appointment** | Book an appointment |
| 💬 **Testimonials** | Patient reviews |
| ❓ **FAQ** | Frequently asked questions |
| 🖼️ **Gallery** | Photo gallery |
| 📜 **Terms** | Terms of service |
| 🔐 **Privacy** | Privacy policy |
| 📧 **Contact** | Contact information & form |
| 🚫 **404** | Custom error page |

---

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (recommended for full functionality)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/clinic-healthcare.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd clinic-healthcare
   ```

3. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server:
     ```bash
     # PHP built-in server
     php -S localhost:8000
     
     # Python
     python -m http.server 8000
     
     # Node.js
     npx http-server -p 8000
     ```

4. **Visit the site**
   ```
   http://localhost:8000
   ```

---

## 📁 Project Structure

```
clinic-healthcare/
├── 404.html                  # Custom 404 error page
├── about.html               # About us page
├── appointment.html        # Appointment booking
├── contact.html           # Contact page
├── departments.html      # Departments listing
├── department-details.html # Department details
├── doctors.html          # Doctors/Team page
├── faq.html             # FAQ page
├── gallery.html         # Photo gallery
├── index.html          # Home page
├── privacy.html        # Privacy policy
├── service-details.html # Service details
├── services.html     # Services page
├── starter-page.html  # Starter template
├── terms.html       # Terms of service
├── testimonials.html # Testimonials page
│
├── assets/
│   ├── css/
│   │   └── main.css    # Main stylesheet
│   │
│   ├── img/
│   │   ├── bg/        # Background images
│   │   ├── clients/   # Client logos
│   │   ├── gallery/   # Gallery images
│   │   ├── health/    # Health/department images
│   │   └── person/    # Person/doctor images
│   │
│   ├── js/
│   │   └── main.js    # Main JavaScript
│   │
│   ├── scss/          # SCSS source files
│   │
│   └── vendor/
│       ├── bootstrap/    # Bootstrap JS
│       ├── fontawesome/  # Font Awesome
│       ├── aos/          # AOS animations
│       ├── glightbox/    # GLightbox
│       ├── purecounter/  # Counter plugin
│       └── swiper/       # Swiper slider
│
├── forms/
│   ├── appointment.php   # Appointment form handler
│   └── contact.php      # Contact form handler
│
└── README.md           # This file
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👏 Credits

| Resource | Link |
|----------|------|
| Template | [Clinic Bootstrap Template](https://bootstrapmade.com/clinic-bootstrap-template/) |
| Framework | [Bootstrap](https://getbootstrap.com/) |
| Animations | [AOS](https://michalsnik.github.io/aos/) |
| Lightbox | [GLightbox](https://biati.gitlab.io/glightbox/) |
| Icons | [Font Awesome](https://fontawesome.com/) |
| Slider | [Swiper](https://swiper.js.org/) |
| Counter | [PureCounter](https://www.npmjs.com/package/purecounter) |

Special thanks to [BootstrapMade](https://bootstrapmade.com/) for the wonderful template design.

---

---

## 👨‍⚕️ Author

**Tena Clinic** is developed and maintained by **Miftah** - a passionate web developer based in Ethiopia.

<p align="center">
  <a href="https://github.com/miftah">
    <img src="https://img.shields.io/badge/GitHub-Follow-333?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub">
  </a>
  <a href="https://linkedin.com/in/miftah">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn">
  </a>
</p>

---

<p align="center">
  <strong>Made with ❤️ in Ethiopia 🇪🇹</strong>
</p>

<p align="center">
  <em>Your Health, Our Priority.</em>
</p>

---

<p align="center">
  <a href="https://tenaclinic.et">🌐 Visit Website</a> •
  <a href="mailto:info@tenaclinic.et">📧 Contact</a> •
  <a href="https://instagram.com/tenaclinic">📸 Instagram</a> •
  <a href="https://facebook.com/tenaclinic">📘 Facebook</a>
</p>

---

<p align="center">
  <sub>© 2024-2026 Tena Clinic. All rights reserved.</sub>
</p>