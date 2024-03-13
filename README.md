# sqlalchemy-challenge
# Hawaii Climate Analysis and API

## Overview
This project offers a Flask API for analyzing climate data in Hawaii. Whether you're planning a vacation or optimizing business operations, this API provides valuable insights into Hawaii's weather patterns. The analysis includes precipitation, temperature, and station information, enabling users to make informed decisions based on up-to-date data.

## Repository Structure
- `SurfsUp/`: Directory containing the Flask application and climate analysis scripts.
  - `climate_starter.ipynb`: Jupyter Notebook file for conducting climate analysis.
  - `app.py`: Flask application file providing API routes.
  - `Resources/`: Directory containing data files used for analysis.
- `README.md`: This file provides an overview of the project.



## Usage
- **Homepage**: Visit `/` to access the homepage and view available routes.
- **Precipitation Data**: Access `/api/v1.0/precipitation` to retrieve precipitation data for the last 12 months.
- **Station Information**: Retrieve station information by visiting `/api/v1.0/stations`.
- **Temperature Observations**: Get temperature observations for the previous year from the most active station at `/api/v1.0/tobs`.
- **Temperature Statistics**: Access temperature statistics for a specific start date (`/api/v1.0/<start>`) or start-end range (`/api/v1.0/<start>/<end>`).


