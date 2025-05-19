# ml-cnn

Apply VGG-11 + batch normalization to do multi-class classification on FER2013 dataset.

### Problem: Use CNN model to classify class-imbalanced facial images

### Description
The training dataset contains 7 classes of class-imbalanced 48x48 facial expression images. You should apply any CNN algorithm using PyTorch package and create feature tensors based on the input images as the model’s inputs and train your CNN models to classify the training data. The training process must not include pre-trained weights. To evaluate the result, TA will run the command `$ python predict.py model.pth test output.csv`. Your prediction should be saved as a .csv file. **The test accuracy must be greater than 66%.**

### Grading Policy
If the testing accuracy of your prediction is greater than 66%, you will receive half of the credits. Other half of the credits would be evaluted based on your ranking on model performance.

### CNN Model Architecture
