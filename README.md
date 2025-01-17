# Home-Automation-through-IOT-using-cloud-servies-
### Overview
This project is a Home Automation Device developed using Internet of Things (IoT) technology, integrating various Google Cloud Services. It allows users to control home appliances remotely through a web interface. The system is built using a Flask web server and is hosted on Google Cloud Platform (GCP). User commands are stored and retrieved using Firebase Realtime Database.

## Features
* Home Automation Device: Control home appliances remotely.
* Flask Web Server: The backend is developed using Flask to handle web requests and process user commands.
* Google Cloud Platform Integration: Utilizes GCP Compute Engine, GCP Buckets, and GCP Load Balancer for hosting and managing the application.
* Firebase Realtime Database: Stores and retrieves user input commands to operate the devices in real-time.

## Components
1. Flask Web Server:
Handles HTTP requests from the web interface.
Processes user commands and interacts with Firebase to store and retrieve data.
2. Firebase Realtime Database:
Real-time database to store user commands.
Provides instant data synchronization across devices.
3. Google Cloud Platform:
GCP Compute Engine: Hosts the Flask web server and handles computation tasks.
GCP Buckets: Stores static files and assets.
GCP Load Balancer: Distributes incoming traffic to ensure reliability and performance.

## Installation and Setup
1. Clone the Repository:
    git clone https://github.com/vrushali-more28/Home-Automation-through-IoT-using-Cloud-Services.git
    cd Home-Automation-through-IoT-using-Cloud-Services
2. Set Up Virtual Environment:
    python3 -m venv venv
    source venv/bin/activate
3. Install Dependencies:
    pip install -r requirements.txt
4. Configure Firebase:
    * Create a Firebase project and obtain the firebaseConfig object.
    * Replace the placeholder configuration in your project with your Firebase configuration details.
5. Run the Flask Server:
    export FLASK_APP=app.py
    flask run
6. Deploy on Google Cloud Platform:
    * Set up a project on GCP.
    * Deploy the Flask web server on GCP Compute Engine.
    * Configure GCP Buckets and GCP Load Balancer for optimal performance and reliability.

## Usage
1. Access the Web Interface:
    Open a web browser and navigate to the deployed URL.
2. Control Devices:
    * Use the web interface to send commands to the home automation devices.
    * Commands will be processed and executed in real-time, with the state of the devices reflected in the web interface.

