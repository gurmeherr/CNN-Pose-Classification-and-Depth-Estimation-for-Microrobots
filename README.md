# Pose Classification and Depth Estimation of Microrobots

Pose classification and depth estimation are essential tasks in microrobotics, enabling precise identification and manipulation of micro-objects at micro- and nanoscale levels. Pose classification determines the orientation or configuration of microrobots in space, supporting tasks like trajectory planning, manipulation, and real-time monitoring. Depth estimation predicts the distance of microrobots from the imaging plane, which is critical for achieving accurate 3D tracking, manipulation, and automation.

## Models
The models used are:
1. Custom CNN
2. Vision Transformer
3. Resnet50
4. ConvNext-Tiny

### Pre-Requisite
1) Python 3.7+
2) Libraries:
a) torch (PyTorch)\
b) torchvision\
c) pickle (for classification label decoder)\
d) json (for regression stats)\
e) Pillow (for image loading)\
f) numpy and sklearn (if classification metrics are needed)\



## Points to be taken care of
1. Images must be resized to 224x224 and converted to 3-channel RGB
2. Models are trained
3. Use the label encoder and standardised depth files for proper unmapping to avoid ambiguity

## Email
gurmeherkhurana2000@gmail.com\
gurmeher.khurana24@imperial.ac.uk

## In case of any problem or for further assistance, please feel free to contact me

## Links to Colab Notebooks
1. EDA: https://colab.research.google.com/drive/1lR_0_A5wtcv4sHPlH-kTZ_L8s6N2Ci6V?usp=sharing
2. Custom CNN: https://colab.research.google.com/drive/1_l93Zy0pU8lDB5rR65Vweduve6gSHlKP?usp=sharing
3. ResNet50: https://colab.research.google.com/drive/1_PBDgBXSAEOrCdkwKOfZ4g88Y9KCFA7a?usp=sharing
4. Vision Transformer: https://colab.research.google.com/drive/1THMtBcjnHsJ4l-n3chQGXHfqXS91-Vzc?usp=sharing
5. ConvNeXt-Tiny: https://colab.research.google.com/drive/1o3C5iBgxEUj4Xm5LG2RI0w6ShxvxedCy?usp=sharing
6. ResNet50 Depth Estimation: https://colab.research.google.com/drive/1GZp-AltiEyZSWb8fyiMoWWzVgrQdn8X2?usp=sharing
