# Flight-Booking
To run a this project,  typically need to follow these steps:


### 1. Install Dependencies
Ensure all dependencies specified in `requirements.txt` are installed:

```bash
pip install -r requirements.txt
```

### 2. Apply Migrations
To apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 3. Start the Server
To run the Django server:

```bash
python manage.py runserver
```

This command starts the server locally, typically at `http://127.0.0.1:8000/`. You should see output similar to:

```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
July 13, 2024 - 12:00:00
Django version 3.2.4, using settings 'your_project.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

### 4. Access Your Django Project
Open a web browser and go to `http://127.0.0.1:8000/` (or `http://localhost:8000/`). 

