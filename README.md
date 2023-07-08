# Dog_Breed_Classification

This is an end-to-end dog breed classification project using Tensorflow 2.0 and Tensorflow hub

The Data used in this project is taken from Kaggle. https://www.kaggle.com/c/dog-breed-identification/data. It consists of a collection of 10,000+ labeled images of 120 different dog breeds. 

This kind of problem is called multi-class image classification. It's multi-class because we're trying to classify multiple different breeds of dog. If we were only trying to classify dogs versus cats, it would be called binary classification (one thing versus another).

TensorFlow/Deep Learning workflow:

1. Get data ready (download from Kaggle, store, import).
2. Prepare the data (preprocessing, the 3 sets, X & y).
3. Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
4. Evaluating a model (making predictions, comparing them with the ground truth labels).
5. Improve the model through experimentation (start with 1000 images, make sure it works, and increase the number of images).
6. Save, sharing, and reloading your model.
