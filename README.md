
# Hospital Information Web Application

This project is a simple Flask web application that displays information about hospitals. The data is sourced from a dataset that includes various details about hospitals, such as their name, address, and services provided.

## Installation

To run this project, you need to have Python and the necessary packages installed. You can install the required packages using the following commands:

```bash
pip install pandas
pip install -U Flask
```

## Usage

1. **Run the Flask Application**:
    - To start the Flask web application, execute the following command in your terminal or command prompt:
    ```bash
    python -m flask run
    ```
    - By default, the application will run on `http://localhost:7300`.

2. **Access the Application**:
    - Open your web browser and navigate to `http://localhost:7300` to view the hospital information.
    - Navigate to `/Data` to see the formatted data table.
    - Navigate to `/about` to see additional information about the dataset and the variables included.

## Project Structure

- `app.py`: Main script to run the Flask application.
- `templates/`: Directory containing HTML templates used by Flask.

## Data Source

The hospital information is sourced from a dataset available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/cms/hospital-general-information).


