# Internship Program of Web Development with HTML & CSS & JavaScript by ApexPlanet Software Pvt. Ltd.

Task 2 :-
Interactive JavaScript components added to the existing 4-page website from Task 1.

## Pages

- `index.html` – Home
- `about.html` – About
- `services.html` – Services
- `contact.html` – Contact

## Folder Structure

```
Task 2/
├── index.html
├── about.html
├── services.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
    └── logo.png
        other images
```

## Interactive Components Added

- **Hamburger Menu** — responsive toggle menu for mobile devices, opens and closes the navigation.
- **Dark / Light Mode Toggle** — switches between dark and light theme, saves preference in `localStorage`, auto-applies on page reload.
- **Back To Top Button** — appears after scrolling down, smoothly scrolls back to the top on click.
- **Image Slider / Carousel** — auto-sliding gallery with Previous / Next buttons, dot indicators, and swipe support.
- **Modal Popup** — "Get a Free Quote" popup, closes via close button, outside click, or Escape key.
- **Form Validation** — real-time validation on the contact form for name (min 3 chars), email (valid format), phone (10 digits), and message (required). Shows error/success feedback while typing.
- **Smooth Scrolling** — all anchor links scroll smoothly to their target section.
- **Animated Counters** — numbers animate from 0 to their target value when the section scrolls into view (Projects, Clients, Experience, Team).
- **Real-Time Character Counter** — displays characters typed in the contact form textarea with a 200-character limit.

## Component Placement

| Component | Home | About | Services | Contact |
|---|---|---|---|---|
| Hamburger Menu | ✅ | ✅ | ✅ | ✅ |
| Dark / Light Mode | ✅ | ✅ | ✅ | ✅ |
| Back To Top Button | ✅ | ✅ | ✅ | ✅ |
| Image Slider | ✅ | | | |
| Modal Popup | ✅ | | ✅ | |
| Animated Counters | ✅ | ✅ | | |
| Form Validation | | | | ✅ |
| Character Counter | | | | ✅ |
| Smooth Scrolling | ✅ | ✅ | ✅ | ✅ |

## JavaScript Features Used

- `localStorage` — saves and restores the selected theme across sessions.
- `IntersectionObserver` — triggers counter animation when the section enters the viewport.
- `addEventListener` — handles all user interactions (clicks, scroll, input, keydown, touch).
- `classList.toggle` / `classList.add` / `classList.remove` — manages active states for menu, modal, and button visibility.
- `scrollTo` / `scrollIntoView` — powers smooth scrolling behaviour.
- `setInterval` / `clearInterval` — drives the auto-sliding carousel.
- `RegExp` — validates email format in the contact form.
