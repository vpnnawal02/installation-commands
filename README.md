# React installation
npm create vite@latest {name of project}


# Tailwind installation to React
npm install tailwindcss @tailwindcss/vite
  
## in vite.config.js file
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'
import tailwindcss from '@tailwindcss/vite'

// https://vite.dev/config/
export default defineConfig({
  plugins: [
    react({
      babel: {
        plugins: [['babel-plugin-react-compiler']],
      },
    }),
    tailwindcss(),],
})
## In index.css
  @import "tailwindcss";


# Setting up Django
  ## creating virtual environment
    python -m venv .venv
  ## activate virtual environment
    .venv\Scripts\activate.bat
  ## installing django
    pip install Django
  ## creating new django project
    django-admin startproject {myproject}
      cd {myproject}
  ## starting project
    python manage.py runserver
