# Quizzler Trivia App

This Trivia app is a simple Python quiz application that fetches questions from the Open Trivia Database API and allows users to answer true/false questions interactively through a graphical user interface (GUI).

## Features

- Retrieves questions from the Open Trivia Database API.
- Presents questions one at a time.
- Allows users to answer with "True" or "False."
- Provides immediate feedback on the correctness of the answer.
- Displays the user's score as they progress through the quiz.
- Ends the quiz when all questions have been answered.

## Prerequisites

Before running the Quizzler app, make sure you have the following dependencies installed:

- Python 3.x
- Tkinter (usually included with Python)
- requests (for making API requests)

You can install the `requests` library using pip:

```
pip install requests
```

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/quizzler.git
```

2. Navigate to the project directory:

```
cd quizzler
```

## Usage

To start the Quizzler app, run `main.py`:

```
python main.py
```

The application window will open, and you can begin answering questions. Click the "True" or "False" buttons to submit your answers.

<img src="https://github.com/amansinghgill/Trivia-App/assets/90486946/1aa2b682-22ca-47a0-9cf6-6693d27b0ea7" alt="UI" width="150px" style="margin: 0 auto; display: block;">

## Customization

If you want to customize the number of questions or question type (e.g., multiple-choice), you can modify the parameters in the `data.py` file:

```python
parameters = {
    "amount": 10,      # Change the number of questions here
    "type": "boolean", # Change to "multiple" for multiple-choice questions
}
```

## Acknowledgments

- Questions are fetched from the [Open Trivia Database](https://opentdb.com/).

