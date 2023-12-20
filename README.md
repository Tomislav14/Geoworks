# Bicycle Parking Locations - Visualization with Folium and Pandas

This project creates an interactive map displaying bicycle parking locations using Folium and Pandas in Python.

## Overview

The objective of this Python project is to:
- Plot bicycle parking locations from a CSV file onto an interactive map.
- Use Folium for map creation, layering, and marker placement.
- Employ Pandas to manage and extract information from the dataset.

## Dataset

The dataset used for this project is retrieved from 'Javna_parkiralista_za_bicikle.csv', containing various attributes related to bicycle parking locations.

### File Details:
- **File Name:** 'Javna_parkiralista_za_bicikle.csv'
- **Location:** 'E:/Javna_parkiralista_za_bicikle.csv'

## Usage

To run the project:
1. Ensure you have Python installed along with the required libraries: Pandas, Folium.
2. Download the dataset 'Javna_parkiralista_za_bicikle.csv' and place it in the specified location.
3. Run the 'main.py' script.

## Code Details

### Python Script:
- **File:** `main.py`
- **Actions:**
  - Reads the CSV file into a Pandas DataFrame.
  - Creates a map centered at the mean location coordinates.
  - Adds different tile layers to the map for varied map views.
  - Places markers on the map for each bicycle parking location, providing pop-up information for each marker.
  - Integrates Folium plugins like MousePosition, Draw, and MeasureControl for added functionality.

## Contributing

Contributions to this project are welcome! If you have any suggestions or improvements, feel free to fork the repository, make changes, and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
