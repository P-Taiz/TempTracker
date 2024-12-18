# Weather Application

## Overview
This Weather Application is a simple Android app that provides real-time weather updates. Users can view the current weather of their location or search for the weather in a specific city by entering the city name. The app integrates the OpenWeatherMap API to fetch weather data and displays information such as temperature, weather conditions, and city name.

---

## Features
- **Real-Time Weather:** Get the current weather based on your GPS location.
- **City Search:** Search for weather updates in any city.
- **User-Friendly Interface:** Simple and intuitive design for easy navigation.

---

## Technical Details
- **Languages:** Java
- **API Used:** OpenWeatherMap API
- **Permissions Required:**
  - `INTERNET` for fetching data.
  - `ACCESS_FINE_LOCATION` for GPS-based location updates.
- **Libraries Used:**
  - `AsyncHttpClient` for network requests.
  - JSON handling for API response parsing.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Open the project in Android Studio.
3. Add your OpenWeatherMap API key to the `APP_ID` field in `MainActivity.java`.
4. Build and run the app on an emulator or device.

---

## How to Use
1. **Get Weather by Location:**
   - Allow location access when prompted.
   - View the current weather on the main screen.
2. **Search by City:**
   - Click on the search icon.
   - Enter the city name and press enter.
   - The app will display the weather for the specified city.

---

## Future Enhancements
- Offline mode with cached weather data.
- Enhanced UI design.
- Support for multiple languages.

---

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for enhancements or bug fixes.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
