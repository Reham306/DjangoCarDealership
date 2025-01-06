


# Django Car Dealership

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python Version](https://img.shields.io/badge/python-3.10%2B-green)](https://www.python.org/downloads/)  
[![Django Version](https://img.shields.io/badge/django-4.2%2B-green)](https://www.djangoproject.com/)  

This is the backend service for the **Car Dealership** platform. The project integrates Django with IBM Cloud Functions and Watson NLU to manage car dealership data, user reviews, and their analysis.

---

## Table of Contents
- [Features](#features)  
- [Setup Instructions](#setup-instructions)  
- [Project Structure](#project-structure)  
- [Technologies Used](#technologies-used)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features
- **Django Backend**: Powers the car dealership platform with RESTful APIs.  
- **Integration with IBM Cloud**: Utilizes IBM Cloud Functions for data fetching and processing.  
- **Watson NLU Analysis**: Provides sentiment analysis for user reviews.  
- **SQLite Database**: Local development database.  

---

## Setup Instructions

### Prerequisites  
- Python 3.10+  
- Git  
- Virtual Environment (optional but recommended)  

### Steps to Set Up
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Reham306/DjangoCarDealership.git  
   cd DjangoCarDealership  
   ```  

2. Create and activate a virtual environment:  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # For Linux/macOS  
   venv\Scripts\activate  # For Windows  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Apply migrations to set up the database:  
   ```bash  
   python manage.py makemigrations  
   python manage.py migrate  
   ```  

5. Start the development server:  
   ```bash  
   python manage.py runserver  
   ```  

6. Open your browser and navigate to `http://127.0.0.1:8000/` to view the app.  

---

## Project Structure
```
DjangoCarDealership/
├── manage.py
├── requirements.txt
├── .gitignore
├── README.md
├── car_dealership/  # Main Django app
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
└── templates/       # HTML Templates
```

---

## Technologies Used
- **Django**: Web framework for Python.  
- **IBM Cloud Functions**: Serverless APIs for data integration.  
- **IBM Watson NLU**: Sentiment analysis for user reviews.  
- **SQLite**: Local database for development.  

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any suggestions or improvements.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


