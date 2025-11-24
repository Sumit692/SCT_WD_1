This project is a Neon-styled Navigation Bar UI Demo featuring a glowing tech look, smooth scroll effects, hover animations, mobile menu, and section-based active highlighting.
Built entirely with HTML, CSS, and JavaScript, this template can be used for landing pages, portfolios, or modern product websites.

✨ Features
🌐 Neon-Themed UI

Futuristic glowing colors

Smooth hover lighting effects

Active link highlighting

Transparent glass-like background

📌 Fixed Navigation Bar

Stays at the top during scroll

Automatically changes style when scrolled (adds glow & shadow)

📱 Responsive Mobile Menu

Hamburger menu toggle

Auto-populated mobile navigation items

Smooth slide-in panel

Closes automatically on item click or ESC key

🎯 Section Highlighting

Uses IntersectionObserver

Active menu item updates based on scroll position

Works for both desktop & mobile menus

🧭 Smooth Scrolling

Click any navigation item → scrolls smoothly to section

CTA button scrolls to “Work” section

♿ Accessibility

ARIA labels

ESC key closes mobile menu

Buttons properly marked with attributes

🛠️ Tech Stack

HTML5

CSS3 (Neon UI + responsive design)

Vanilla JavaScript

IntersectionObserver API

Smooth scrolling

DOM manipulation

📂 Project Structure
/neon-nav-demo
│── index.html   (Main UI + JS inside) 


(All styling and scripts are included inline inside index.html.)

🔧 How It Works
🟦 Navigation Behavior

When you scroll 40px or more, a .scrolled class is added to the nav → darker background + glow.

Menu automatically updates which link is active using IntersectionObserver.

🟥 Mobile Menu Behavior

Clicking the hamburger toggles the mobile menu.

Navigation links are cloned into the mobile menu automatically.

Clicking any item closes the menu.

🟩 Smooth Page Navigation

When clicking:

<a href="#about">About</a>


The script:

Prevents default behavior

Calculates correct offset (nav height)

Smooth-scrolls to the section

🚀 Usage

Download or clone the repository

Open index.html in any browser

Scroll, hover, and interact with the neon UI

📈 Future Improvements (Optional)

Add theme toggle (light/dark)

Add animations for hero content

Convert into reusable components

Create a React version

🙌 Acknowledgements

This Neon Nav Demo showcases modern UI/UX techniques and serves as a great starter template for futuristic, tech-inspired landing pages.
