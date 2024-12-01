WEATHER APP (MERN Stack)


This project is a Weather Dashboard application built using the MERN stack. It integrates the OpenWeather API to fetch weather data based on user input and provides a clean, interactive interface to display results.


Features
- Fetch weather details for any city.
- Filter weather conditions by keywords (e.g., "clear").
- Error handling for invalid city names or API failures.


Project Structure
weather-dashboard/
  ├── frontend/         # React frontend
  ├── backend/          # Node.js backend
  ├── README.md         # Project instructions

  
Setup Instructions
Prerequisites
1. Install Node.js on your system.
2. Register for an OpenWeather API key at https://openweathermap.org/.

   
Frontend Setup
1. Navigate to the `frontend` folder:
   cd frontend
2. Install dependencies:
   npm install
3. Start the React application:
   npm start
   
Backend Setup
1. Navigate to the `backend` folder:
   cd backend
2. Install dependencies:
   npm install
3. Create a `.env` file in the `backend` folder and add your OpenWeather API key:
   OPENWEATHER_API_KEY=your_api_key
4. Start the backend server:
   node index.js

   
How to Run the Application
1. Start the backend server:
   cd backend
   node index.js
2. Start the frontend application:
   cd frontend
   npm start
3. Open your browser and navigate to http://localhost:3000.
4. Enter a city name to fetch and view weather details.

   
Example Usage
1. Open the application.
2. Enter a city name, such as New York, and click "Get Weather."
3. View the temperature, humidity, and weather description.

