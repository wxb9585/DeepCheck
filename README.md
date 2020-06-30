# DeepCheck
Use CNN and other deep learning method to automatically check the faulty part of the sewer.

DeepCheck is the project to use deep learning method to check the faulty of the sewer pips. The dataset is provided by the internship company and are not allowed to share. The final goal of this project is to implement the trained model onto the pip checking robot, and allow the robot to automatically check the faulty.

## Project process.

### Preprocess the dataset

The dataset is in a good order, which could be loaded to the $$ pytorch Imagefolder $$ directly. However, as the data is not balance and need to be improved. So i am going to use the image augmentation method to enlarge the unbalanced category.

### Separate data

