# Digital Anthropometry Calculation
This repository contains the code for digital anthropometry calculations using image processing techniques. The calculations are used to detect abnormalities in infants by measuring various body parameters from images.

# Overview
Model Architecture: U-Net

Metric: Mean IoU

This is the result of taking the dataset and U-Net architecture in the ipynb file above
The result can use in https://github.com/juaaju/Capstone
To use https://github.com/juaaju/Capstone you can do steps below

# Digital Anthropometry Calculation

This repository contains the code for digital anthropometry calculations using image processing techniques. The calculations are used to detect abnormalities in infants by measuring various body parameters from images.

## Overview

- **Model Architecture:** U-Net
- **Calculation Method:** Ellipse fitting
- **Parameters Calculated:**
  - Head circumference
  - Arm circumference
  - Abdomen circumference
  - Thigh circumference
  - Chest circumference
  - Body length

## Results

The results of these calculations are used to detect abnormalities in infants, providing a valuable tool for early diagnosis and intervention.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/digital-anthropometry.git
    cd digital-anthropometry
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the project, execute the `main.py` file:

```bash
python main.py
