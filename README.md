#Weather Webpage
##Overview
This project is a simple weather webpage that displays the current temperature, humidity, and wind speed for a specific city. It is built using HTML, CSS, and JavaScript. The data is fetched from an external weather API, and the webpage dynamically updates to show the latest weather information based on the city entered by the user.

##Features
Real-time Weather Data: The webpage fetches real-time weather data for the specified city, including temperature, humidity, and wind speed.
Responsive Design: The webpage is designed to be responsive and works well on both desktop and mobile devices.
User Input: Users can input the name of the city for which they want to check the weather.
Dynamic Content: The weather information updates automatically when a new city is entered

##Technologies Used
HTML: Used for structuring the webpage.
CSS: Used for styling the webpage, making it visually appealing and responsive.
JavaScript: Used for fetching data from the weather API and updating the webpage content dynamically.

##How It Works
User Input:
The webpage contains an input field where the user can enter the name of a city.

Fetching Weather Data:
When the user submits the city name, a JavaScript function is triggered that sends a request to a weather API (e.g., OpenWeatherMap API).
The API returns a JSON response containing the weather data for the specified city.

Displaying Weather Data:
The JavaScript code processes the JSON response and extracts the relevant data, including temperature, humidity, and wind speed.
The extracted data is then displayed on the webpage, replacing the placeholder content.

Error Handling:
The webpage includes error handling to manage cases where the city name is incorrect or if the API request fails. Appropriate error messages are displayed to the user.

##Setup and Installation
1.Clone the repository to your local machine using:
git clone [https://github.com/yourusername/weather-webpage.git](https://github.com/sanketshinde2005/WeatherPage)
2.Open the index.html file in your preferred web browser to view the webpage.

## Webpage Screenshots
![Screenshot 2024-08-25 170731](https://github.com/user-attachments/assets/1a5dba8a-9d2e-423f-b5e6-9ccfdb4333ec)
![Screenshot 2024-08-25 170751](https://github.com/user-attachments/assets/c833767c-be56-4d26-8aaa-154189e850a7)

##Future Enhancements
Add More Weather Metrics: Display additional weather information such as forecast, sunrise/sunset times, etc.
Geolocation: Automatically detect the user's location and display the weather for their current city.
Improved UI/UX: Enhance the user interface with animations, better styling, and more interactive elements.

##My Work
http://liveweather-beta.vercel.app
