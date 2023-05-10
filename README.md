
# Road Sign Dtection ans Classification ⛔ 🚷 🚸

In this project, we aim to classify road sign images using transfer learning and comparing different architectures of CNN.
At the first step we built a network and then we tried to make it better, then we use transfer learning and ensemble learning to enhance the performance.


## 

 -  ### Dataset
  
We use GTSRB dataset on [kaggle](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) which consist of 40 classes and more than 50000 images.
 - ### Data Augmentation
 we use some data Augmentation techniques such as:
 width_shift_range, height_shift_range, vertical_flip, horizontal_flip, fill_mode, zoom_range.
 
 - ### Transfer Learning
 We use a Mobilenet and Densenet as our base models and change the last layer in different ways to fine-tune the model for our specific problem. We experiment with different combinations of the last layer and choose the best one based on the validation accuracy.

 - ### Ensemble Learning
 In order to use Ensemble Learning we combined densenet and mobilenet and we could achive the better accuracy rate.






