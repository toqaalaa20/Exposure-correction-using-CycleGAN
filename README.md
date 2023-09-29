# Image enhancement using U-net

The goal of this project is to develop an image enhancement system using the U-Net architecture, a deep learning model known for its effectiveness in tasks such as image segmentation and restoration. In this project, we will focus on how U-Net can be used to improve the clarity and detail of images, making them more visually appealing and informative.

- The model is trained on MIT-Adobe FiveK Dataset.
- The image passes through 3 downsampling blocks, and 3 upsampling blocks, evaluated by percpetual loss from pretrained VGG16

- The dataset is split into training, validation, and testing directories
- A patch of size 128X128 is obtained from each image with its corresponding ground truth batch and then fed into the model for training
  
### Get Started 
1. Clone this repository
```
git clone https://github.com/toqaalaa20/An-application-for-Image-enhancement
```
