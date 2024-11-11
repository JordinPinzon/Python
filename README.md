# Project - Flask

This project is a simple "Hello World" application built with [Flask](https://flask.palletsprojects.com/).

## Student Name

Jordin Pinzon

## Course

SI8 - P2

## Option 1: 
## Clone the Repository from GitHub

1. Install Git
If you don't have Git installed, go to the official Git page and download it from the website: " https ://git -scm .com/ ". Install it following the instructions for your operating system.
2. Clone the Repository from GitHub
Open the terminal or command line on your computer and navigate to the folder where you want to clone the project. Then, use the command:
git clone https://github.com/JordinPinzon/Python.git

## Install Dependencies
Once you have cloned the repository, enter the project folder with the command:
cd Flask

Next, install all the necessary dependencies using the command:
Run `pip install -r requirements.txt` to install all the required dependencies.

## Start Server
After installing the dependencies, run the Flask server with the following command:
Run `python app.py` to start the Flask development server.
## Check the project
Open your browser and access the following URL:
Navigate to `http://localhost:5000/`.
The application will automatically reload if you change any of the source files.

## Option 2
## Download the Docker Hub Image
1. Install Docker
If you don't have Docker installed, go to the official Docker page and download it from " https ://www .docker .com /products /docker -desktop ". Follow the instructions to install Docker on your operating system.
2. Download Image from Docker Hub
Open your terminal and run the following command to download the Docker image:
Docker pull jordin13/Python-app :nombreetiqueta
## Build the Docker Image
Once the image is downloaded, you can run the image with the command:
docker build -t flask-app .
## Run the container
Once the image is downloaded, run a container using the following command:
docker run -p 5000:5000 --name AppPython flask-app 
## Access the Project
Open your browser and go to the following address:
http://localhost:5000
