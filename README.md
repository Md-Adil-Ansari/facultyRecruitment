# facultyRecruitment
# Project Setup Guide

## Demo video
[faculty recruitment video](https://youtu.be/wbG52UKsss0?si=noDomeHN2SJrcjiy)

Follow these steps to set up and run your project:

## Backend Setup

1. Open the terminal and navigate to the `backend` folder:
   ```bash
   cd backend
2. Install dependencies:
   ```bash
   npm install
3. Create a .env file inside the backend folder and add the following configurations:

PORT=8000

DB_PASSWORD=<mongodb_connection_string>

CORS_ORIGIN=*

ACCESS_TOKEN_SECRET=lajoirijt

ACCESS_TOKEN_EXPIRY=1d

REFRESH_TOKEN_SECRET=kjokkqAAA

REFRESH_TOKEN_EXPIRY=10d

MAIL_ID=<your_gmail_address_for_sending_emails>

MAIL_PASSWORD=<gmail_app_password>

CLOUDINARY_CLOUD_NAME=<cloudinary_cloud_name>

CLOUDINARY_API_KEY=<cloudinary_api_key>

CLOUDINARY_API_SECRET=<cloudinary_api_secret>

## Frontend Setup
1. Open another terminal and navigate to the `frontend` folder:
   ```bash
   cd frontend
2. Install dependencies:
   ```bash
   npm install

## Running Docker
1. Ensure Docker is installed on your system.
2. In the terminal, navigate to the root folder containing your docker-compose.yml file.
3. Run the following command to start Docker containers:
    ```bash
    docker compose up

## Accessing the Application
Once Docker containers are up and running, open your web browser and go to:
http://localhost:5173/

## Additional Notes
1. Make sure to replace placeholders like <mongodb_connection_string>, <your_gmail_address_for_sending_emails>, <gmail_app_password>, <cloudinary_cloud_name>, <cloudinary_api_key>, and <cloudinary_api_secret> with your actual values.

2. The specified ports (8000 for backend and 5173 for frontend) and other configurations can be adjusted based on your project requirements.




