# Object Localization with Tensorflow
Coursera Guided Project Network : [Object Localization with Tensorflow](https://www.coursera.org/projects/object-localization-tensorflow) </br> 
Instructor : Amit Yadav </br>
## Project Description </br>
This guided project employs TensorFlow's Keras API to train a convolutional neural network to classify and locate emojis in images. The position of the emojis in the photographs is referred to as localization in this context. This means the network will have a single input and two outputs. Object localization is a more straightforward variant of object detection. We may have many items in the input photos for object detection, and an object detection model predicts the classes as well as the bounding boxes for all of those objects. In object localization, we assume that there is only one item in each given image and that our CNN model will classify and locate that object. The model is trained with 500 epochs with ADAM (adaptive moment estimation) optimizers with an intial learning rate of 1e-3. A learning rate scheduler is applied to reduce the learning rate by a factor of 0.2 every five epochs. The minimum learning rate is set at 3e-7. The final classification accuracy achieved is 100% with an IoU (Intersection of Union) of 0.7228. </br>
## The framework and theory covered
1. TensorFlow
2. Keras
3. Machine Learning / Deep Learning
4. Computer Vision
5. IoU (Intersection of Union)

Source Code : [Object Localization with TensorFlow]()
