# saidtex Front-End

This is the Front-End application for **saidtex**, a platform to manage partners and users.  
It is built with **Next.js** and uses **TailwindCSS** and several UI libraries to deliver a modern and responsive user interface.

---

## Features

- Responsive UI built with **Next.js** + **TailwindCSS**
- Component-based architecture (Hero, Nav, Footer, About, Partners, etc.)
- Smooth scroll and section navigation
- Reusable navigation for Buy & Sell pages
- Email integration using `emailjs`

---

## Project Structure

```
Saidtex-Front-End/
├── app/
│   ├── buyandsell/
│   │   └── page.jsx              # Buy & Sell landing page
│   │
│   ├── components/               # Reusable UI components  
│   │   ├── about.jsx
│   │   ├── contact.jsx
│   │   ├── footer.jsx
│   │   ├── hero.jsx
│   │   ├── nav.jsx
│   │   ├── partenaires.jsx
│   │   ├── sellNav.jsx
│   │   └── whyus.jsx
│   │
│   ├── globals.css               # Global Tailwind styles
│   ├── layout.js                 # Root layout (Next.js)
│   └── page.js                   # Home page
│
├── public/                       # Static assets (images, icons, etc.)
│
├── package.json                  # Project dependencies & scripts
├── jsconfig.json                 # Path aliases / IntelliSense
├── next.config.mjs               # Next.js configuration
└── .gitignore
```

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/AymaneMehdi/Saidtex-Front-End.git
   cd Saidtex-Front-End
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

---

## Running the Project

```bash
npm run dev
```

Runs the project on **http://localhost:3000**

---

## Tech Stack

| Tool / Library           | Description                              |
|--------------------------|-------------------------------------------|
| **Next.js**              | React framework for building the app     |
| **React**                | Base library for UI development          |
| **TailwindCSS**          | Utility-first CSS framework              |
| **Bootstrap**            | CSS framework (optional)                 |
| **EmailJS**              | Client-side email sending                |

---

## Scripts

| Command           | Description                     |
|------------------|---------------------------------|
| `npm run dev`     | Run development server          |
| `npm run build`   | Build for production            |
| `npm start`       | Start production server         |

---

## License

This project is licensed under the [MIT License](LICENSE).
---
Copyright© Aymane Mehdi
