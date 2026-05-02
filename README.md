# DermaGlow Skin Clinic

DermaGlow Skin Clinic is a premium single-page dermatology website built as a frontend portfolio project. It showcases polished visual design, responsive layout work, reusable component structure, and a production-ready React setup suitable for modern service-brand landing pages.

## Project Purpose

This repository was created for portfolio and demonstration use.

- The brand, clinic, testimonials, doctors, and business details are fictional.
- The project is intended to showcase UI design, frontend engineering, and deployment readiness.
- It can be used as a reference for luxury clinic websites, wellness brands, and high-end marketing landing pages.

## What This Project Demonstrates

- Premium hero design with layered visuals and motion
- Responsive navigation and section-based landing page architecture
- Reusable UI composition with clean React components
- Modern styling with Tailwind CSS v4 design tokens
- Lightweight motion and interaction polish with Framer Motion
- Deployment-ready setup for Vercel

## Tech Stack

- React 19
- TanStack Start
- Vite 7
- TypeScript
- Tailwind CSS v4
- Framer Motion
- Lucide React

## Local Development

Install dependencies:

```bash
npm install
```

Recommended runtime:

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

