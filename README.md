# Todo Application

A full-stack todo application with Python Flask backend and JavaScript frontend.

## Features

- Create, read, update, and delete todos
- Mark todos as complete/incomplete
- Filter todos by status (all, active, completed)
- Real-time statistics
- Responsive design
- Clean and modern UI

## Tech Stack

### Backend
- Python 3.x
- Flask 3.0.0
- Flask-SQLAlchemy 3.1.1
- Flask-CORS 4.0.0
- SQLite database

### Frontend
- Vanilla JavaScript (ES6+)
- HTML5
- CSS3
- Fetch API for HTTP requests

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
- Windows: `venv\Scripts\activate`
- Mac/Linux: `source venv/bin/activate`

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Run the Flask server:
```bash
python app.py
```

The backend will be available at `http://localhost:5000`

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Open `index.html` in your browser, or use a local server:
```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`

## API Endpoints

- `GET /api/todos` - Get all todos
- `GET /api/todos/<id>` - Get a specific todo
- `POST /api/todos` - Create a new todo
- `PUT /api/todos/<id>` - Update a todo
- `DELETE /api/todos/<id>` - Delete a todo
- `PATCH /api/todos/<id>/toggle` - Toggle todo completion status
- `GET /api/health` - Health check endpoint

## Project Structure

```
todo-app/
├── backend/
│   ├── app.py           # Flask application and routes
│   ├── database.py      # Database initialization
│   ├── models.py        # SQLAlchemy models
│   └── requirements.txt # Python dependencies
├── frontend/
│   ├── index.html       # Main HTML file
│   ├── app.js          # JavaScript application logic
│   ├── styles.css      # CSS styles
│   └── README.md       # Frontend documentation
├── .gitignore
├── package.json
└── TECHNICAL_PLAN.md   # Detailed technical documentation
```

## License

MIT License

---

Made with Bob