# Python Project Setup

This repository contains a Python project. Follow the instructions below to set up your development environment.

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create and activate a virtual environment:
```bash
# Create virtual environment
python3 -m venv .venv

# Activate virtual environment
# On macOS/Linux:
source .venv/bin/activate
# On Windows:
# .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip3 install -r requirements.txt
```

## Development

- Make sure your virtual environment is activated before running the project
- The `.venv` directory is gitignored and should not be committed
- Python cache files (`__pycache__`, `.pyc`, etc.) are also gitignored

## Project Structure

```
.
├── .venv/               # Virtual environment (gitignored)
├── requirements.txt     # Project dependencies
└── README.md           # This file
```

## Additional Notes

- Always activate the virtual environment before working on the project
- To deactivate the virtual environment, simply type `deactivate` in the terminal
- If you add new dependencies, update requirements.txt:
```bash
pip freeze > requirements.txt
``` 