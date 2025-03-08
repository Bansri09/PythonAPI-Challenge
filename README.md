# Python API Challenge

## Exploring Weather Data and Vacation Planning

In this project, I applied my skills in Python requests, APIs, and JSON traversals to explore weather data across different cities and plan future vacations.

## Background

Data's true power is its ability to definitively answer questions. So, let's take what I've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: *"What is the weather like as we approach the equator?"*

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would we prove that?

## Project Overview

This project is broken down into two main deliverables: WeatherPy and VacationPy.

### Part 1: WeatherPy

In this part, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. Using the citipy Python library, the OpenWeatherMap API, and my problem-solving skills, I developed a representative model of weather across cities.

#### Requirements:

1. **Create Plots to Showcase the Relationship Between Weather Variables and Latitude:**
   - Latitude vs. Temperature
   - Latitude vs. Humidity
   - Latitude vs. Cloudiness
   - Latitude vs. Wind Speed

2. **Compute Linear Regression for Each Relationship:**

![linear-regression-plot](https://github.com/user-attachments/assets/d12c99e2-9638-4b8f-9530-d2b251bba58e)

   - Northern Hemisphere: Temperature vs. Latitude
   - Southern Hemisphere: Temperature vs. Latitude
   - Northern Hemisphere: Humidity vs. Latitude
   - Southern Hemisphere: Humidity vs. Latitude
   - Northern Hemisphere: Cloudiness vs. Latitude
   - Southern Hemisphere: Cloudiness vs. Latitude
   - Northern Hemisphere: Wind Speed vs. Latitude
   - Southern Hemisphere: Wind Speed vs. Latitude

5. **Analysis:**
   - Explained the linear regression models and described any relationships or findings.

### Part 2: VacationPy

In this part, I used my weather data skills to plan future vacations. By leveraging Jupyter notebooks, the geoViews Python library, and the Geoapify API, I created map visualizations for an ideal vacation destination.

#### Requirements:

1. **Create a Humidity Map:**
   - Displayed a point for every city in the dataset, with the size of the point representing the humidity.
    ![humidity_map](https://github.com/user-attachments/assets/2138cc87-40d7-49a3-be65-41e1c5fa262d)

2. **Find Ideal Weather Conditions:**
   - Filtered cities based on ideal weather conditions (e.g., max temperature, wind speed, cloudiness).

3. **Locate Hotels:**
   - Used the Geoapify API to find the first hotel located within 10,000 meters of the city coordinates.
   - Displayed hotel information on the map.
![hotel_map](https://github.com/user-attachments/assets/bac89c89-462b-40bd-b923-19bc3aa8a98c)

## Instructions

### Before You Begin

- Created a new repository called `python-api-challenge`.
- Added a `.gitignore` file to prevent the `api_keys.py` file from being shared with the public.
```bash
    # Adding config.py file.
    api_keys.py
    ```

## Additional Information

- The city data generated is based on random coordinates and query times, so outputs may vary.
- Took time to study the OpenWeatherMap API and understand the endpoints and JSON structure.
- Applied critical thinking skills to understand how and why tools like citipy and OpenWeatherMap API are recommended.

## Conclusion

This project provided valuable insights into weather patterns across different cities and helped plan ideal vacation destinations based on weather conditions. The visualizations and analyses offer a strong foundation for future data analytics projects.

---


