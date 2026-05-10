# Derma Glow Clinic

## Overview

This repository contains the source code for the demo portfolio website of Derma Glow Clinic, a modern web application showcasing contemporary design and functionality.

## Description

This is a demo portfolio website built to demonstrate best practices in web development, featuring responsive design, interactive elements, and optimized performance.

## Technologies Used

- Vite
- TypeScript
- React
- Tailwind CSS (if applicable)
- Other modern web technologies

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- Bun package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Derma_Glow_Clinic
   ```

2. Install dependencies:
   ```bash
   bun install
   ```

3. Start the development server:
   ```bash
   bun run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port specified by Vite).

## Build

To build the project for production:

```bash
bun run build
```

## License

<<<<<<< HEAD
- Node.js 22.12.0 or newer

Start the development server:

```bash
npm run dev
```

## Production Build

Create the production build:

```bash
npm run build
```

Run the built app locally:

```bash
npm run start
```

## Vercel Deployment

This project is configured to deploy on Vercel.

- `vercel.json` sets the install command to `npm install`
- `vercel.json` sets the build command to `npm run build`
- Nitro is enabled in `vite.config.ts` so TanStack Start can deploy correctly on Vercel
- No environment variables are required for deployment

Typical deployment flow:

1. Push the repository to GitHub.
2. Import the repository into Vercel.
3. Deploy with the default project settings.

## Project Structure

```text
src/
  assets/              Static images used in the UI
  components/site/     Page sections such as hero, treatments, doctors, footer
  components/ui/       Shared UI primitives
  routes/              TanStack Start route files
  lib/                 Small utility helpers
  styles.css           Global styles and design tokens
public/
  favicon.svg          Browser-tab logo
  site.webmanifest     Basic web app metadata
```

=======
This project is for demonstration purposes only and is not licensed for commercial use.
>>>>>>> 2740f68 (Final Push)
