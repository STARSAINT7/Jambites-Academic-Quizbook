# JAMB Academic Quizbook — UTME CBT Practice Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Offline Ready](https://img.shields.io/badge/Offline-100%25-brightgreen.svg)]()

**JAMB Academic Quizbook** is a lightweight, responsive, single-file HTML5/JavaScript web application built to help candidates preparing for the Joint Admissions and Matriculation Board (JAMB) Unified Tertiary Matriculation Examination (UTME) practice, test their speed, and master their subjects.

Designed with an animated glassmorphism UI, sleek dark gradient theme, and custom modal components, this application runs **100% offline** in any standard web browser without server installations or external library dependencies.

---

## 🌟 Key Features

- **Single-File Architecture:** The entire app—including styles, UI logic, custom dialog overlays, and the extensive question bank—is cleanly contained within a single standalone `.html` file for zero-friction distribution (via flash drives, local networks, or web hosting).
- **Glassmorphism UI Design:** Modern translucent card layout (`backdrop-filter: blur`), animated linear gradient backgrounds, and responsive layouts tailored for mobile phones, tablets, and desktop displays.
- **Robust CBT Engine:**
  - Candidate registration modal with personalized student greetings.
  - Subject-specific countdown timers (**36 minutes** for Use of English; **30 minutes** for other subjects) with automated submission handling upon expiry.
  - Dynamic **question and option shuffling** per test session to guarantee unique practice runs.
  - Live progress tracking bar and real-time score counters.
- **Instant Academic Evaluation:** Automated grading upon submission, featuring tier-based academic feedback and performance scaling[cite: 7].
- **Fallback In-App Dialogs:** Custom-styled modal overlays designed to replace native browser `alert()` and `confirm()` popups, ensuring flawless behavior in restricted browser environments[cite: 7].

---

## 📚 Subjects Covered (22 JAMB UTME Subjects)

The app features an extensive multi-subject question database matching UTME standards:

1. 📖 **Use of English** (Compulsory — 60 Questions)[cite: 7]
2. 📐 **Mathematics**[cite: 7]
3. ⚛️ **Physics**[cite: 7]
4. ⚗️ **Chemistry**[cite: 7]
5. 🧬 **Biology**[cite: 7]
6. 📜 **Literature-in-English**[cite: 7]
7. 🏛️ **Government**[cite: 7]
8. 📈 **Economics**[cite: 7]
9. 🌍 **Geography**[cite: 7]
10. ✝️ **Christian Religious Knowledge (CRK / CRS)**[cite: 7]
11. ☪️ **Islamic Religious Knowledge (IRK / IRS)**[cite: 7]
12. 🌾 **Agricultural Science**[cite: 7]
13. 📊 **Principles of Accounts**[cite: 7]
14. 🛒 **Commerce**[cite: 7]
15. 💻 **Computer Studies**[cite: 7]
16. 🏠 **Home Economics**[cite: 7]
17. 🏗️ **Building / Technical Drawing**[cite: 7]
18. 🎨 **Fine Arts**[cite: 7]
19. 🇫🇷 **French**[cite: 7]
20. 🇳🇬 **Hausa**[cite: 7]
21. 🇳🇬 **Igbo**[cite: 7]
22. 🇳🇬 **Yoruba**[cite: 7]

---

## 🚀 Getting Started & Hosting

### Running Locally
1. Clone the repository or download the `.html` file[cite: 7]:
   ```bash
   git clone [https://github.com/STARSAINT7/jamb-academic-quizbook.git](https://github.com/STARSAINT7/jamb-academic-quizbook.git)
