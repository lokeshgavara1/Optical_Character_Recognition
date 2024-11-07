<h1 align="center"> OPTICAL CHARACTER RECOGNITION TOOL</h1>

<p align="center">
  <img src="https://cdn.investintech.com/wp-content/uploads/2021/06/OCR-Software.jpg">
</p>


[![Language](https://img.shields.io/badge/Python-darkblue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![Framework](https://img.shields.io/badge/Flask-darkgreen.svg?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/en/2.2.x/)
[![HTML](https://img.shields.io/badge/HTML-black.svg?style=flat&logo=html5&logoColor=white)](https://html.com/)
[![CSS](https://img.shields.io/badge/CSS-yellow.svg?style=flat&logo=css3&logoColor=white)](https://www.w3.org/TR/CSS/#css)
[![Javascript](https://img.shields.io/badge/Javascript-yellow.svg?style=flat&logo=javascript&logoColor=white)](https://www.javascript.com/)
![hosted](https://img.shields.io/badge/Heroku-430098?style=flat&logo=heroku&logoColor=white)
![hosted](https://img.shields.io/badge/Railway-430098?style=flat&logo=railway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-blue?style=flat&logo=docker&logoColor=white)
[![Gitpod](https://img.shields.io/badge/Gitpod-orange?style=flat&logo=gitpod&logoColor=white)](https://www.gitpod.io/)
![reposize](https://img.shields.io/github/repo-size/Nneji123/Automatic-License-Plate-Detection-Recognition-API)


## About
>A Flask web app that integrates Tesseract OCR to extract text from image files.. 

[Flask Web App](https://dao-ocr-production.up.railway.app/)


## Table of Contents
- [About](#about)
- [Repository File Structure](#repository-file-structure)
- [Problem Statement](#problem-statement)
- [Proposed Approach](#proposed-approach)
- [Tools Used :wrench:](#tools-used-wrench)
- [HTML Web App Demo](#html-web-app-demo)
- [OCR In Action](#ocr-in-action)
- [How to run the Application](#how-to-run-the-application)
- [Tests](#tests)
- [Deployment](#deployment)


## Repository File Structure
```bash
├───static
│   ├───css
│   │   └───images
│   ├───font-awesome
│   │   └───fonts
│   ├───fonts
│   │   ├───font-awesome-4.7.0
│   │   │   ├───css
│   │   │   ├───fonts
│   │   │   ├───less
│   │   │   └───scss
│   │   ├───Linearicons-Free-v1.0.0
│   │   │   └───WebFont
│   │   ├───montserrat
│   │   └───poppins
│   ├───forms
│   ├───img
│   ├───js
│   ├───test-img
│   ├───vendor
│   │   ├───aos
│   │   ├───bootstrap
│   │   │   ├───css
│   │   │   └───js
│   │   ├───bootstrap-icons
│   │   │   └───fonts
│   │   ├───boxicons
│   │   │   ├───css
│   │   │   └───fonts
│   │   ├───glightbox
│   │   │   ├───css
│   │   │   └───js
│   │   ├───isotope-layout
│   │   ├───php-email-form
│   │   ├───purecounter
│   │   └───swiper
│   └───vendorlog
│       ├───animate
│       ├───animsition
│       │   ├───css
│       │   └───js
│       ├───bootstrap
│       │   ├───css
│       │   └───js
│       ├───countdowntime
│       ├───css-hamburgers
│       ├───daterangepicker
│       ├───jquery
│       ├───perfect-scrollbar
│       └───select2
├───templates
├───venv
│   ├───Include
│   ├───Lib
│   │   └───site-packages
│   │       ├─── #Files and Folders
│   └───Scripts
└───__pycache__ 
```


## Problem Statement
>In today's world, we are flooded with a vast amount of data in different forms such as images, PDFs, and scanned documents. Extracting text data from these sources can be a tedious and time-consuming task. It is essential to convert these data sources into a digital format that can be easily processed and analyzed. Manually transcribing text from images is not only time-consuming but also prone to errors, making the process unreliable. This is where Optical Character Recognition (OCR) comes into play. The goal of this project is to create a Flask web app that can integrate Tesseract OCR to extract text from image files accurately.

## Proposed Approach
>The proposed approach is to create a Flask web app that can accept image files, extract text using Tesseract OCR, and display the extracted text in a readable format. The user will be able to upload an image file to the web app, and the web app will process the image using Tesseract OCR. The extracted text will then be displayed on the web app, and the user will have the option to copy the extracted text file. To ensure accuracy, we will test the web app with various image file formats and compare the extracted text with the original text. 



## Tools Used :
- Python
- Flask
- Flask-Scss
- HTML
- CSS
- Javascript
- Tesseract-OCR
- Pytesseract
- Rails
- Docker


## How to run the Application
<details> 
  <summary><b>Running on Local Machine</b></summary>

**To run the application on your local system do the following:**
1. Clone the repository:
```bash
https://github.com/lokeshgavara1/Optical_Character_Recognition.git
```

2. Change the directory:
```
cd Your directory name
```

3. Install the requirements:
```
pip install -r requirements.txt
```

4. Run the application
```
python -m flask run
```
**You should be able to view the application by going to http://127.0.0.1:5000/**
</details>


<details> 
  <summary><b>Running on Local Machine with Docker Compose</b></summary>

**You can also run the application in a docker container using docker compose(if you have it installed)**

1. Clone the repository:
```bash
https://github.com/lokeshgavara1/Optical_Character_Recognition.git
```

2. Change the directory:
```
cd Your directory name
```

3. Run the docker compose command
```docker
docker compose up -d --build 
```
You should be able to view the application by going to http://localhost:5000/
</details>
