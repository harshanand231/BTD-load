## 📌Topic
Brain Tumor Detection

## Overview

This project implements a deep learning model for detecting brain tumors using MRI scans. The model is trained using Convolutional Neural Networks (CNNs) and deployed as a Flask API for easy inference.

## Getting Started

First, 
fork the repo.
then,
run the development server:

```bash
python app.py
# or
flask --app.py
```
## API Keys, Secret Keys

In .env file which in ignored in gitignore

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `templates/index.html in github i putted index.html outside because it was not rendeering from inside`.
The page auto-updates as you edit the file

## Features

Deep Learning Model: CNN-based image classification.

Preprocessing: Image normalization and augmentation.

Training & Evaluation: TensorFlow/Keras with accuracy and loss tracking.

Deployment: Flask API for predictions.

## Technologies Used

Python

TensorFlow/Keras

OpenCV

Flask

PostgreSQL (for login signup database)

JavaScript, HTML, CSS, Bootstrap (for frontend UI)

Google Developer Console for Sign-up with google

### Installation

Model Training

Flask API for Prediction

## Usage

Upload an MRI scan image via the Flask API.

The model will analyze and predict if a tumor is present.

The results will be displayed as JSON output.

Future Enhancements

Improve accuracy with transfer learning.

Deploy a web-based UI using React.

License

This project is licensed under the MIT License.
## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



## Authors

- [@harshanand231](https://www.github.com/harshanand231)

## 🚀 About Me
I'm a full stack developer...
