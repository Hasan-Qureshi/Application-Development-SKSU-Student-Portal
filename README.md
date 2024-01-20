# Application-Development-SKSU-Student-Portal
The repository contains the source code for the SKSU Student portal project.
Directory

SKSU Website
 ├── pycache
 ├── huza
 ├── uploaded_files
 ├── main.py (database connect, fastapi, all the APIs)
 ├── middleware.py (port configuration)
 ├── models.py (pydantic model)
 ├── frontend
 │   ├── package.json
 │   ├── postcss.config.js
 │   ├── public
 │   │   ├── assets
 │   │   │   └── images  # All Project Images
 │   │   ├── favicon.ico
 │   │   ├── index.html
 │   │   ├── manifest.json
 │   │   └── robots.txt
 │   ├── README.md
 │   ├── src
 │   │   ├── App.jsx
 │   │   ├── assets
 │   │   │   └── fonts  # Project fonts
 │   │   ├── components  # UI and Detected Common Components
 │   │   ├── constants  # Project constants, e.g., string consts
 │   │   ├── hooks  # Helpful Hooks
 │   │   ├── index.jsx
 │   │   ├── pages  # All route pages
 │   │   ├── Routes.jsx  # Routing
 │   │   ├── styles
 │   │   │   ├── index.css  # Other Global Styles
 │   │   │   └── tailwind.css  # Default Tailwind modules
 │   │   └── util
 │   │       └── index.jsx  # Helpful utils
 │   └── tailwind.config.js  # Entire theme config, colors, fonts, etc.
 └── .gitignore  # Gitignore file for the entire project


1) To start running the dev env for backend install the required dependencies for uvicorn and run this command:
        -uvicorn main:app --reload
2) To start running the dev env for frontend install the required dependencies for javascript react and tailwind, and
   run this command:
        -npm start
