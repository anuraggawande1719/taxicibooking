# Taxi Booking Application

This is a Django-based taxi booking application that allows users to book taxis online. It includes features such as user registration, taxi booking, and viewing booking history and give customer payment receipt .

## Features

- User Registration and Authentication
- Taxi Booking Detail
- Customers Booking History
- New Taxi Detail
- Payment Receipt

## Technologies Used

- Django
- Python
- MySQL
- HTML/CSS

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Django 3.x
- MySQL
- pip (Python package installer)

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/taxicibooking.git
    cd taxicibooking
    ```

2. **Create and Activate Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up MySQL Database**

    - Create a database named `taxicibooking` in MySQL.
    - Update the database settings in `taxicibooking/settings.py`:

    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.mysql',
            'NAME': 'taxicibooking',
            'USER': 'your_mysql_user',
            'PASSWORD': 'your_mysql_password',
            'HOST': 'localhost',
            'PORT': '3306',
        }
    }
    ```

5. **Run Migrations**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Create a Superuser**

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the Server**

    ```bash
    python manage.py runserver
    ```

8. **Access the Application**

    Open your web browser and go to `http://127.0.0.1:8000`.

## Project Structure

- `taxicibooking/`: Root directory of the project.
- `taxicibooking/settings.py`: Django settings for the project.
- `taxicibooking/urls.py`: URL declarations for the project.
- `taxicibooking/wsgi.py`: WSGI configuration for the project.
- `booking/`: Django application for taxi booking.
- `templates/`: HTML templates for the project.


## License

This project is licensed under the MIT License.

## Contact

If you want to contact me you can reach me at anuraggawande2001@gmail.com.

