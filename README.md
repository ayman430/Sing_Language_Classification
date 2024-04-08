# Sing_Language_Classification
We aim to develop a robust model for classifying sign language characters. Given an image of a sign, our objective is to accurately determine the corresponding character it represents.

## Used tools 
- tensorflow and keras
- numpy
- pandas
- matplotlib
- openCV

## NoteBook contains
- As all images in one folder so we upload them in DataFrame to be able to split them in training, validation and test datasets.
- Use 'ImageDataGenerator' from keras to upload data from DataFrame using 'flow_from_dataframe'.
- Vizualize some images from random batches
- Analyzed the distribution of target classes to ensure balanced datasets.
- Leveraged a pre-trained Xception model, enhancing it with additional layers on top to craft a custom model tailored to our task.
- Compiled and trained the model for 10 epochs, utilizing ModelCheckpoint to save the best-performing model based on validation loss.
- Visualized model performance in terms of loss and accuracy during training.
- Conducted model testing to evaluate its performance.
- Loaded the best-performing model.
- Developed prediction functions:
    - Preprocessing function to prepare images before feeding them into the model.
    - Classification function to predict the character represented by the input image 
- load images and gives to model to real check for it, which gives a high ability for correct prediction

## Conclusion
### High accurate Sign Loanguage Classification Model with accuracy: 99% 
