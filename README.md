# # Diabetic retinopathy Deep learning prediction

This is replication of results from https://www.nature.com/articles/s41746-019-0172-3, achieving 75.92% accuracy on resized and augmented data. With a bit of feature engineering and data review (imbalanced classes) I believe this model can achieve over 80% accuracy.


# Files

There is only one notebook, written with FastAI to train and save the model, and recreate the experiment 

## Data

Data used can be downloaded from kaggle

## Approach

I used transfer learning in this experiment, using Resnet152, with several epochs on top of it with augmented data from this dataset


