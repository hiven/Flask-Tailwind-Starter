# Flask + TailwindCSS Starter Template with PostCSS+PurgeCSS
---
## Key Features
- Basic Flask app scaffolding
- TailwindCSS setup using npm (with purge implemented for Production)

## How to use
Setup and activate a virtual python environment before proceeding.

Clone the repository onto your local computer and run:

1. `pip install -r requirements.txt` to install flask packages (assuming you have already  setup)
2. `npm install` to install npm packages from `package.json`
3. `npm run develop:css` to build Tailwind for development (no purge) and when ready for production run  `npm run build:css` to prepare a purged CSS build for production

Start Flask application by running `python run.py`.

Enjoy!