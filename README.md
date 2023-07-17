# FarmFusion

<img src="https://www.iisd.org/sites/default/files/styles/og_image/public/2020-06/RS2085_food-agriculture-topic.jpg?itok=cM6jCv9Q">

## Introduction

The Agriculture Solutions Web Application is a powerful and user-friendly tool designed to revolutionize farming practices and empower farmers with data-driven solutions. This web application is built using HTML, CSS, JavaScript, Flask, Python, and Machine Learning (ML) to provide essential services such as crop recommendation, fertilizer suggestion, and plant disease identification. With its intuitive interface and cutting-edge technology, this application aims to optimize agricultural productivity and promote sustainable farming practices.

## Features

### Crop Recommendation

<img src="https://media.istockphoto.com/id/177406803/photo/nebraska-cornfield.jpg?s=612x612&w=0&k=20&c=C-V8naH3UT0ZbHLX90V4G3Ycp91AeamkZuYScrsbvUg=" width="650">

Make informed decisions about crop selection with our advanced crop recommendation feature. By entering specific NPK values and your location, the application utilizes real-time temperature and humidity data fetched through a Weather API to provide personalized crop recommendations. Maximize yields by choosing crops suitable for your specific environmental conditions.

### Fertilizer Recommendation

<img src="https://www.geturbanleaf.com/cdn/shop/articles/fertilizer-1000x675.jpg?v=1629183715" width ="500">

Optimize fertilizer management with our comprehensive fertilizer recommendation feature. Specify your target crop and input NPK values to receive a detailed list of 5-6 fertilizer recommendations. This data-driven approach minimizes guesswork and ensures efficient nutrient utilization, leading to improved crop growth and reduced resource wastage.

### Plant Disease Identification

<img src="https://www.familyhandyman.com/wp-content/uploads/2020/05/Black-Spot-Diplocarpon-rosae-GettyImages-1097545284.jpg?fit=696,696" width="400" height="300">

Swiftly identify and combat plant diseases with our advanced ML-based plant disease identification feature. Simply upload an image of an infected plant, and the application's powerful ML algorithm analyzes the visual characteristics to identify the specific disease. Early detection enables timely intervention, protecting your crops and ensuring higher yields.

## DATA SOURCE 📊
- [Crop recommendation ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset)
- [Fertilizer suggestion](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv)
- [Disease detection](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

## Installation

1. Clone the repository: `git clone https://github.com/your-username/agriculture-solutions-webapp.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the application: `python app.py`
4. Open your web browser and access the application at `http://localhost:5000`

## Running the Project Locally 🛠️
- Before following the steps below, ensure that you have [git](https://git-scm.com/download), [Anaconda](https://www.anaconda.com/), or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system.
- Clone the project repository using the command: `git clone https://github.com/Gladiator07/Harvestify.git` or download and unzip the code if you prefer.
- Open Anaconda Prompt in the directory where the project was cloned and run the following commands:
  ```
  conda create -n farmfusion python
  conda activate farmfusion
  pip install -r requirements.txt
  ```
- Once the dependencies are installed, navigate to the project directory using the command: `cd farmfusion`
- To run the project locally, execute the following command:
  ```
  python app.py
  ```
- You will see a localhost URL displayed in the command prompt. Open this URL in your web browser, and now you can use the project locally.


## Demo



