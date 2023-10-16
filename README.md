# Assignment 2 Report

## Task 1: Loading and Preprocessing the Image

In this task, we began by loading an image from a remote URL using the `requests` library and the `Image` module from the Python Imaging Library (PIL). The image we loaded was the following:

![Original Image](https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/1062x597/format/jpg/quality/100/https://s.aolcdn.com/os/ab/_cms/2022/10/28094926/2023-toyota-supra-gt4-evo-2.jpg)

The shape of the color image was (597, 1062, 3), indicating that it is a color image with dimensions 1062 pixels in width, 597 pixels in height, and 3 color channels (Red, Green, Blue). To make further processing easier, we resized the image to a size of 224x224 pixels.

## Task 2: Grayscale Conversion

In this step, we converted the resized image to grayscale. Grayscale conversion is a common preprocessing step in image processing. It simplifies the image to a single channel, making it easier to perform various operations. The resulting grayscale image had dimensions of 224x224 pixels.

## Task 3: Generating Random Filters

For this task, we defined a function `generate_random_filters` to create random filters. We generated 10 random 5x5 filters, simulating the behavior of convolutional filters used in deep learning models. Each filter was a matrix of random values.

## Task 4: Displaying the Images

We displayed both the color and grayscale images to visualize the preprocessing steps:

### Color Image (224x224)
![Color Image](https://colab.research.google.com/drive/1SZJuRMIzQ-KSVgiBuvgxWsCU7yVyyLsf#scrollTo=FaSbt5MdnZ9s)

This is the resized color image with dimensions 224x224 pixels.

### Grayscale Image (224x224)
![Grayscale Image](insert_grayscale_image_url_here)

This is the grayscale version of the image, also with dimensions 224x224 pixels.

Please replace the placeholders `insert_color_image_url_here` and `insert_grayscale_image_url_here` with the actual URLs or paths to your images. This report provides an overview of each task and its results in a structured manner.
