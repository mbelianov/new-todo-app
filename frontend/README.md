# Todo App Frontend

Vanilla JavaScript frontend for the Todo application.

## Features

- Clean, modern UI with responsive design
- Real-time todo management
- Filter by status (all, active, completed)
- Statistics dashboard
- Toast notifications
- Keyboard shortcuts (Ctrl/Cmd + K to focus input)

## Setup

Simply open `index.html` in a web browser, or serve it using a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`

## Configuration

The API base URL is configured in `app.js`:

```javascript
const API_BASE_URL = 'http://localhost:5000/api';
```

Make sure the Flask backend is running on port 5000.

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

Requires ES6+ support for modern JavaScript features.