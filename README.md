# Health-Centre-Distribution-Heatmap-
This GitHub repository contains Python code for generating a heatmap of health center distribution in Bhubaneswar, Odisha, India. The code processes health center data from a CSV file, performs spatial analysis using H3 hexagons, and visualizes the distribution on a map using Plotly Express and Geopandas

Key Features:

    Data Processing: The code reads health center data from a CSV file, selects relevant columns, and renames them for clarity.

    H3 Hexagon Grid: It generates a hexagon grid using H3 geospatial indexing, allowing you to customize the hexagon size and resolution.

    Spatial Analysis: The code calculates the number of health centers within each hexagon, providing insights into the distribution of health facilities in Bhubaneswar.

    Interactive Heatmap: Utilizing Plotly Express, the code creates an interactive choropleth map displaying health center distribution. Users can hover over hexagons to see the names of health centers.

Instructions:

To use the code, follow these steps:

    Prepare your health center data in a CSV file with columns for name, neighborhood, district, latitude, and longitude.

    Configure the code with the file path to your data and specify parameters like hexagon size and resolution.

    Run the code to generate an interactive heatmap of health center distribution in Bhubaneswar.

    Customize the map appearance, such as color scale and opacity, as needed.

    The resulting map visually represents health center distribution in different areas of Bhubaneswar.

