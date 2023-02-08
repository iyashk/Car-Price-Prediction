# Car Price Prediction

A model to predict the price of a used car should be developed in order to assess its value based on a variety of characteristics. Several factors affect the price of a used car, such as company, model, year, transmission, distance driven, fuel type, seller type, and owner type. As a result, it is crucial to know the car's actual market value before purchasing or selling it..

## Steps:

1. [ Creating a new Conda env. ](#step1)
2. [ Training. ](#step2)
3. [Execution](#step3)
4. [Testing of the Model.](#step4)
5. [Dataset](#dataset)

<a name="step1"></a>

## 1. Creating a new Conda environment

Its always better to implement a project in a new environment as you can know the exact requirements needed for the project to run. When we create a new environmen, we are starting with no pre-installed packages or tools. So to create a new environment in anaconda prompt use the command : `conda create -n carprice python=3.6`

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_1.png?raw=true" />
</p>

and now activate and switch to this environment using the command: `conda activate carprice`

<a name="step2"></a>

## 2. Training

Move to the location where you have cloned this repo, and now open the jupyter notebook from this directory.
now run every cell in the notebook.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_2(1).png?raw=true" width="625" height="200" />
</p>

After every cell is done running, we see a new file with `".pkl" extension` has been created in the same `src` folder. This file contains our model. A web interface has been developed using flask and HTML and can be used for prediction.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_2(2).png?raw=true" width="625" height="200" />
</p>

<a name="step3"></a>

## 3.Working of the Model on real-time user inputs

I recommend to install the following packages in the "carprice" environment

    - "flask" package : `pip install flask` command.

    - "jsonify" package : `pip install jsonify` command.

    - "requests" package : `pip install requests` command.

    - "numpy" package : `pip install numpy` command.

    - "sklearn" package : `pip install sklearn` command

Run the app.py in the anaconda prompt using `python3 app.py` then open the web-address displayed below.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/IMAGE.png?raw=true" height="200px" />
</p>

<a name="step4"></a>

## 4.Testing the model

A html page opens and enter the values according to the HTML file and the price is predicted.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/img_2.png?raw=true"  />
</p>
<a name="dataset"></a>

## 5.Dataset

The data we have used in this project was downloaded from <a href = "https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho" style="text-decoration:none;" target="_blank"> Kaggle</a>. It was uploaded from Cardekho.com .
The dataset consists of 301 rows and 9 columns with no null values. Column data
consist of independent Features. The independent features contain both categorical and numeric
values.
