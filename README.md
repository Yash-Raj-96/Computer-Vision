# Computer Vision

This repository contains a Python-based application that uses computer vision techniques to control system functionalities through hand gestures.

### Key Components
1. **Live Mouse Control** - Control the mouse cursor with hand gestures.
2. **Volume and Brightness Control** - Adjust system volume and screen brightness using hand gestures.
3. **Docker & Kubernetes** - Supports Docker for containerization and Kubernetes for deployment.

## Requirements
- Python 3.x
- OpenCV
- Mediapipe
- Docker

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Yash-Raj-96/Computer-Vision.git
    cd Computer-Vision
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python app.py
    ```

## Build and Run the Docker Container

1. Build the Docker image:
    ```bash
    docker build -t computer-vision-app .
    ```

2. Run the Docker container:
    ```bash
    docker run -d -p 5000:5000 computer-vision-app
    ```

## Apply Kubernetes Configurations

1. Apply the Kubernetes deployment configuration:
    ```bash
    kubectl apply -f k8s/deployment.yaml
    ```

2. Apply the Kubernetes service configuration:
    ```bash
    kubectl apply -f k8s/service.yaml
    ```

