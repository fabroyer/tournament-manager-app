# Chess Tournament Manager

## Overview

Python application designed to manage chess tournaments from the command line.
The application allows users to create and manage tournaments, register players, generate rounds, record match results and display tournament rankings.
The project was developed using Object-Oriented Programming principles and follows the Model-View-Controller (MVC) design pattern.

The project was completed as part of the OpenClassrooms Python Developer program.

## Installation

### Clone the Repository

- `git clone https://github.com/fabroyer/tournament-manager-app.git`
- `cd tournament-manager-app`

### Create and Activate Virtual Environment

Windows:
```bash
python -m venv env
env\Scripts\activate
```

Mac/Linux:
```bash
python -m venv env
source env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage

### Run App

```bash
python main.py
```

## Flake8 Report

Run Flake8 to check PEP 8 compliance:
```bash
flake8
```

HTML report:
```bash
flake8 --format=html --htmldir=flake-report
```

To view the report, open the generated `index.html` file in your web browser.

## Application Overview

Tournament Manager is a Python application designed to organize and manage chess tournaments from the command line.
Users can register players, create tournaments, and manage the complete lifecycle of a four-round competition.

For each tournament, eight players are selected. Match pairings are automatically generated according to the Swiss-system tournament format.
After each round, users record match outcomes, allowing the application to update standings and generate the next round's pairings.

The application also enables users to view player information, tournament details, round results, and tournament rankings.
All data is stored locally and can be accessed throughout the application's lifecycle.
