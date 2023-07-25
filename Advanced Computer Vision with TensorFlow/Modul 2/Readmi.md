# Week 2
This week, we’ll get an overview of some popular object detection models, such as regional-CNN and ResNet-50. You’ll use object detection models that you’ll retrieve from TensorFlow Hub, download your own models and configure them for training, and also build your own models for object detection. By using transfer learning, you will train a model to detect and localize rubber duckies using just five training examples. You’ll also get to manually label your own rubber ducky images!

--------
# Learning Objectives
1. Get a conceptual overview of Regional CNN (R-CNN), Fast-RCNN, and Faster R-CNN.
2. Retrieve the R-CNN model from TensorFlow hub and use it to perform object detection.
3. Use TensorFlow’s object detection API to visualize the predicted bounding boxes from an object detection model
4. Go beyond models in TensorFlow Hub: Load and configure a Resnet-50 model that isn’t on TensorFlow Hub, restore pre-trained weights, and select the parts of the model to retrain.
5. Use the object detection API to manually annotate images for object detection
6. Implement a custom training loop to fine-tune a model using just 5 training examples.

# Object Detection
***************
## References: Amazon Rekognition, PowerAI & DIGITS
- [Amazon recognition](https://aws.amazon.com/rekognition/?blog-cards.sort-by=item.additionalFields.createdDate&blog-cards.sort-order=desc)
- [PowerAI](https://cloud.ibm.com/catalog#services)
- [DIGITS](https://developer.nvidia.com/digits)


## Reference: R-CNN, Fast R-CNN
- ([R-CNN](https://arxiv.org/abs/1311.2524)) Rich feature hierarchies for accurate object detection and semantic segmentation (Girshick Donahue, Darrell & Malik, 2013)

- [Fast R-CNN](https://arxiv.org/abs/1504.08083) (Girshick, 2015)

# Object Detection in TensorFlow
***************
## Reference: TensorFlow Hub
[TensorFlow Hub](https://www.tensorflow.org/hub)

# Object Detection APIs
***************
## Read about the Object Detection API
- Please read more about the object detection API here: ([link](https://github.com/tensorflow/models/tree/master/research/object_detection))

- Please also read through the guides at the bottom of this page: ([link](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2.md))

- Please also read up on checkpoints and how they work ([link](https://www.tensorflow.org/guide/checkpoint))

## Use the Object Detection API
Please go through this [official tutorial](https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/tf2_object_detection.ipynb) from Tensorflow to practice using the Object Detection API


# Retraining with the Object Detection API
---------
## Reference: RetinaNet, Model Garden
- ([RetinaNet](https://arxiv.org/abs/1708.02002)) Focal Loss for Dense Object Detection (Lin, Goyal, Girshick, He &  Dollár, 2017)

- [TensorFlow's Model Garden](https://github.com/tensorflow/models)

## Eager Few Shot Object Detection
Please go through this [tutorial](https://colab.research.google.com/github/https-deeplearning-ai/tensorflow-3-public/blob/main/Course%203%20-%20Advance%20Computer%20Vision/W2/ungraded_labs/C3_W2_Lab_3_Interactive_Eager_Few_Shot_OD.ipynb) to practice using the Object Detection API and training a pre-trained model. This will be very similar to this week's programming assignment.
