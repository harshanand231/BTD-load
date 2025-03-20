<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brain Tumor Detection</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Brain Tumor Detection</h1>

        <h2>Overview</h2>
        <p>This project implements a deep learning model for detecting brain tumors using MRI scans. The model is trained using Convolutional Neural Networks (CNNs) and deployed as a Flask API for easy inference.</p>

        <h2>Features</h2>
        <ul>
            <li><b>Deep Learning Model:</b> CNN-based image classification.</li>
            <li><b>Preprocessing:</b> Image normalization and augmentation.</li>
            <li><b>Training & Evaluation:</b> TensorFlow/Keras with accuracy and loss tracking.</li>
            <li><b>Deployment:</b> Flask API for predictions.</li>
        </ul>

        <h2>Technologies Used</h2>
        <p>Python, TensorFlow/Keras, OpenCV, Flask, PostgreSQL (optional), React.js (for UI)</p>

        <h2>Installation</h2>
        <pre>
        git clone https://github.com/yourusername/brain-tumor-detection.git
        cd brain-tumor-detection
        pip install -r requirements.txt
        python app.py
        </pre>

        <h2>Usage</h2>
        <p>- Upload an MRI scan image via the Flask API.</p>
        <p>- The model will analyze and predict if a tumor is present.</p>
        <p>- The results will be displayed as JSON output.</p>

        <h2>Future Enhancements</h2>
        <ul>
            <li>Improve accuracy with transfer learning.</li>
            <li>Deploy a web-based UI using React.</li>
        </ul>

        <h2>License</h2>
        <p>This project is licensed under the MIT License.</p>
    </div>
</body>
</html>
