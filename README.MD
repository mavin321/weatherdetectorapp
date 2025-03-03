# Weather Detector App

## Overview
The **Weather Detector App** is a Django-based web application that provides real-time weather information using the OpenWeather API. Users can enter a city name to retrieve the current temperature, weather conditions, humidity, and other relevant details.

## Features
- Fetch real-time weather data using OpenWeather API
- User-friendly interface for searching city weather
- Displays temperature, humidity, wind speed, and weather conditions
- Error handling for invalid city names

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **API**: OpenWeather API
- **Database**: SQLite (or any other Django-supported database)

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Django
- Requests (for API calls)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/mavin321/weatherdetectorapp.git
   cd weather-detector
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables:
   - Create a `.env` file in the project root and add your OpenWeather API key:
     ```
     OPENWEATHER_API_KEY=your_api_key_here
     ```
5. Run database migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```
7. Open the application in your browser:
   ```
   http://127.0.0.1:8000/
   ```

## Usage
1. Enter a city name in the search bar.
2. Click the "Search" button.
3. View the real-time weather details.

## Configuration
- **API Key:** Obtain an API key from [OpenWeather](https://openweathermap.org/) and update the `.env` file.
- **Database:** By default, SQLite is used. You can change it in `settings.py` to use PostgreSQL, MySQL, etc.

## Future Enhancements
- Implement user authentication for personalized weather tracking
- Add a feature to display weather forecasts for upcoming days
- Improve UI with interactive maps and graphical weather representations

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is licensed under the MIT License.

## Contact
For inquiries or support, reach out at **mavinpeteromondi@gmail.com**.

