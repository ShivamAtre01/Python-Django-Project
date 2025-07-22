# Python-Django-Project
# Django Twitter-Like App

A Django-based microblogging web application similar to Twitter. Users can post tweets, view others' tweets, and manage media content.

## Features

- User Authentication (Login, Logout)
- Tweet creation and display
- Media support (Image uploads)
- Static and responsive templates
- SQLite for local development
- Admin panel for management

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/ShivamAtre01/Python-Django-Project.git
cd Python-Django-Project
2)Set Up Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3) Install Dependencies
pip install -r requirement.text

4)Apply Migrations

python manage.py makemigration tweet
python manage.py migrate

5)Run the Development Server
python manage.py runserver
Know you get website page 
