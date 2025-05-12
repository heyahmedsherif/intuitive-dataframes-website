# Intuitive Dataframes Website

A simple and modern website for Intuitive Dataframes built with Flask.

## Features

- Clean and responsive design
- Multiple pages (Home, About, Contact)
- Contact form
- Modern UI with CSS animations

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On Windows:
```bash
venv\Scripts\activate
```
- On macOS/Linux:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Make sure your virtual environment is activated
2. Run the Flask application:
```bash
python app.py
```
3. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
.
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── static/            # Static files (CSS, images)
│   └── css/
│       └── style.css
└── templates/         # HTML templates
    ├── base.html
    ├── index.html
    ├── about.html
    └── contact.html
```

## Development

- The application runs in debug mode by default
- Templates use Jinja2 templating engine
- CSS is organized in a single file for simplicity
