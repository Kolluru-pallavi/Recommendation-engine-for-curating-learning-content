# Recommendation-engine-for-curating-learning-content
# Learn Spark Recommends

A modern, fast, and responsive personalized learning recommendation system built using React, TypeScript, Vite, and Tailwind CSS.

## ✨ Features

- 🔐 **Login/Register Forms**
  - Built with reusable and accessible form components
  - Client-side validation using TypeScript and responsive error handling
  - Clean UI with Tailwind CSS and integrated form logic for better user experience
  - Easily extendable for OAuth or backend integration

- 🧠 **AI/Logic-Driven Recommendation Engine**
  - Core `RecommendationEngine.tsx` component intelligently suggests learning content
  - Can be extended to use collaborative or content-based filtering techniques
  - Personalization logic based on user history, preferences, or manual input

- 🎨 **Beautiful and Consistent UI**
  - Modular UI library in `/components/ui/` using Tailwind CSS
  - Includes reusable components like buttons, alerts, accordions, badges, breadcrumbs, and more
  - Follows design system principles for scalability

- 🚀 **Fast Development Workflow**
  - Lightning-fast Hot Module Replacement (HMR) using Vite
  - Clean and structured TypeScript configuration
  - Tailwind and PostCSS for utility-first styling and build-time optimizations

- 📦 **Multiple Package Manager Support**
  - Use **npm** or **Bun** based on developer preference
  - Includes lock files for both (`package-lock.json`, `bun.lockb`)
  - Seamless setup and cross-platform compatibility

## 🛠️ Tech Stack

- **React** (with JSX/TSX)
- **TypeScript** (typed components and logic)
- **Tailwind CSS** (responsive, utility-first styling)
- **Vite** (build tool and dev server)
- **Bun / npm** (dependency and script management)
- **Modular Components** (auth, UI, engine)

## 🧩 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/learn-spark-recommends.git
cd learn-spark-recommends

# If using npm:
npm install
npm run dev

# If using Bun (if installed):
bun install
bun dev
