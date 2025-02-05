# Simple Calculator

A basic Python calculator that supports addition and subtraction. Implemented using Python, tested with **pytest**, and follows coding standards with **pylint**. The project is managed in a **virtual environment**.

## Features
- Addition
- Subtraction
- Unit tests using pytest
- Code quality check with pylint
- Virtual environment setup

## Installation & Setup

1. **Create and activate a virtual environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. **Install dependencies**:
   ```sh
   pip install pytest pylint
   ```

## Usage

1. Run the calculator script:
   ```sh
   python calculator.py
   ```

2. Run tests:
   ```sh
   pytest test_calculator.py
   ```

3. Check code quality:
   ```sh
   pylint calculator.py
   ```

## Files
- `calculator.py` - Contains the add and subtract functions.
- `test_calculator.py` - Unit tests for the calculator.
- `requirements.txt` - List of dependencies.
- `.pylintrc` - Pylint configuration file.

This project is done as a part of the Course IS601 taken at NJIT under Professor K. Williams.


