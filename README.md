# panaverse-tailwind

1) Create a Next.js Project with following command
npx create-next-app@latest --experimental-app
2) Delete all things in app/Page.tsx
3) Install Tailwind.Css with following command
npm install -D tailwindcss postcss autoprefixer
4) Create a Css config File with following command
npx tailwindcss init -p
5) Edit the Tailwind.config.js by folowing methods
write following in content
{./src/**/*.{js,ts,jsx,tsx}}
Edit global.css by following code
@tailwind base;
@tailwind components;
@tailwind utilities;
6) Test your tailwind by writting a heading of Hello World

