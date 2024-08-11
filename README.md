# Building a computer vision model to classify images of cats and dogs

 Binary Image Classifier using Computer Vision
 
Developed a convolutional neural network (CNN) using TensorFlow Keras to classify images of cats and dogs. Downloaded and preprocessed the dataset, splitting it into training and testing sets. Designed and trained the model, achieving high accuracy in distinguishing between the two classes. Evaluated model performance with accuracy and loss metrics, visualizing the results using matplotlib. Deployed the model to predict and classify new images, demonstrating its effectiveness in real-world scenarios.

Image Augmentation techniques used:

    1. rotation_range
    2. width_shift_range
    3. height_shift_range
    4. shear_range
    5. zoom_range
    6. horizontal_flip
    7. fill_mode
    8. brightness and contrast manipulation

All these techniques were used in batches to test which set of augmentations gave the best results.