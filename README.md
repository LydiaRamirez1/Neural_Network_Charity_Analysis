# Neural_Network_Charity_Analysis
## Overview
The purpose of this analysis was to train a neural network model to predict whether money donated to an organization would be used successfully and for its intended purpose.

## Results
Data Processing:
- Variable examined as the target for my model: IS_SUCCESSFULL
- Variables that were examined as features for my model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- Variables that were removed from the dataset: EIN, NAME *These variables were removed due to them simply being identification information.

The Model:
- Neurons: 23
- Layers: 4
TanH was selected for the first two hidden layers. ReLU was selected for the last two hidden layers. Sigmoid was selected for the output layer.
Originally there were 13 neurons and 2 layers but more were added in an attempt to improve the performance of the model. The activation functions were selected becuase they were the best performing for each layer.

## Summary
The accuracy of the deep learning model was average. I would recommend trying to use a random forest model to see if less moving parts in the code lead to an easier time optimizing the model.
