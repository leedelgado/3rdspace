# 3rdspace

## Overview
**3rdspace** is a mobile-first web application designed to turn any physical gathering into a "third space"—a location where people can hang out, chat, and connect at little to no cost. Recognizing that genuine, organic conversations can be difficult to initiate, 3rdspace lowers the barrier to socializing by providing context-aware icebreakers and conversation starters for attendees at the same event.

## The Problem
People increasingly lack accessible third spaces outside of their home (first space) and workplace (second space) for casual, free socialization. Even when attending physical events, sparking a conversation with a stranger can feel intimidating. 3rdspace addresses this friction by giving users a tangible starting point for dialogue, effectively transforming any localized event into a welcoming community space.

## User Stories & Flow
The application functions as a linear, single-page application that seamlessly guides users through the connection process:

* **Event Check-in:** As a user, I can select my current event or location (e.g., Startup Mixer, Local Coffee Shop) so that I only see people in my immediate vicinity.
* **Topic Selection:** As a user, I can browse a grid of high-level interests (Tech & AI, Sports, Arts, Health, Games, Travel, Nature, Food & Drink) to indicate what I want to talk about right now.
* **Discovery:** As a user, I can view profiles of nearby attendees who share my selected interest. Each profile provides me with a highly specific, curated icebreaker prompt (e.g., "Ask Sarah about her favorite meditation app").
* **Connection & Action:** As a user, once I decide to connect, I receive an estimated physical distance to my match. I am equipped with the primary icebreaker, bonus questions, and secondary interests to ensure the conversation flows naturally.

## Tech Stack
* **Markup:** HTML5
* **Styling:** CSS3, Bootstrap 5 (via CDN). The application utilizes custom CSS variables, flexbox/grid layouts, and keyframe animations to create a native app-like experience.
* **Typography & Iconography:** Google Fonts (Inter, Playfair Display) and Bootstrap Icons.
* **Logic & State Management:** Vanilla JavaScript handles view routing, state transitions, and dynamic DOM population using a hardcoded, client-side database. No build tools or backend are required for the MVP.

## Installation & Local Development
Since 3rdspace operates entirely on the client side, running the project locally is straightforward:

1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. *Note:* The UI is deliberately constrained to mobile dimensions (`max-width: 414px`). For the best development experience, inspect the page and toggle the device toolbar to an iPhone or similar mobile viewport.

## Contributors
This project was built during the Pursuit AI Native Hackathon on <time datetime="2026-03-25">March 25, 2026</time> by:
* [Lee Delgado](https://github.com/leedelgado)
* [Lawrence Carillo](https://github.com/lawrencecarrillo)
* [Karl Johnson](https://github.com/hirekarl)
* [Marc Perez](https://github.com/marcperezart)
* [Michael Reyes](https://github.com/yahnmaicosreyes-cpu)
* [Rob Walker](https://github.com/74001w)
