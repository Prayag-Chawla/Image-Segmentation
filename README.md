
## Image Segmentation
The goal of Image Segmentation is to train a Neural Network which can return a pixel-wise mask of the image.

## model
The model that I will use here is a modified U-Net. A U-Net contains an encoder and a decoder. In order to learn the robust features, and reducing all the trainable parameters, a pretrained model can be used efficiently as an encoder.


## Libraries and Usage

```
import tensorflow as tf
from tensorflow_examples.models.pix2pix import pix2pix
import tensorflow_datasets as tfds
from IPython.display import clear_output
import matplotlib.pyplot as plt

```


## Training vs validation loss
![image](https://github.com/Prayag-Chawla/Image-Segmentation/assets/92213377/d9bf6b73-8935-43cc-bcda-e4fbe3104891)




## Accuracy


![image](https://github.com/Prayag-Chawla/Image-Segmentation/assets/92213377/98e5a79b-f4ca-40db-8b3c-a38411413c9d)




## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Used By
In the real world, Image Segmentation helps in many applications in medical science, self-driven cars, imaging of satellites and many more. Image Segmentation works by studying the image at the lowest level.
## Appendix

A very crucial project in the realm of data science and image processing using visualization techniques as well as machine learning modelling.

## Acknowledgements

The project is taken from
https://thecleverprogrammer.com/2020/07/22/image-segmentation/
## Tech Stack

**Client:** Python, Image Segmentation



## Feedback

If you have any feedback, please reach out to us at chawlapc.619@gmail.com

