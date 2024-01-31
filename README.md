# An introduction to conformal prediction
### Slides of presentation: [Conformal prediction](workshop/2024-01-PyLadies-Amsterdam-meet-up-Conformal-prediction.pdf)
### [Video](https://www.youtube.com/watch?v=--WcrDRtrYk&t=1s) of the presentation: Leveraging conformal prediction for calibrated probabilistic time series forecasts - Inge van den Ende, PyData Eindhoven 2023
### Workshop summary in a [blog post](https://medium.com/@icvandenende/leveraging-conformal-prediction-in-python-to-accelerate-the-renewable-energy-transition-09b5c855f69d)
## Workshop description
During the workshop we will apply conformal prediction:
1. Add a prediction interval to a point forecast 
2. Calibrate a probabilistic forecast (conformalized quantile regression)

Open the notebooks in the workshop folder to make the assignment. You can find the full code in the 
notebooks in the solutions folder. Both notebooks show how implement that step in the `crepes` 
package, the `MAPIE` package and manually by yourself. 

## Requirements
Python >= 3.10 and experience with making a regression forecast. In the workshop we take a LightGBM
model as an example to make a forecast, but this model is not explained in the workshop.


## Usage
* Clone the repository
* Install requirements with `pip install -r requirements.txt`
* Start jupyter lab and navigate to the workshop folder
* Open the first workshop notebook

## Video record
Re-watch [this YouTube stream](https://youtube.com/live/QFtdTyIWrz8)

## Credits
This workshop was set up by @pyladiesams and @ingevandenende.
