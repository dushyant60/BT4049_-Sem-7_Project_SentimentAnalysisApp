# Sentiment Analysis Web App

This project demonstrates a simple Sentiment Analysis web application built using Flask and NLTK's VADER.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Analyzes sentiment (positive/negative) of text input using NLTK's VADER sentiment analysis tool.
- Basic web interface to input text and view sentiment analysis results.

## Prerequisites

Ensure you have the following installed before running the app:

- Python (version 3.x)
- Pip (Python package installer)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/dushyant60/BT4049_-Sem-7_Project_SentimentAnalysisApp.git
    cd BT4049_-Sem-7_Project_SentimentAnalysisApp
    ```

2. Set up a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    # Activate the virtual environment
    # For Windows:
    venv\Scripts\activate
    # For MacOS / Linux:
    source venv/bin/activate
    ```

3. Install dependencies:

    ```bash
    pip install nltk flask
    ```

## Usage

1. Run the Flask app:

    ```bash
    python app.py
    ```

2. Open a web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the Sentiment Analysis web app.

3. Enter text in the input box and click "Analyze" to see the sentiment analysis results.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).
