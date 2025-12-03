# Parkinson's Disease Detection

A machine learning project for detecting Parkinson's disease using spiral and wave drawing patterns.

## Setup

1. **Create virtual environment** (if not already created):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On macOS/Linux
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Verify configuration**:
   ```bash
   python config.py
   ```

## Usage

1. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook model.ipynb
   ```

3. In your notebook, import the configuration:
   ```python
   from config import *
   create_directories()
   verify_dataset()
   ```

## Dataset

This project uses the "Parkinson's Disease Detection Using Spiral Images (Hand Drawings)" dataset from Mendeley Data.

**Citation**: Medasani, Shiva (2023), "Parkinson's Disease Detection Using Spiral Images (Hand Drawings)", Mendeley Data, V1, doi: 10.17632/fd5wd6wmdj.1

### Download Instructions

1. Visit the dataset page: https://data.mendeley.com/datasets/fd5wd6wmdj/1
2. Download the dataset files
3. Extract the contents into the project root directory
4. Ensure the following structure:
   ```
   dataset/
   ├── spiral/
   │   ├── healthy/
   │   └── parkinson/
   └── wave/
       ├── healthy/
       └── parkinson/
   ```

The dataset contains two types of drawing patterns:
- **Spiral drawings**: Located in `dataset/spiral/`
- **Wave drawings**: Located in `dataset/wave/`

Each category contains subdirectories for healthy and Parkinson's samples.

## Requirements

See `requirements.txt` for the complete list of dependencies.

## Dataset Citation

Medasani, Shiva (2023), "Parkinson's Disease Detection Using Spiral Images (Hand Drawings)", Mendeley Data, V1, doi: 10.17632/fd5wd6wmdj.1
