# Vue Facts App

A simple, responsive Vue 3 + Vite app that displays fun facts about Vue.js in a card-style layout. It uses a header, main content area, and footer components styled with a custom global stylesheet.

## Tech Stack

- **Framework**: Vue 3 (Composition API with `<script setup>`)
- **Bundler/Dev Server**: Vite
- **Language**: JavaScript
- **Styling**: Global CSS (`src/assets/main.css`)

## Getting Started

### Prerequisites

- **Node.js** (LTS recommended)
- **npm** (comes with Node)

### Install dependencies

```sh
npm install
```

### Run the development server

```sh
npm run dev
```

By default, Vite will print a local URL (e.g. `http://localhost:5173`) in the terminal. Open it in your browser to view the app.

### Build for production

```sh
npm run build
```

### Preview the production build (optional)

```sh
npm run preview
```

## Project Structure (high level)

- **`src/App.vue`**: Root component that composes the header, main content, and footer.
- **`src/main.js`**: App entry file; creates the Vue app and imports the global stylesheet.
- **`src/components/Header.vue`**: Top section with the app title/branding.
- **`src/components/Main.vue`**: Main content area for Vue facts.
- **`src/components/Footer.vue`**: Footer section for credits or links.
- **`src/assets/main.css`**: Global styles including layout and color scheme.

## Notes

- This project started from the standard Vue 3 + Vite template and has been customized into a Vue facts app with its own components and styling.
