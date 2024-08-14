Data Collection Module 11

This repository contains the assignments and projects related to Module 11 of my data analysis bootcamp. The focus of this module is on data collection, specifically through web scraping and API interactions. The main project involves scraping data related to Mars and conducting an analysis of the collected data.

Table of Contents
-Project Overview
-Files in the Repository
-Technologies Used
-Installation
-Usage
-Project Details
-Contributors

Project Overview

In this module, I learned how to collect data from the web using Python libraries such as BeautifulSoup, Splinter, and APIs. The main project focuses on scraping Mars-related data from various websites and performing an analysis on the collected data. The insights gained from this project provide a deeper understanding of Mars' weather patterns and other relevant information.


Files in the Repository

-part_1_mars_scraping.ipynb: A Jupyter notebook that details the process of scraping Mars data from NASA's website and other sources.

-part_2_mars_weather.ipynb: A Jupyter notebook that analyzes the scraped Mars weather data.

-mars_data.py: A Python script that automates the data scraping process.
-scrape_mars.py: A Python script that scrapes the latest Mars data and stores it in a MongoDB database.
-app.py: A Flask application that serves a web page displaying the scraped Mars data.
-index.html: The main HTML file for the Flask web application.

Technologies Used

-Python: The primary language used for data collection and analysis.
-BeautifulSoup: A Python library used for web scraping.
-Splinter: A tool for automating browser actions, useful in web scraping.
-Pandas: For data manipulation and analysis.
-Flask: A micro web framework used to create the web application.
-MongoDB: A NoSQL database used to store the scraped data.
-HTML/CSS: For creating the web interface.


Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Dozsoybootcamp/Datacollection_module11.git
Navigate to the project directory:
bash
Copy code
cd Datacollection_module11
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Set up MongoDB on your local machine or use a cloud-based MongoDB service.
Usage
Run the scrape_mars.py script to collect the latest Mars data:
bash
Copy code
python scrape_mars.py
Start the Flask web application:
bash
Copy code
python app.py
Open your web browser and navigate to http://localhost:5000 to view the Mars data.


Project Details

Mars Scraping: This project scrapes data from NASA's Mars mission websites, including the latest news, featured images, Mars facts, and weather data.
Mars Weather Analysis: The second part of the project analyzes the scraped weather data to uncover patterns and insights about the Martian atmosphere.
Web Application: The Flask web app serves the scraped data in an easy-to-read format, with dynamic updates based on the latest available information.

Contributors
Duygu - GitHub Profile
