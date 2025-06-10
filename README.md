# React Weather App

A simple and responsive weather application built with **React** that fetches and displays current weather data for any city using the [GoWeather API](https://goweather.herokuapp.com/).

## Features
- City search with dynamic input
- Real-time data fetching using Axios
- Input validation and error handling
- Weather data display: temperature, wind, and description
- Loading state


## Walkthrough
- Search Input
    User enters the name of a city in the input field.
    Pressing **Enter** triggers the fetch process.
- Data Fetching
    The app sends a GET request to the GoWeather API.
    Displays a loading message while waiting for the response.
- Display Result
    If successful, the weather details are displayed:
        - Temperature
        - Wind
        - Description
- Error Handling
    If no city is entered or the city has no valid data, a descriptive error message is shown.


## What I Learned
- Using `useEffect` and `useState` to manage component lifecycle and state.
- Making API calls with Axios and integrating them into a responsive React UI.
- Handling different application states: loading, error, and success.
- Creating a clean user experience with TailwindCSS and accessibility in mind.

## Challenges Faced
- Ensuring accurate error handling when API returns incomplete or empty data.
- Preventing empty or whitespace-only searches from triggering API calls.
- Managing controlled inputs to avoid unnecessary re-renders (Only search when enter is pressed).
