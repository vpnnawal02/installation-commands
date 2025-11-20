# React installation
npm create vite@latest {name of project}


# Tailwind installation to React
npm install tailwindcss @tailwindcss/vite
  
## in @tailwindcss/vite file
  import { defineConfig } from 'vite'
  import tailwindcss from '@tailwindcss/vite'
  export default defineConfig({
    plugins: [
      tailwindcss(),
    ],
  })

## In index.css
  @import "tailwindcss";


#Setting up Django
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
