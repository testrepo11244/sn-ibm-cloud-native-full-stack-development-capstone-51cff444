# Best Cars Dealership

**Repository name:** `xrwvm-fullstack_developer_capstone`

**Project name:** Best Cars Dealership

## Project Overview

Best Cars Dealership is a full-stack car dealership web application developed as part of the IBM Full Stack Application Development Capstone Project. The application allows users to browse dealerships across the United States, filter dealers by state, view dealer details and customer reviews, register and log in, submit reviews, and view car makes and models. The project uses Django and Django REST Framework on the backend, React on the frontend, and integrates IBM Cloud services for sentiment analysis and deployment.

## Key Features

- User registration, login, and logout functionality
- Dealer listing with state-based filtering
- Dealer detail pages with customer reviews
- Review submission and sentiment analysis using IBM Watson Natural Language Understanding
- Car make and model lookup APIs
- Admin interface for managing dealer data
- CI/CD pipeline using GitHub Actions
- Cloud deployment on IBM Cloud Code Engine

## Technology Stack

- **Backend:** Django, Django REST Framework, Python
- **Frontend:** React, JavaScript, HTML, CSS
- **Database:** SQLite / PostgreSQL
- **Cloud Services:** IBM Cloud Code Engine, IBM Watson Natural Language Understanding
- **CI/CD:** GitHub Actions

## Project Structure

```
xrwvm-fullstack_developer_capstone/
├── README.md
├── server/
│   ├── manage.py
│   ├── frontend/
│   │   ├── static/
│   │   │   ├── About.html
│   │   │   ├── Contact.html
│   │   │   └── css/
│   │   └── src/
│   │       └── components/
│   │           └── Register/
│   │               └── Register.jsx
│   └── djangoapp/
│       ├── models.py
│       ├── views.py
│       ├── urls.py
│       └── serializers.py
└── .github/
    └── workflows/
        └── django.yml
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/xrwvm-fullstack_developer_capstone.git
   ```

2. Install backend dependencies:
   ```bash
   cd server
   pip install -r requirements.txt
   ```

3. Run database migrations:
   ```bash
   python manage.py migrate
   ```

4. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

5. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```

6. Start the React development server:
   ```bash
   npm start
   ```

## Authors

- Best Cars Dealership Capstone Team
- IBM Skills Network Full Stack Application Development Capstone Project

## License

This project is created for educational purposes as part of the IBM Skills Network Full Stack Application Development Capstone Project.