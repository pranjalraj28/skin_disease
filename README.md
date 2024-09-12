Autoimmune Skin Disease Detection Model
Project Description
This project implements a deep learning model for detecting autoimmune skin diseases using CNN (Convolutional Neural Networks), leveraging the ResNet architecture. The model has been tested using ResNet-9 and ResNet-34, and it delivers high accuracy and recall. A user-friendly web interface, powered by Gradio, allows easy image upload and real-time inference, making it accessible even to non-technical users. Additionally, the interface includes a trained chatbot for interactive user support.

Table of Contents
Installation
Usage
Model Architecture
Features
Demo
Contributing
License
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Gradio app:
bash
Copy code
python app.py
Usage
Once the Gradio interface is up and running, you can:

Upload Skin Images: Use the interface to upload an image of the skin.
Model Prediction: The model will predict whether the image indicates one of six autoimmune skin conditions.
Confidence Score: The result will include a prediction label along with a confidence score.
Chatbot Interaction: Ask questions and receive information about skin conditions through the chatbot.
Model Architecture
The model uses ResNet (Residual Networks) for classification.
It was fine-tuned and tested on both ResNet-9 and ResNet-34 architectures, delivering strong performance metrics in terms of accuracy and recall.
The dataset consists of labeled skin images for six types of autoimmune diseases.
The model was trained to classify these six conditions with high precision, helping medical professionals with early detection.
Features
Image Upload: Upload an image for instant classification.
Prediction: The model classifies the image into one of six autoimmune skin disease labels and provides a confidence score.
Chatbot: The interface includes a trained chatbot for interactive support and answering user queries related to autoimmune skin diseases.
Web Interface: The Gradio-powered UI is simple and intuitive for medical professionals and non-technical users.
Real-Time Inference: Quick predictions based on uploaded images.
Demo
Here’s a sample output from the project:

[Include a screenshot or image of the Gradio interface with a sample prediction]

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-branch
Make your changes and commit them:
bash
Copy code
git commit -m "Added feature"
Push to the branch:
bash
Copy code
git push origin feature-branch
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
