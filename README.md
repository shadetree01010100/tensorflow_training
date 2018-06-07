# TensorFlow Training

Learning reasources for the application and development of machine learning and artificial intelligence in the nio Platform. More thorough documentation and tests coming soon.

## How to Use

Clone this project template using the nio command line interface (CLI).

`nio new <new_project_name> -t https://github.com/tyoungNIO/tensorflow_training.git`
  
## Pre-Configured Services

**MNIST Digit Recognition**  
Train and test a neural network on a popular dataset of the hand-written digits 0-9. Tests an untrained network on 10k Test images, performs 10k training steps on another 50k Train images, and then repeats the 10K test images, surpassing 96% accuracy when trained.

Tensorboard logging is enabled, to use it open another teminal and run `tensorboard --logdir=<path/to/project/root>/tensorboard --host=0.0.0.0` and then open `localhost:6006` in a web browswer.

**Webcam Classification**  
Load a Google pre-trained image classification model, InceptionV1, and perform inferences (predictions) on frames captured from your local webcam at a rate of 1 frame/second. Frames that contain objects that can be identified with at least 50% confidence will be logged.
