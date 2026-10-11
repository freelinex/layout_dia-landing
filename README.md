# Dia — Creative Agency Landing Page

A responsive one-page website for Air, an agency specializing in branding, marketing, and communications. The project showcases the agency, its areas of expertise, services, and client testimonials, and helps visitors access contact information and a feedback form. The goal of the project was to create a modern landing page with responsive layout and interactive elements.

## Demo

[View the website](https://freelinex.github.io/layout_dia-landing/)

## Technologies Used

- **HTML5** — page markup.
- **SCSS (Sass)** — styles, variables, mixins, and media queries.
- **CSS Flexbox and Grid** — element layout and responsive grids.
- **JavaScript** — mobile menu, slider, and form processing.
- **Parcel** — project build and local development server.
- **Node.js and npm** — dependency management and running commands via `@mate-academy/scripts`.
- **ESLint, Stylelint, and Linthtml** — validating JavaScript, styles, and HTML.
- **GitHub Pages** — hosting the demo.

## Running Locally

To run the application, you'll need **Node.js**, **npm**, and **Git** installed.

1. Clone the repository and navigate to the project folder:

   ```bash
   git clone https://github.com/freelinex/layout_dia-landing.git
   cd layout_dia-landing
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the local server:

   ```bash
   npm start
   ```

   Open the URL displayed in the terminal after startup in your browser.

To create a production build, use `npm run build`; to check the code with linters, use `npm run lint`.

## Features

- **Responsive layout** for smartphones, tablets, and large screens.
- **Mobile menu** with scroll lock; closes when you press Escape, click outside the menu, or select a link. The button’s state is reflected in the `aria-expanded` attribute.
- **Carousel** with three images and forward/backward navigation.
- **Seamless navigation** through page sections via anchor links.
- **Sections about the agency, areas of expertise, services, and testimonials**, supplemented with a call-to-action block and contact information.
- **Interactive hover effects** for buttons, links, and other interface elements.
- **Feedback form** with required fields and built-in email validation. Fields are cleared after submission; data is not sent to the server.
