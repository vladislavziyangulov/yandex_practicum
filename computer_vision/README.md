# Client age estimation

At our disposal are photo-portraits and ages (in years) of customers of a supermarket. 
It is required to train the model to determine the approximate age of the client. 
This will help analyze purchases and offer products to customers of different age groups, as well as monitor the integrity of cashiers when selling alcohol.

The work is divided into exploratory analysis of the age groups represented in the dataframe, and the training itself, tuning the neural network

# Result

The resulting model performs well on the training, validation and test samples. 
Indeed, on the test sample the MAE is 7. 

The model is slightly overfitted, but thanks to regularization and augmentation, the overfitting is not severe
