# Animal Shelter Dashboard

## Project Overview

The Animal Shelter Dashboard is a Python-based application I originally developed for CS 340: Client/Server Development at Southern New Hampshire University. The application allows users to search animal shelter records, view information in a table, and explore the data through interactive visualizations.

I developed the application using **Python, MongoDB, and Jupyter Notebook**. For my CS 499 Computer Science Capstone, I enhanced the original dashboard by adding full CRUD functionality, user authentication, improved input validation, and additional data management features.

## Application Features

The enhanced application includes:

- **Animal Record Search:** Users can search and filter animal shelter records stored in MongoDB.
- **Full CRUD Functionality:** Users can create, read, update, and delete animal records directly through the dashboard.
- **User Authentication:** A login system restricts database modifications to authorized users. Passwords are hashed using bcrypt.
- **Data Management:** Users can add new animal records, edit existing information, and delete records through separate dashboard tabs.
- **Input Validation:** Additional checks help prevent invalid or incomplete information from being entered into the database.
- **Automatic Calculations:** Date of birth information is used to calculate age-related fields automatically.
- **Data Visualizations:** A bar chart displays animal record information, replacing the original pie chart.
- **Interactive Map:** Displays geographic information associated with animal records.
- **Improved Navigation:** The dashboard layout was reorganized to make searching and managing records easier.

## Technologies Used

- Python
- MongoDB
- PyMongo
- Jupyter Notebook
- Dash and Plotly
- Pandas
- Dash Leaflet
- bcrypt

## Original Application and Enhancements

The original application provided a dashboard for searching animal shelter records and viewing the results through a data table, pie chart, and interactive map.

For my capstone enhancement, I expanded the dashboard into a full CRUD application, allowing users to add, update, and delete records instead of only searching the database. I also implemented user authentication to control access to database modifications.

Additional improvements included stronger input validation, automatic age calculations, updated data fields, and a redesigned layout. I replaced the pie chart with a bar chart to improve how information was displayed while keeping the interactive map.

These changes expanded the application's functionality and allowed me to apply database management, authentication, and application development skills to an existing project.

## How to Access and Run the Application

The repository contains two versions of the dashboard:

- **AnimalShelterDashboard_Original.zip:** The original application developed in CS 340.
- **AnimalShelterDashboard_Enhanced.zip:** The enhanced application completed for CS 499.

### Requirements

To open and run the application, you will need:

- Python
- JupyterLab or Jupyter Notebook
- MongoDB
- Required Python libraries, including PyMongo, Dash, Plotly, Pandas, Dash Leaflet, and bcrypt

### Setup Instructions

1. Download the ZIP file for the version you want to review.
2. Extract the ZIP file to a folder on your computer.
3. Install MongoDB and the required Python libraries.
4. Create a MongoDB database named `aac` with an `animals` collection.
5. Import the animal shelter dataset included with the enhanced application into MongoDB.
6. Configure the MongoDB connection settings in the CRUD Python module.
7. Open the dashboard notebook in JupyterLab or Jupyter Notebook.
8. Make sure the CRUD Python module is named `CRUD_Python_Module.py` and is accessible from the notebook.
9. Run the notebook cells to launch the dashboard.

The application was originally developed in Codio using JupyterLab and MongoDB. Running it outside Codio requires a local MongoDB database and the appropriate Python dependencies.
