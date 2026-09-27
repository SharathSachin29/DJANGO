# Django Practice

Repository containing Django semester course materials, manuals, and practice projects.

## Project Structure

- **`practice2_library/`**: Django Library Management Application
  - Book listing, addition, and management views
  - Configured with SQLite database and migration files
- **Course Documents & Manuals**:
  - `Django_Class.pdf`
  - `Django_Practice_Manual_1_Static_Website.pdf`
  - `Django_Practice_Manual_2_Database_Website.pdf`

## Setup & Running the Project

1. Navigate to the project directory:
   ```bash
   cd practice2_library
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # macOS/Linux:
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```
