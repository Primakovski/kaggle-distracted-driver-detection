# kaggle-distracted-driver-detection

I have imlemented simple solution for a very interesting [kaggle competition](https://www.kaggle.com/c/state-farm-distracted-driver-detection).
It was done only for educational purpose with very limited time so there is still a huge amount of things which could be improved.

I used Keras + pretrained VGG16 network where I freezed first 4 blocks of convolutioanl layers during training. 
I also substituted last classification layer with my custom one for correct classification.

With such approach I got 0.44659 score on the Private Leaderboard and 99.69% valdation accuracy after only 5 epochs of training.

[Dataset](https://www.kaggle.com/c/5048/download-all) must be extracted into the ~/input folder.
