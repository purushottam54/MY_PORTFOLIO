# Portfolio_my

A responsive, multi-mode personal portfolio website for Purushottam Sarsekar, featuring a terminal-inspired desktop experience and a modern mobile layout. This project showcases web development, cybersecurity, and programming projects, and provides access to a downloadable resume.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [About the Author](#about-the-author)
- [License](#license)

## Overview

This project is a personal portfolio website that adapts its interface based on the user's device:

- **Desktop:** Presents a unique terminal-style interface (`cmdport.html`) for an interactive, hacker-themed experience.
- **Mobile:** Switches to a modern, card-based portfolio layout (`portfo1.html`) for easy navigation and readability.

The site highlights the author's skills, pinned projects, and provides a downloadable/viewable resume (`resume_real.pdf`).

## Features

- **Device-based Redirection:**
  - `index.html` automatically redirects users to the appropriate interface:
    - **Desktop:** `cmdport.html` (terminal UI)
    - **Mobile:** `portfo1.html` (modern portfolio UI)
- **Terminal UI (cmdport.html):**
  - Simulates a Linux terminal with custom commands (`name`, `help`, `about`, `social-media`, `project`, `banner`, `clear`, etc.)
  - Command history, autocomplete, and root access simulation
  - Animated glitch effects and responsive design (hidden on mobile)
- **Modern Portfolio UI (portfo1.html):**
  - Profile sidebar with avatar, bio, and social links
  - Pinned and expandable project cards with tech stack icons
  - About section and resume viewer (embedded PDF)
  - Toggle to show/hide additional projects
  - Built with Tailwind CSS and FontAwesome
- **Resume:**
  - `resume_real.pdf` is viewable directly in the browser via the portfolio page

## Project Structure

```
Portfolio_my/
├── cmdport.html        # Terminal-style desktop portfolio
├── index.html          # Entry point, handles device redirection
├── portfo1.html        # Modern mobile portfolio
├── resume_real.pdf     # Downloadable/viewable resume
```

## Usage

1. **Open `index.html` in your browser.**
   - On desktop, you'll see the terminal interface.
   - On mobile, you'll see the modern portfolio layout.
2. **Explore the features:**
   - Use terminal commands in desktop mode for info and fun interactions.
   - Browse projects, bio, and view the resume in mobile mode.
3. **View Resume:**
   - Click the "View Resume" button in the mobile layout to open the embedded PDF.

## About the Author

**Purushottam Sarsekar**  
B.E. Student | Web Developer | Android Developer  
Dr. D. Y. Patil College of Engineering, Akurdi, Pune

- GitHub: [purushottam54](https://github.com/purushottam54)
- LinkedIn: [Purushottam Sarsekar](https://www.linkedin.com/in/purushottam-sarsekar-b66136290/)

### Pinned Projects (Sample)

- **Access-Controlled-HTTP:** Share data/files between computer networks (Python)
- **HOME-MAINTENANCE-SERVICES:** App to reduce manual work (JavaScript)
- **SQL_VIRTUAL_LAB:** Real-time SQL query executor (PHP)
- **Firewall-Breaker:** Tool to bypass Windows firewall (Python)
- **Paste-jacking-code:** Cybersecurity tool for command injection (JavaScript)
- **PHOTO-EDITOR:** Photo editor using GSAP, HTML, CSS, JS
- **money_converter:** Currency converter (Bootstrap)
- **Portfolio-template:** Portfolio website template (CSS)

## License

This project is for personal and educational use. For other uses, please contact the author.
