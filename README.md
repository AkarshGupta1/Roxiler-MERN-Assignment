# Roxiler MERN Stack Assessment

## Prerequisite Software
Make sure you have the following software installed:

• Visual Studio Code: For editing and running the code.

• MongoDB Compass: For managing your MongoDB databases.

• Node.js Framework: Required for running the server and client applications.

## Steps to Run the Project

• Download the Repository:

• Start by downloading or cloning the repository from the source provided.

• Open the Project in Visual Studio Code:

• After downloading, open the project folder in Visual Studio Code.

• Set Up the Client:

• Inside Visual Studio Code, locate the "client" directory.

• Install the necessary dependencies by right-clicking on the directory and selecting "Open in Integrated Terminal." Then use the option to install the required packages.

• Set Up the Server:

• Similarly, locate the "server" directory within Visual Studio Code.

• Open the terminal in this directory and install the server dependencies.

• Running the Application:

• Open two terminals in Visual Studio Code, one for the server and one for the client.

• Start the server by clicking the "Run" or "Play" button, or by running it through the terminal.

• Start the client side similarly.

## How to Load Third-Party API Data to the Database

• Modify the Server File:

• Go to the server/server.js file.

• Find line 30 and remove the comment to enable the API data loading feature.

• Update MongoDB Configuration:

• In the server/models/ProductTransaction.js file, update the MongoDB connection URL with your own database's URL.

• Reload the Server:

• After making these changes, restart the server. The third-party API data should now be loaded into your MongoDB database.

## This description walks you through the process without relying on command lines, focusing on using the Visual Studio Code interface and MongoDB Compass.
