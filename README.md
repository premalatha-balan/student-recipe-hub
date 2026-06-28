# 🍳 Student Recipe Hub

A recipe finder for university students - focused on meals that are:
- 💰 **Cheap** (student budget friendly)
- ⏱️ **Fast** (less than 30 minutes)
- 🍽️ **Delicious** (actually tasty!)

## Features

- 🔍 **Pantry Search**: Type what ingredients you have, and find recipes that use ALL of them
- 💰 **Cost Indicators**: Each recipe shows if it's Cheap, Mid, or a Treat
- ⏱️ **Time Filters**: Quick meals for busy study sessions
- 📱 **Mobile Friendly**: Built for students on their phones

## Tech Stack

- Backend: Python Flask
- Database: SQLite
- Frontend: HTML, CSS, Vanilla JavaScript

## Quick Start

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate` (Mac/Linux) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Initialize the database: `sqlite3 recipes.db < schema.sql`
6. Run the app: `python app.py`
7. Open `http://127.0.0.1:5000` in your browser

## Future Plans

- [ ] User accounts to save favorite recipes
- [ ] Shopping list generator
- [ ] Submit your own recipes
- [ ] Meal planning calendar