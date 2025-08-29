# Shopco

Shopco is a personal project where I built a modern, fully responsive e-commerce front-end based on a Figma design. The application is developed using **Next.js 14 App Router**, **TypeScript**, **Tailwind CSS**, **Redux**, **Framer Motion**, and **ShadCN UI**, providing a scalable and optimized solution that follows industry best practices.

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Contact](#contact)

## Overview

This project showcases how I transformed a Figma design into a production-ready Next.js application. It emphasizes **performance optimization**, **SEO best practices**, and **accessibility**, making it a strong foundation for modern e-commerce front-end applications.

## Demo

Check out the live demo: [Shopco Demo](https://YOUR_DEPLOYED_LINK.vercel.app/)

## Features

- **Next.js 14**: Server-side rendering (SSR), Static Site Generation (SSG), optimized routing, and API integrations.
- **TypeScript**: Strongly typed code for better error detection and maintainability.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Redux**: State management for managing the shopping cart and global states.
- **Framer Motion**: Smooth animations and transitions for an enhanced user experience.
- **ShadCN UI**: Beautifully styled, accessible, and customizable UI components.
- **Fully Responsive**: Mobile-first design ensuring the layout adapts across devices.
- **Performance Optimized**: Best practices followed for fast loading and interaction.
- **Accessible**: Built with accessibility standards to provide an inclusive experience.

## Technologies

- **Next.js 14**
- **TypeScript**
- **Tailwind CSS**
- **Redux**
- **Framer Motion**
- **ShadCN UI**
- **Figma** 

## Installation

To get started locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/next-ecommerce-shopco.git
   cd next-ecommerce-shopco


2. **Install dependencies:**

   ```bash
   npm install
   ```

   ```bash
   yarn install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

   ```bash
   yarn dev
   ```

4. **Open in your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

- To explore or modify the code, navigate through the `components`, `features`, and `app` directories.
- The shopping cart logic is managed using **Redux**. You can find the store configuration and cart actions in the `src/lib/features` directory.
- **ShadCN UI** components are used across the app. They can be customized in the `src/components/ui` directory.
- You can easily modify and extend the project to suit your needs, whether for personal use or professional projects.

## Project Structure

```bash
Shopco/
│
├── public/                # Static assets
├── src/
│   ├── app/               # Next.js App Router
│   ├── components/        # Reusable components (including ShadCN UI components)
│   └── lib/
│       ├── features/      # The Redux logics for features (e.g., shopping cart)
│       ├── hooks/         # Custom React hooks
│       ├── store.ts       # Redux store
│       ├── utils.ts       # Utility functions
│   ├── styles/            # Tailwind CSS styles (global, utilities and fonts)
│   ├── types/             # TypeScript types
│
├── components.json         # ShadCN UI configuration
├── next.config.mjs         # Next.js configuration
├── package.json            # Node.js dependencies and scripts
├── postcss.config.mjs      # Post CSS configuration
└── README.md               # Project documentation
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
```

## Contact

Feel free to reach out to:

- **Name**: Muhammad Faizan
- **Email**: [faizan.devstack@gmail.com](mailto:faizan.devstack@gmail.com)
- **GitHub**: [https://github.com/faizan-devstack](https://github.com/faizan-devstack)
