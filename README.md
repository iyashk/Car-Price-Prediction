# Car Price Prediction

A model to predict the price of a used car should be developed in order to assess its value based on a variety of characteristics. Several factors affect the price of a used car, such as company, model, year, transmission, distance driven, fuel type, seller type, and owner type. As a result, it is crucial to know the car's actual market value before purchasing or selling it.

## Steps:

1. [ Creating a new Conda env. ](#step1)
2. [ Execution. ](#step2)
3. [The Search Engine description.](#sengine)
4. [ Setting up in Windows. ](#winsetup)
5. [The Search Engine Usage.](#usage)
6. [Dataset](#dataset)

<a name="step1"></a>

## 1. Creating a new Conda environment

Its always better to implement a project in a new environment as you can know the exact requirements needed for the project to run. When we create a new environmen, we are starting with no pre-installed packages or tools. So to create a new environment in anaconda prompt use the command : `conda create -n carprice python=3.6`

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_1.png?raw=true" />
</p>

and now activate and switch to this environment using the command: `conda activate carprice`

<a name="step2"></a>

## 2. Execution

Move to the location where you have cloned this repo, and now open the jupyter notebook from this directory.
now run every cell in the notebook.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_2(1).png?raw=true" width="625" height="200" />
</p>

After every cell is done running, we see a new file with `".pkl" extension` has been created in the same `src` folder. This file contains our model. That can be used for prediction using a web interface dveloped using flask and html.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/Step_2(2).png?raw=true" width="625" height="200" />
</p>
**Step 3 :**

Run the app.py in the anaconda prompt. open the webpage link from the prompt.

<p align="center">
<img src="https://github.com/iyashk/Car-Price-Prediction/blob/main/images/IMAGE.png?raw=true" width="525" height="200" />
</p>

**Step 4 :**

A html page opens and enter the values according to the HTML file and the price is predicted.

after a pickle file named "random_forest_regression_model.pkl" genrates... Change the directory in the anaconda promt to where the pickle file is saved .

<a name="dataset"></a>

## 6.Dataset
