# AI/ML Docker Project

A professional Docker environment for AI and Machine Learning development with Python.

## Quick Start
```bash

# Create directories
mkdir -p src data models notebooks # For linux/Macos
mkdir src, data, models, notebooks # For win powershell
# Build the container
docker-compose build

# Run the application
docker-compose up ai-app
```

## Project Structure
```
.
├── Dockerfile           # Container configuration
├── docker-compose.yml   # Services setup
├── requirements.txt     # Python dependencies
├── main.py             # Demo script
├── src/                # Source code
├── data/               # Datasets
├── models/             # Saved models
└── notebooks/          # Jupyter notebooks
```
