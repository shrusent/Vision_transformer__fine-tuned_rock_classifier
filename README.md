# Vision transformer model fine-tuned for rock classification:

The rock data is provided in a drive link in the notebook. It has 360 for training and 120 images for testing. For alidation,we split the data from train to 120 images for validation. 
After fine tuning this model using rock data, a pick a linear layer that has 8 features from the ViT model and comapre those weights with the human data mds_120 provided here:https://osf.io/d6b9y/ .By using procustes analsyis, correlation between every fetaures in human data and average of validation and test data is computed to comapre whoch feature is highly correlated.
