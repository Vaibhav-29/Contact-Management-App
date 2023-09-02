# Contact-Management-App
Creating a contact management app with ReactJS, TypeScript, TailwindCSS, React Router v6, React Query, and deploying it to GitHub involves several steps. I'll provide you with a step-by-step guide on how to create the app, explain each step, and show you how to deploy it to GitHub Pages.

npx create-react-app contact-management-app --template typescript

cd contact-management-app
npm install react-query react-query/devtools react-router-dom react-leaflet leaflet axios tailwindcss @headlessui


// services/api.ts
import axios from 'axios';

const instance = axios.create({
  baseURL: 'https://disease.sh/v3/covid-19',
});

export default instance;
