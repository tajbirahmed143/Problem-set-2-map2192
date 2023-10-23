# Assignment 2 Report
## My code link
[Colab Notebook](https://colab.research.google.com/drive/1ew7dHNuk4Nt4YuSXSvjGGTY7pMrjIFui?usp=sharing)
## Step 1: Import Necessary Libraries
```md
import numpy as np
import matplotlib.pyplot as plt
from scipy import signal
from skimage import data, color, io
import imageio as io
from skimage.transform import rescale, resize
```
Here we import necessary libraries for handling numerical operations (NumPy), plotting (Matplotlib), signal processing (SciPy), and image manipulation (SciKit-Image and ImageIO).
## Step 2: Define Plotting Function
```md

def plot(x):
    fig, ax = plt.subplots()
    im = ax.imshow(x, cmap = 'gray')
    ax.axis('off')
    fig.set_size_inches(5, 5)
    plt.show()

```
plot(x) is a custom function to visualize an image (x) with a gray colormap and without axes, ensuring clean visual outputs. 

## Step 3: Load and Visualize Original Image
```md
image = io.imread("https://images.photowall.com/products/48203/outdoor-kitten.jpg?h=699&q=85")
image = image[:,:,:]
plot(image)
```
## Step 4: Resize Image
## Step 5: Convert to Grayscale Using Different Methods
## Channel Mixing Method
##
##
##










```md

```
