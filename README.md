# Auth Pages - FedEx

## Overview
A full set of authentication UI pages built for Web Programming 1 (Assignment 2). The project focuses on consistent styling, a gradient background, responsive card layouts, and interactive states across all screens.

## Pages
- Login (`html/index.html`)
- Register (`html/register.html`)
- Forgot Password (`html/forgot-password.html`)
- Reset Password (`html/reset-password.html`)
- Two-Factor Authentication (`html/two-factor.html`)

## Features
- Unified gradient background and elevated card-form design.
- Consistent typography, color system, and motion effects.
- Responsive layout: two-column on larger screens, single-column on small screens.
- Hover, focus, and disabled states for inputs, links, and buttons.
- Decorative pseudo-elements using `::before` and `::after`.
- Show/Hide password buttons (Login, Register, Reset).
- Login error banner with shake animation (toggle by adding `.is-error` to the form).
- Register password strength meter (weak/medium/strong).
- Reset password strength bar and match validation.
- Two-factor code inputs with resend countdown timer.
- Dark mode toggle using CSS custom properties and `prefers-color-scheme`.

## Dark Mode
- System preference is used by default.
- The toggle lets you switch themes manually.
- The selected theme is stored in `localStorage` for future visits.

## Project Structure
```
Auth/
  css/
    login.css
    register.css
    forgot-password.css
    reset-password.css
    two-factor.css
  html/
    index.html
    register.html
    forgot-password.html
    reset-password.html
    two-factor.html
  images/
    icons8-fedex-100.png
```

## How to Run
Open `html/index.html` in any modern browser.

## Notes
- The project is front-end only. Form actions are placeholders.
- To preview the login error state, add the `is-error` class to `.form-block` in `html/index.html`.
- The two-factor resend link restarts the timer only when it reaches 0.

## Credits
- Logo image: `images/icons8-fedex-100.png`.
