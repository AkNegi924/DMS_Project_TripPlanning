Demo: https://www.youtube.com/watch?v=muAkncYRhTE

![Screenshot (619)](https://github.com/user-attachments/assets/5f7153de-9777-4b00-8159-754b5b0d0a86)

# Travel Recommender System and TSP Solver

This Python application utilizes Flask and various libraries to provide travel recommendations based on user preferences and generate the optimal path for a trip using the Traveling Salesman Problem (TSP) solver.

![Screenshot (620)](https://github.com/user-attachments/assets/f3f85c74-271d-4919-a71e-53508608d6ad)

## Execution Steps

### Prerequisites

Make sure you have the following installed:

- Python (3.x recommended)
- Required Python libraries (`pip install`):
  - Flask
  - NetworkX
  - Matplotlib
  - Pandas
  - Geopy
  - Folium
  - Requests
  - Wikipedia-API

![Screenshot (621)](https://github.com/user-attachments/assets/fd32f44b-7594-410f-a900-48ea1fb2b326)

### Execution

1. **Clone the repository or download the code files.**
2. **Install the required dependencies:**

   ```bash
   pip install flask networkx matplotlib pandas geopy folium requests wikipedia-api
   ```
3. **Run the application:**

   Navigate to the directory where the code is located and execute:

   ```bash
   python main.py
   ```

   main.py is the name of the Python file where your Flask application is defined.
4. **Access the application:**

   Open a web browser and go to `http://localhost:5000` to access the application.

![Screenshot (622)](https://github.com/user-attachments/assets/9b5df925-fb17-4b4d-9ee2-effeee6baac3)

## Usage

1. Visit the home page to initiate the travel recommendation process.
2. Enter your preferences (budget, weather, distance) and location.
3. Receive recommendations based on your preferences.
4. Choose cities and view the optimal path or explore them on the map.

## Files and Structure

- `main.py`: The main Flask application file.
- `destinations1.xlsx`: Excel file containing destination information.
- `templates`: Directory containing HTML templates for web pages.
- `static`: Directory for static files (CSS, images, etc.).

### Important Functions

- `getrec`: Retrieves recommended cities based on user preferences.
- `find_tsp`: Finds the optimal path using the TSP algorithm.
- `generate_tsp_graph`: Generates a visual representation of the optimal path using Matplotlib.
- `create_map`: Creates an interactive map with recommended cities using Folium.

![Screenshot (623)](https://github.com/user-attachments/assets/a3635423-c09f-4756-abca-9b5fdc36ec22)


## Notes

- The code utilizes destination data from an Excel file (`destinations1.xlsx`). Ensure the file is in the correct format and contains the necessary information.
- Modify or replace the `get_coordinates1` function to fetch actual coordinates or integrate with a live location service if needed.

## Acknowledgements

This application uses various Python libraries and APIs to provide travel recommendations and solve the TSP. Credits to their respective developers and communities for their contributions.
