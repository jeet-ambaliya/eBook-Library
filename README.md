# eBook Library

Welcome to the eBook Library project! This application allows users to manage their eBook collections, providing functionalities to add, view, and manage eBooks in a user-friendly interface.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add new eBooks to the library
- View the list of eBooks
- Search for eBooks by title or author
- Delete eBooks from the library

## Installation

To get started with the eBook Library project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eBook-Library.git
   cd eBook-Library
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the application, use the following command:
```bash
python MainGateway.py
```

## Project Structure

The project directory contains the following files:

- `MainGateway.py`: The main entry point for the application.
- `MockDB.py`: Mock database implementation for testing purposes.
- `connection.py`: Handles database connections.
- `controller.py`: Contains the main logic for handling eBook operations.
- `testDB.py`: Unit tests for the database functionalities.
- `testing.py`: Additional tests for the application.
- `utils.py`: Utility functions used across the project.
- `.idea/`: Contains IDE-specific settings (can be ignored).

## Contributing

We welcome contributions to the eBook Library project! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your commit message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request and describe your changes.
