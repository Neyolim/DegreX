
---

# Project summary

I built a responsive, accessible Single Page Application (SPA) using **React** by following a YouTube tutorial to practice real-world React patterns. The app is component-driven, uses hooks heavily (state + side-effects), includes a carousel, smooth-scrolling navigation, and a contact form that posts submissions so I receive them by email (no custom backend required).

---

# Key features

* Clean component-per-folder structure (component and styles grouped together)
* Reusable UI components with well-defined `props` interfaces
* Extensive use of React hooks: `useState`, `useEffect`, `useRef`
* Carousel component (for testimonials) — implemented while following the tutorial and adapted to fit the project
* Smooth page scrolling via `react-scroll` for anchor navigation
* Contact form integrated with a serverless form service (Web3Forms) so form submissions are emailed to me (configured via an access key)
* Mobile-first responsive layout and accessible semantics

---

# Tech stack

* React (functional components + hooks)
* JavaScript (ES6+)
* CSS (component-scoped files; easy to swap for CSS Modules )
* react-scroll (smooth in-page navigation)
* A custom Carousel (implemented/adapted during practice)
* Web3Forms to receive contact form emails without a backend

---

# What I learned 

I followed a practical tutorial and used the project as a sandbox to learn how to scale a frontend from small to medium size:

1. **Project & folder hygiene** — I kept each component in its own folder (component file, `Component.css`, helper files). Grouping related code made refactors and navigation much easier.
2. **Props-driven reusable components** — Building small, focused components with clear props made the UI predictable and simple to reuse.
3. **React hooks in practice** — I used `useState` for local state, `useEffect` for side-effects (data fetching, subscriptions, cleanup), and `useRef` for DOM references and persistent values across renders. I used `useRef` to control the carousel and manage accessibility focus.
4. **Third-party integration** — I integrated `react-scroll` for smooth anchor navigation and a serverless form provider so I could accept contact messages without building a backend.
5. **Forms & UX** — Implemented client-side validation, loading / success / error states, and a graceful user experience for the contact form; submissions are routed to my email through the form service.
6. **Small performance wins** — Experimented with code-splitting (lazy loading), memoization patterns, and careful effect dependencies to avoid unnecessary re-renders.

These are concrete patterns I practiced and can reuse across future projects.

---

## Final notes 

* This repo demonstrates practical, production-minded React patterns learned through guided practice: component encapsulation, hook-driven logic, and lightweight third-party integrations.

---
