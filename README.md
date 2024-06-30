
# Book Recommender System

This repository contains a Flask web application that provides book recommendations based on collaborative filtering and popularity-based methods.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model and Data](#model-and-data)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Book Recommender System app allows users to get personalized book recommendations. The recommendations are generated using collaborative filtering and popularity-based methods.

## Features

- Personalized book recommendations based on user preferences.
- Popularity-based recommendations for users without historical data.
- User-friendly interface built with Flask.

## Installation

To run this application locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/book-recommender-system.git
   cd book-recommender-system
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv env
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```bash
     .\env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```

4. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Flask app:**
   ```bash
   python app.py
   ```

## Usage

After running the app, open your web browser and go to `http://localhost:5000`. You will see the Flask interface where you can input your preferences and get book recommendations.

## Model and Data

- The app uses collaborative filtering to provide personalized recommendations based on user interactions.
- Popularity-based recommendations are generated based on the most popular books in the dataset.
- The model and dataset are loaded from appropriate files.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.
