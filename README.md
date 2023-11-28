# Project Name
 - Pinterest clone in drf

### Prerequisites

   Make sure you have the following installed on your machine:

   - [Python](https://www.python.org/downloads/) (version 3.x)
   - [Pipenv](https://pipenv.pypa.io/en/latest/install/) (optional, but recommended for virtual environment management)


## Installation

1. Clone the repository:

   git clone https://github.com/Niraj03/pinterest-drf.git
   
2. Navigate to the project directory:

   cd pinterest-drf

3. Create a virtual environment (optional, if not using Pipenv):

   python -m venv "virtual environment name"

4.  Activate the virtual environment:

   On Windows:
   .\virtual environment name\Scripts\activate

   On Unix or MacOS:
   source virtual environment name/bin/activate

5. Install dependencies:

   pip install -r requirements.txt

6. fill .env file

   fill all required value in .env file



## Running the project

1. Apply migrations:

   python manage.py migrate

2. Create a superuser (for admin access):

   python manage.py createsuperuser

3. Run the development server:

   python manage.py runserver
