# Autoimmune Skin Disease Detection Model

## Project Description
This project implements a deep learning model for detecting autoimmune skin diseases using **Convolutional Neural Networks (CNNs)**, leveraging the **ResNet architecture**. The model has been fine-tuned and tested on both **ResNet-9** and **ResNet-34**, achieving high accuracy and recall.

A user-friendly web interface, powered by **Gradio**, allows users to upload skin images and get real-time predictions. Additionally, the interface includes a trained chatbot for interactive user support, providing helpful information about skin diseases.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Features](#features)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Gradio app:**
    ```bash
    python app.py
    ```

## Usage

Once the Gradio interface is up and running, you can:

1. **Upload Skin Images**: Use the interface to upload an image of the skin.
2. **Model Prediction**: The model will predict whether the image indicates one of six autoimmune skin conditions.
3. **Confidence Score**: The result will include a prediction label along with a confidence score.
4. **Chatbot Interaction**: You can interact with a trained chatbot to ask questions and receive information about skin conditions.

## Model Architecture
- The model is based on **ResNet (Residual Networks)** for image classification.
- It was fine-tuned and tested using **ResNet-9** and **ResNet-34** architectures, both delivering strong performance in terms of accuracy and recall.
- The training dataset consists of labeled skin images for six types of autoimmune diseases.
- The model helps classify these diseases with high precision, assisting medical professionals in early detection.

## Features

- **Image Upload**: Upload an image of the skin for instant classification.
- **Prediction**: The model will classify the uploaded image into one of six autoimmune disease labels and provide a confidence score.
- **Chatbot**: The interface includes a trained chatbot that answers user queries related to autoimmune skin diseases.
- **Web Interface**: Simple and intuitive **Gradio** interface for both medical professionals and non-technical users.
- **Real-Time Inference**: Instantaneous predictions from the model.

## Demo
Here’s a sample output from the project:
<img width="664" alt="Screenshot 2024-09-12 at 7 45 52 PM" src="https://github.com/user-attachments/assets/e970b05c-ad98-46a9-aee5-cece8528fd51">

<img width="957" alt="Screenshot 2024-09-12 at 7 46 10 PM" src="https://github.com/user-attachments/assets/853a4e9c-8fd2-4f71-bb48-9de5dc893f1f">

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Added feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
