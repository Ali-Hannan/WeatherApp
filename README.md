Overview

This is a full-stack weather application built using React for the frontend and Node.js/Express for the backend. It fetches real-time weather data from the OpenWeatherMap API while securely handling API requests via the backend. The app allows users to search for any city and view current weather, temperature, humidity, wind speed, and more, all within a responsive and user-friendly interface.

Features:

  1. 🔍 City-based weather search

  2. ☁️ Live weather data using OpenWeatherMap API

  3. 🔐 API key hidden securely via backend (.env)

  4. 🌡 Temperature, humidity, wind speed, and weather icons

  5. 📱 Fully responsive design (mobile + desktop)

  6. 💬 Error handling and loading states

  7. 🌍 Built with Vite for fast frontend development

Tech Stack:

| Frontend   | Backend | Other |
Frontend	Backend	Other
React  	Node.js	Vite
HTML/CSS   	Express	Axios
JavaScript	dotenv	CORS


Getting Started
📁 Clone the repository:

git clone https://github.com/Ali-Hannan/WeatherApp.git

cd weather-app

1. Backend Setup (Express)
  - Go to the server directory:
      		 cd server

  - Install dependencies:
        		npm install

    - Create a .env file and add your OpenWeatherMap API key:
       		 WEATHER_API_KEY=your_openweather_api_key

    - Start the backend:
       		 node index.js

2. Frontend Setup (React)

-	Open a new terminal and go to the React project:
        		 cd client  # or root if frontend is in same dir

   	 - Install dependencies:
        		npm install

    	- Start the React app:
      		 npm run dev



Usage: 
-	Type any city into the search bar
-	Press Enter or click the search icon
-	Weather data for the city will appear
-	API requests are securely handled via backend

Future Enhancements

•	🌐 Geolocation-based weather

•	⭐ Save favorite cities

•	👤 User login & history

•	🌗 Light/Dark mode toggle

•	📲 Deploy as Progressive Web App (PWA)


Author:

Built by Ali Hannan

linkdIn: Ali Hannan Muhammad Nasim | Github: Ali-Hannan



