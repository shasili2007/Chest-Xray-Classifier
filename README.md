# Chest-Xray-Classifier
NN resnet which detects whether or not someone has pneumonia from an Xray of their chest.

## Status - Work in progress, currently fixing errors which i suspect is related to data leakage (as the average loss from training is extremely low) and the classification report, as only one classes is being predicted.

Dataset -> Chest X-Ray Images (Pneumonia), link on line below
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
5,863 images

Results:               precision    recall  f1-score   support

                  normal       0.38      1.00      0.55       234
               pneumonia       0.00      0.00      0.00       390

               accuracy                           0.38       624
               macro avg       0.19      0.50      0.27       624
            weighted avg       0.14      0.38      0.20       624




How to run -> Open pneumoniaV2.ipynb as a kaggle notebook, uploading from github, then attach corresponding dataset and run all cells.
