# Hospital Pose Detection

## Overview

Hospital Pose Detection is an advanced AI-powered system designed to detect and analyze human poses in a hospital setting. It leverages state-of-the-art machine learning models to assist healthcare professionals in monitoring patient movements, ensuring safety, and improving the overall quality of care. This project provides an easy-to-use interface for setting up and using the pose detection system.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Features

- **Real-time Pose Detection:** Monitors patient movements in real-time using live camera feeds.
- **Activity Recognition:** Identifies specific activities (e.g., sitting, standing, lying down) to help in patient care.
- **Alert System:** Sends alerts for abnormal activities or movements that may indicate a fall or other emergency.
- **Data Privacy:** Ensures that all patient data is handled in compliance with HIPAA and other relevant regulations.
- **Integration Friendly:** Easy integration with existing hospital management systems and electronic health records (EHR).

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Virtual environment tools (optional but recommended)

### Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/SrijanSadhu/pose-detection.git
    cd pose-detection
    ```

2. **Create a Virtual Environment (optional)**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**
    ```bash
    pip install opencv-python
    pip install mediapipe
    pip install numpy
    ```

## Usage

### Running the Application

After installation, you can run the application from:

```bash
cd hospital.ipynb
```
This will start the pose detection system and begin processing video feeds according to the configuration.


## Contributing

We welcome contributions to improve the Hospital Pose Detection system. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

Thank you for using Hospital Pose Detection! Your contributions and feedback are valuable to us.
