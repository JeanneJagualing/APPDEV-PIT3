# My To-Do App

A cool to-do list app with a pink style and dark mode! Built with Django (backend) and React (frontend).

## Backend API Endpoints
- **GET /api/todos/**: See all my tasks
- **POST /api/todos/**: Add a new task (send: `{"title": "Do homework", "completed": false}`)
- **GET /api/todos/<id>/**: Look at one task (replace <id> with a number, like 1)
- **PUT /api/todos/<id>/**: Change a task (send: `{"title": "New title", "completed": true}`)
- **DELETE /api/todos/<id>/**: Delete a task

## How to Run It
### Backend
1. Go to `backend/`
2. Set up a virtual environment: `python -m venv venv`
3. Activate it: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
4. Install stuff: `pip install -r requirements.txt`
5. Set up the database: `python manage.py migrate`
6. Start it: `python manage.py runserver`

### Frontend
1. Go to `frontend/`
2. Install stuff: `npm install`
3. Start it: `npm start`

## Live Links
- Backend: [[RENDER]](https://appdev-pit-3.onrender.com)
- Frontend: [Put Vercel link here later]
#   P I T - 3  
 #   A P P D E V - P I T 3  
 