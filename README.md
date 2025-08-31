# Weather API Project

This is a practical project to create a localhost API for accessing weather data using Python, Flask, and pandas. The API serves temperature data from local CSV files.

## Demo

![Weather Data API Demo](images/demo.png)

## Features

- Simple REST API for querying daily temperature by station and date
- Data served from local files
- Easy to run and extend

## Dataset

The dataset is sourced from the [European Climate Assessment and Dataset (ECAD)](https://www.ecad.eu/).

## Getting Started

1. Clone the repository.
2. Install dependencies:
   ```
   pip install flask pandas
   ```
3. Run the API server:
  ```
  python main.py
  ```
4. Access the API at `http://127.0.0.1:5000/api/v1/<station>/<date>`

## Example
```
GET /api/v1/10/1998-10-25
```
Returns the temperature for station 10 on 1998-10-25.

## Future Improvements

- **Deployment:** Host the API on platforms like Heroku, Vercel, or AWS so others can access it online.
- **Web Interface:** Add a frontend for easier data browsing and visualization.
- **Authentication:** Implement user authentication for secure access.
- **Extended Data:** Support more weather parameters and larger datasets.
- **Documentation:** Add OpenAPI/Swagger docs for better API usability.

## License

This project is for educational purposes.

