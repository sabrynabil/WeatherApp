# 🌦️ Weather App with Authentication - Dockerized Microservices

This is a full-stack weather application built using a microservices architecture. The app allows users to **sign up or log in**, enter the name of a city, and **view real-time weather information** for that city.

All services are containerized using Docker and orchestrated with Docker Compose.

## 🧱 Project Structure

The application consists of three main services:

- **Authentication Service**
  - Handles user registration and login
  - Manages authentication 
- **Weather Service**
  - Fetches current weather data based on user input
  - Integrates with a public weather API (e.g., OpenWeatherMap)
- **UI Service**
  - Frontend interface for the app
  - Allows users to interact with authentication and weather features

Each service is containerized using Docker, and they are orchestrated with Docker Compose.

## 🐳 Technologies Used

- **Docker**: Containerization for each microservice
- **Docker Compose**: Service orchestration
- **Node.js/ Python**: 
- **MYSQL**: CREATED MTSQL DATABASE
- **OpenWeatherMap API**: For real-time weather information
- 
## 📦 Installation

### Prerequisites

- Docker installed on your system
- Docker Compose installed

### Steps to Run the Application

1. Clone the repository:

```bash
git clone https://github.com/sabrynabil/WeatherApp.git
cd WeatherApp
```

2. Build and start the application with Docker Compose:
```bash
docker-compose up --build
```

3. Open your browser and visit:
```bash
http://your-ip:3000  # Replace with the correct port if different
```

## 🖥️ How to Use

- Go to the app in your browser.
- Sign up with a new account or log in.
- Enter a city name into the input field.
- View the current weather information.

## 📁 Project Structure Example
```
├── auth-service/
│ └── Dockerfile
├── weather-service/
│ └── Dockerfile
├── ui-service/
│ └── Dockerfile
├── docker-compose.yml
└── README.md
```
## 🚀 Features

- 🔐 Secure user authentication
- 🌍 City-based weather search
- ⚙️ Microservice architecture
- 🐳 Fully dockerized deployment

## ✅ To-Do / Future Improvements

- Add persistent database support
- Add logout functionality
- Implement tests for each service
- Handle API errors more gracefully
