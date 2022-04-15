# Product search using Azure Custom Vision

Azure Custom Vision is an image recognition service that lets you build, deploy, and improve your own image identifier models. An image identifier applies labels to images, according to their detected visual characteristics. Each label represents a classifications or objects. Unlike the Computer Vision service, Custom Vision allows you to specify your own labels and train custom models to detect them.

The Custom Vision service uses a machine learning algorithm to analyze images. You, the developer, submit groups of images that have and don't have the characteristics in question. You label the images yourself at the time of submission. Then the algorithm trains to this data and calculates its own accuracy by testing itself on those same images. Once you've trained the algorithm, you can test, retrain, and eventually use it in your image recognition app to classify images. You can also export the model itself for offline use.

Notebook in this repo:

1. [Azure Custom Vision API](https://github.com/vinayshanbhag/azure_custom_vision/blob/main/Azure_Custom_Vision.ipynb)


Datasets:
1. [Subset of images from this repo](https://github.com/vinayshanbhag/images)
2. [Test set of images to evaluate prediction results](https://github.com/vinayshanbhag/test_images)
