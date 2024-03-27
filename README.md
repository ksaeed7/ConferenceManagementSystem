# ConferenceManagementSystem
  This Conference Management System is designed to facilitate the organization and management of academic conferences. It includes functionalities such as managing submission deadlines, peer reviews, and conference schedules. Developed using Django.

## Features

- Creation and management of conferences
- Submission deadlines for abstracts and papers
- Review processes and deadlines
- User management for participants and reviewers
- Dynamic conference scheduling

## Prerequisites

Before you begin, make sure you have met the following requirements:

- Python 3.8+
- Django 3.2+
- A modern web browser

## Installation

Follow these steps to install the Conference Management System:

1. Clone the repository:
   - `git clone https://yourrepositorylinkhere.com`

2. Navigate to the project directory:
   - `cd conference_management_system`

3. Install the required dependencies:
   - `pip install -r requirements.txt`

4. Apply the database migrations:
   - `python manage.py migrate`

5. Start the development server:
   - `python manage.py runserver`

6. Visit `http://127.0.0.1:8000/` in your web browser to access the application.

## File Structure Overview

- `js_conferences.js`: JavaScript for client-side form validation and dynamic UI interactions.
- `admin.py`: Configuration for Django's admin interface, allowing admin users to manage conference details.
- `apps.py`: Application configuration for the Django app.
- `constants.py`: Contains constant values used throughout the application.
- `models.py`: Data models for the application, representing conferences, submissions, reviews, etc.
- `tests.py`: Tests for ensuring the reliability and correctness of the application.
- `urls.py`: URL routing for the application.
- `Utils.py`: Utility functions used across the application.
- `views.py`: Request-response logic for serving web pages and processing data.

## Contact

For questions or feedback regarding the Conference Management System, please contact me.
