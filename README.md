


# Weather App 🌦️

A simple and responsive Weather Application built with **Java**, **HTML**, **CSS**, and **Spring Boot**.  
It fetches real-time weather data from an API and displays it in a user-friendly interface.  

## 🚀 Features
- 🌍 **Search weather by city name**
- 📅 **Displays current date & time**
- 🌡️ **Shows temperature, humidity, and weather conditions**
- 📱 **Responsive UI**
- ☁ **Real-time weather data fetched from API**
- 🐳 **Dockerized for easy deployment**

## 🛠️ Tech Stack
- **Java** (Spring Boot)
- **HTML, CSS**
- **Docker**
- **Weather API** (e.g., OpenWeatherMap)

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
````

### 2️⃣ Configure API Key

1. Get your API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Add it to your application properties file:

```properties
weather.api.key=YOUR_API_KEY
```

### 3️⃣ Run with Maven

```bash
mvn spring-boot:run
```

### 4️⃣ Run with Docker

```bash
docker build -t weather-app .
docker run -p 8080:8080 weather-app
```

## 📷 Screenshots

>> Home Page
<img width="1919" height="604" alt="Screenshot 2025-08-12 170303" src="https://github.com/user-attachments/assets/fcd7fa7a-57e7-4ddf-b3f3-620698e31592" />

>> Weather Forcast Page
<img width="1919" height="732" alt="Screenshot 2025-08-12 170321" src="https://github.com/user-attachments/assets/cae875b7-c68c-4444-b241-eff3470f8ed7" />



## 📂 Project Structure

```bash
Weather-App/
│── .idea/                     # IntelliJ project settings
│── .mvn/                      # Maven wrapper files
│── .vscode/                   # VSCode settings
│── out/                       # Build output
│   └── artifacts/weather\_app\_jar/weather-app.jar
│── src/
│   ├── main/
│   │   ├── java/com/example/weather\_app/
│   │   │   ├── Controller/
│   │   │   │   └── WeatherController.java
│   │   │   ├── Model/
│   │   │   │   └── WeatherResponse.java
│   │   │   └── WeatherAppApplication.java
│   │   ├── resources/
│   │   │   ├── META-INF/
│   │   │   ├── static/
│   │   │   │   ├── css/
│   │   │   │   │   ├── index.css
│   │   │   │   │   └── weather.css
│   │   │   │   ├── images/
│   │   │   │   │   └── image.png
│   │   │   ├── templates/
│   │   │   │   ├── index.html
│   │   │   │   └── weather.html
│   │   │   └── application.properties
│   ├── test/java/com/example/weather\_app/
│   │   └── WeatherAppApplicationTests.java
│── Dockerfile
│── pom.xml
│── README.md
```

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create a new branch
* Make your changes
* Submit a pull request

---
## NOTE

Made with LOVE and DEDICATION

## Running LINK

[Weather ](https://weather-application-opzx.onrender.com)
