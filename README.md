# Phonepe_Pulse_Data_Visualization

### The Phonepe Pulse Data Visualization and Exploration tool is a user-friendly web application that enables users to explore and visualize data related to the Phonepe Pulse digital payments platform in India.

### The tool offers a variety of pre-built visualizations and custom visualization creation capabilities, allowing users to gain basic insights and perform more advanced analysis of the platform's usage.

# Required libraries

import [libraries]

## WorkFlow

### Importing the Libraries:

Importing the libraries. As I have already mentioned above the list of libraries/modules needed for the project. First we have to import all those libraries. If the libraries are not installed already use the below piece of code to install.

      !pip install ["Name of the library"]
      
If the libraries are already installed then we have to import

       import[Req.Libraries]
       
### Data extraction:

Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format.

       response = requests.get('https://api.github.com/repos/PhonePe/pulse')
       
### Data transformation:

In this step the JSON files that are available in the folders are converted into the readeable and understandable DataFrame format by using the for loop and iterating file by file and then finally the DataFrame is created. In order to perform this step I've used os, json and pandas packages. And finally converted the dataframe into CSV file and storing in the local drive.

### Database insertion:

To insert the datadrame into SQL first I've created a new database and tables using SQLite3

### Dashboard creation:

To create colourful and insightful dashboard I've used Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in Pie, Bar, Geo map functions are used to display the data on a charts and map and Streamlit is used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.





             

