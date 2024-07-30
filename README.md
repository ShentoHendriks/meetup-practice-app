# Shento Hendrik's Barebone SvelteKit with Tailwind Integration

## Description

This project is a barebone setup of SvelteKit integrated with Tailwind CSS. It provides a minimalistic starting point for building modern web applications with SvelteKit and Tailwind CSS. The configuration includes essential tools and settings to streamline development and ensure a smooth workflow.

## Features

- **SvelteKit Framework**: Utilizes the powerful SvelteKit framework for building fast and scalable web applications.
- **Tailwind CSS**: Integrated with Tailwind CSS for utility-first styling, allowing for rapid UI development.
  - **Automatic Class sorting**: Has the official prettier Tailwind CSS Class sorter, based on their recommended order.
- **Vite**: Uses Vite as the build tool for fast and efficient development and production builds.
- **PostCSS**: Configured with PostCSS for processing CSS with plugins like Autoprefixer.
- **Prettier**: Includes Prettier for code formatting, ensuring a consistent code style across the project.
- **TypeScript Support**: Configured to support TypeScript for type-safe development.
- **Svelte Preprocess**: Uses `vitePreprocess` for preprocessing Svelte files, enabling features like TypeScript and SCSS.
- **Adapter Auto**: Configured with `@sveltejs/adapter-auto` for seamless deployment to various environments.
- **Linting and Formatting**: Includes scripts for linting and formatting the codebase using Prettier.

## Getting Started

To get started with this project, clone the repository and install the dependencies:

```sh
git clone https://github.com/ShentoHendriks/sveltekit-barebone-tailwind.git
cd <repository-directory>
npm install