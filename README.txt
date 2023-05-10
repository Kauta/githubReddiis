# PBS Project

## Introduction
Welcome to the PBS Project! This is a web application that scrapes property data from Rightmove, allows user authentication, stores the scraped data in a MySQL database, and enables property recommendations using NLTK. 

## Technologies Used
The following technologies were used to develop this application:
- Python
- Flask
- MySQL
- Beautiful Soup
- NLTK
- Jinja2
- HTML/CSS/JS

## Installation and Setup
1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required packages by running `pip install -r requirements.txt` in the terminal.
4. Set up a MySQL database using the schema in `database_schema.sql` file.
5. Update the `config.py` file with your database credentials.
6. Run the application by executing the command `python app.py` in the terminal.
7. Navigate to `http://localhost:5000` on your browser to view the application.

## How to Use
1. Register as a new user or log in if you already have an account.
2. Click on "Scrape Properties" to start scraping properties from Rightmove. This may take a few minutes depending on the number of pages to be scraped.
3. Click on "View Properties" to view the properties that have been scraped and stored in the database.
4. Click on "Logout" to log out of your account.

## Future Work
- Improve the recommendation algorithm by using more advanced techniques.
- Implement a feature that allows users to save their favorite properties.
- Add more property websites to scrape from.
- Improve the user interface and experience.

## Contributors
- Sarah Abeja

## Credits
- This project was completed as part of the requirements for the completion of a PBS Msc.