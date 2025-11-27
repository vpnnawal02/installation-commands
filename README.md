# React installation
npm create vite@latest {name of project}


# Tailwind installation to React
npm install tailwindcss @tailwindcss/vite
  
## in vite.config.js file
import { defineConfig } from 'vite' <br>
import react from '@vitejs/plugin-react'<br>
import tailwindcss from '@tailwindcss/vite'<br>
<br>
export default defineConfig({<br>
  plugins: [<br>
    react({<br>
      babel: {<br>
        plugins: [['babel-plugin-react-compiler']],<br>
      },<br>
    }),<br>
    tailwindcss(),],<br>
})<br>
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
