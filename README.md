# Crux Compass Workspace

This workspace contains the early-stage development of **Crux Compass**—a climbing resource website aimed at helping users discover nearby climbing spots (gyms, crags, bouldering areas), read the latest climbing news, and contribute their own climbing experiences and content.

---

## Project Overview

**Crux Compass** is envisioned as an all-in-one resource for climbers:

- **Climbing Finder:** Users can search for climbing spots near them—be it a climbing gym, crag, or other outdoor climbing area.
- **News Hub:** Up-to-date climbing news featuring epic ascents, route sends, interviews, and more.
- **Content Submissions:** An interactive platform for climbers to submit their own content, share news, and post updates about their latest climbs.
- **Gallery:** A visual showcase of the latest climbing achievements with responsive images and detailed captions.

The project is still in its development phase. The current implementation includes static HTML pages for the home page, news section, and gallery, along with a basic styling framework.

---

## Completed Features

- **Static Pages:**

  - **Home Page:** Introduces the site, explains the climbing hub concept, and provides climbing terminology, safety tips, and a climbing grade conversion table.
  - **News Page:** Displays articles with climbing news, publication dates, and related images.
  - **Gallery Page:** Showcases climbing images using responsive design techniques (via the `<picture>` element).

- **Design & Layout:**

  - Consistent styling across pages with a unified color scheme and typography.
  - Responsive layout with media queries and flexible image sizing.
  - Use of semantic HTML elements (e.g., `<header>`, `<nav>`, `<article>`, `<figure>`, `<figcaption>`) to improve accessibility and structure.

- **Content Elements:**
  - Climbing grade conversion table with proper column grouping and header definitions.
  - Integration of multimedia elements such as images and blockquotes.
  - Sample articles with time tags and structured data for publishing dates.

---

## Roadmap / To-Do List

### Core Functionality

- [ ] **Climbing Finder Functionality:**

  - Develop an interactive search feature (possibly integrating a mapping service) for users to find climbing gyms, crags, and bouldering spots based on location.
  - Integrate third-party APIs or create a custom backend for location data.

- [ ] **User Content Submission:**
  - Build a submission form for users to contribute news, photos, and climbing reports.
  - Set up a backend system (e.g., using Node.js, Python, or PHP) and a database (e.g., MySQL, PostgreSQL, or MongoDB) to store and manage submissions.
  - Implement moderation features to review and approve user content before it goes live.

### Enhancements & Improvements

- [ ] **Responsive Enhancements:**

  - Refine mobile responsiveness and optimize for various devices.
  - Further test cross-browser compatibility.

- [ ] **Accessibility & SEO:**

  - Improve accessibility with ARIA roles and better semantic markup.
  - Optimize pages for SEO with meta tags, structured data, and faster load times.

- [ ] **User Interface (UI) Enhancements:**

  - Create a dynamic navigation system with smooth transitions between pages.
  - Consider a content management system (CMS) for easier updates and content moderation.

- [ ] **Interactivity & Animations:**
  - Introduce subtle animations and hover effects to enhance user experience.
  - Explore integrating JavaScript frameworks (React, Vue, or Angular) for a more dynamic interface.

### Future Features

- [ ] **User Accounts and Profiles:**
  - Allow users to create accounts, bookmark favorite climbing spots, and track their climbing history.
- [ ] **Community Features:**

  - Develop forums or comment sections for discussions.
  - Add social sharing features to spread climbing news and content.

- [ ] **Event Management:**
  - Integrate an events calendar for upcoming climbing trips, competitions, and meetups.
  - Allow event organizers to submit and manage their events.

---

## Development Notes

- **Tech Stack:**
  - Frontend: HTML5, CSS3 (with responsive design considerations), and basic JavaScript (future work).
  - Backend (Planned): Node.js/Python/PHP (to be determined based on further requirements), along with a database solution.
- **File Organization:**

  - Separate HTML files for Home, News, and Gallery pages.
  - CSS is embedded within HTML files for now; consider externalizing stylesheets as the project grows.

- **Collaboration:**
  - Use Git for version control.
  - Create issues and milestones in our project tracker to manage the to-do list and feature requests.

---

This README serves as an internal project/workspace document to track progress, plan upcoming features, and communicate the overall vision for **Crux Compass**. As the project evolves, this document will be updated to reflect new developments and adjustments to the roadmap.

Happy climbing and coding!
