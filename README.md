# Focus-Blocks
Overview

Focus Blocks is a web/app platform designed to help users maximize productivity by managing their work into focused time blocks. It provides a user-friendly interface for dividing tasks into adjustable durations, offering reminders, timers, and customizable visuals to create a personalized and engaging workflow experience.

Features

Task Management

Create and Organize Tasks: Easily create tasks and organize them into time blocks.

Adjustable Durations: Modify task durations based on your preferences and needs.

Timers and Reminders

Integrated Timers: Start, pause, and track your progress with built-in timers.

Customizable Reminders: Set reminders to stay on track without disrupting your flow.

Visual Customization

Background Themes: Select from a variety of gifs, colors, and themes for a visually pleasing experience.

Dynamic Backgrounds: Match your background to your task for a cohesive and motivating environment.

Notifications

Get real-time notifications when your focus block ends or a reminder is triggered.

Technology Stack

Backend

Flask: The backend is powered by Flask, a high-performance web framework ideal for building modern APIs. FastAPI ensures quick response times and efficient data handling.

Frontend

Built using react to deliver a seamless user experience.

Database

Database management is done through SQL

Deployment

Cloud-Based Hosting: Deployed on a scalable cloud platform (e.g., AWS, Azure, or Google Cloud) to ensure high availability and reliability.

Installation and Setup

Clone the Repository:

git clone https://github.com/yourusername/focus-blocks.git

Navigate to the Project Directory:

cd focus-blocks

Install Dependencies:

Backend dependencies:

pip install -r backend/requirements.txt

Frontend dependencies:

cd frontend
npm install

Run the Application:

Start the backend server:

uvicorn backend.main:app --reload

Start the frontend:

npm start

