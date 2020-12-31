# Bank-Note-Authentication
#### Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.
### Data is provided above also you can download from the link: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

## Process:
* First of all the model is created using RandomForest Classifier and exported as a pickle file.
* Now made a tamporary website using flask and flasgger.
  * To run the tamporary site run the spider notebook program.
  * Use url: http://127.0.0.1:5000/apidocs/#/default/get_ans to get into flasgger API
