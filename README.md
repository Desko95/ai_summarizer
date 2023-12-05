# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________

////\/\/\/\/\/\/\/\/\/\\\\\\

npm create vite@latest

project name: ./ (to create project inside selected folder)
react
javascript
__________________________________________________________________________________________

 npm install @reduxjs/toolkit
 __________________
 deleted all files from src buut main.jsx
 _________________________________________________________________________________________

install talwindCSS with Vite : 

                          npm install -D tailwindcss postcss autoprefixer
then initialise it with : npx tailwindcss init -p
__________________________________________________________________________________________

Configure template paths, in tailwind.config.js file = 

                /** @type {import('tailwindcss').Config} */
                export default {
                content: [
                    "./index.html",
                    "./src/**/*.{js,ts,jsx,tsx}",
                ],
                theme: {
                    extend: {},
                },
                plugins: [],
                }
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________
__________________________________________________________________________________________

