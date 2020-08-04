"# Signature-Similarity" 

Task: Generate a probability score(similarity score) for a given pair of images to verify whether they are same or not.


Data Source: https://www.kaggle.com/robinreni/signature-verification-dataset

Data set structure: Data set contains two folders(train and test images) and two CSV files(train_data.csv and test_data.csv) which have target as 1 if two images are similar else 0(forged signature)


Network: Saimese Similarity Network

loss="binary_crossentropy"

optimizer=sgd

Performaceof the model:

train_loss: 0.0697 - train_accuracy: 0.9973

val_loss: 0.0770 - val_accuracy: 0.9937
