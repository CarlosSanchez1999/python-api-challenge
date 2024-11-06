# Global Weather and Hotel Analysis Project

## Description
This project analyzes weather data for cities worldwide to identify ideal weather conditions and locate nearby hotels. The motivation behind this project is to provide users with insights into cities that meet specific weather criteria and to help them find accommodation options within close proximity. The project uses Python, the OpenWeatherMap API, and the Geoapify API for data retrieval, filtering, and visualization. 

### Technologies Used:
- **Python**: For data processing and API requests.
- **Jupyter Notebook**: To organize and run analyses in structured notebooks.
- **OpenWeatherMap API**: For retrieving real-time weather data.
- **Geoapify API**: To locate nearby hotels for selected cities.
- **hvplot**: For interactive mapping and visualization.

### Challenges Overcome:
One major challenge was managing the lengthy data retrieval process in `WeatherPy`. To avoid re-running this time-consuming step, the project was split into two notebooks:
- `WeatherPy`: Responsible for data retrieval.
- `WeatherPy_Part_2`: Continues the analysis and visualization without requiring a re-run of the retrieval cells.

## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. **Install Required Packages**:
  pip install pandas hvplot requests
3. **Set-Up API-Keys**

## Usage
### Step 1: Run `WeatherPy` Notebook
### Step 2: Run `WeatherPy_Part_2` Notebook
### Step 3: Run `Vacation.py`

## Credits
- **Carlos Fernando Sánchez Lozano** - Project creator and developer.
### Third-Party APIs
- [OpenWeatherMap API](https://openweathermap.org/api) - Used for retrieving weather data for cities worldwide.
- [Geoapify Places API](https://www.geoapify.com/) - Used to find nearby hotels based on city coordinates.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as per the terms of the license.

See the [LICENSE](LICENSE) file for more details.

