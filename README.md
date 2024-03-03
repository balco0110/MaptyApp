# MaptyApp- Workout Tracker

This JavaScript application allows users to track their workouts, including running and cycling exercises. Users can input details such as distance, duration, cadence (for running), and elevation gain (for cycling). The application visualizes workouts on an interactive map and provides a list view of the workouts with detailed information.

## Features

- Create new running or cycling workouts.
- Input workout details such as distance, duration, cadence, and elevation gain.
- Visualize workouts on an interactive map.
- View detailed workout information in a list format.
- Toggle elevation and cadence fields based on workout type selection.
- Click on a workout in the list to navigate to its location on the map.
- Store workout data locally to persist across sessions.

## How to Use

1. Open the `index.html` file in your web browser.
2. Allow the application to access your location for accurate workout tracking.
3. Fill out the workout form with the required details:
   - Select the workout type (running or cycling).
   - Enter the distance covered in kilometers.
   - Enter the duration of the workout in minutes.
   - For running workouts, enter the cadence (steps per minute).
   - For cycling workouts, enter the elevation gain in meters.
4. Submit the form to add the workout to the map and list.
5. Click on a workout in the list to see its location on the map.

## Code Explanation

- The application utilizes classes and inheritance to create workout objects for running and cycling.
- It uses Leaflet.js library for interactive mapping and visualization of workouts.
- Event listeners are implemented to handle user interactions such as form submission and workout selection.
- Local storage is used to persist workout data between sessions.
- Methods are provided to calculate pace (for running) and speed (for cycling) based on workout duration and distance.

