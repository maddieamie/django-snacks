
# LAB - Class 26 
**Project**: Django Snacks Project  
**Author**: Maddie Amelia Lewis

---

### Links and Resources

- **Back-end server URL**: N/A (Local development server: `http://127.0.0.1:8000/`)
- **Front-end application**: N/A (Styled with TailwindCSS for local display)

---

### Setup

#### .env requirements (where applicable)
- Not applicable for this project

#### How to initialize/run your application
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/django-snacks.git
   cd django-snacks
   ```

2. Set up the virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   pip install django
   ```

3. Install TailwindCSS:
Follow the documentation: https://django-tailwind.readthedocs.io/en/latest/installation.html

4. Initialize Django project:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

5. View the website on `http://127.0.0.1:8000/`.

#### How to use your library
- This project creates a simple multi-page Django website with two pages: Home and About.
- Navigate to `/` for the home page and `/about/` for the about page.
- Basic styling is done using TailwindCSS and Flowbite for navigation elements.

---

### Version 1

- Created a Django project named `snacks_project` and an app named `snacks`.
- Configured views, URLs, and templates for Home and About pages.
- Used an ancestor `base.html` template for shared navigation.
- Wrote and passed tests to check for correct URL responses and template usage.


### Tests

#### How do you run tests?
1. To run the Django tests:
   ```bash
   python manage.py test
   ```

#### Any tests of note?
- Tests include:
  - Checking that the Home and About pages return status code `200`.
  - Verifying that both the Home and About pages use the correct templates, including the ancestor `base.html`.

#### Describe any tests that you did not complete, skipped, etc.
- No tests were skipped in this version.

---
