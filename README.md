# Neural-style-transfer-with-AdaIN
Neural Style Transfer with AdaIN

This repository contains an implementation of Arbitrary Neural Style Transfer using Adaptive Instance Normalization (AdaIN). Based on the groundbreaking 2017 paper by Xun Huang and Serge Belongie, this project allows you to apply the artistic style of any image to a target content image in real-time.

Unlike traditional optimization-based style transfer methods that require slow iterative processes, or feed-forward networks tied to a single, specific style, this AdaIN implementation aligns the mean and variance of the content features with those of the style features. This allows for instantaneous, high-quality stylization using any style image provided at inference time, without the need to retrain the network.


This repo provides a lightweight, easy-to-use implementation of AdaIN-based Neural Style Transfer. It is designed for fast inference and high-quality artistic rendering.

Key Features:

Arbitrary Stylization: Apply any style image to any content image—no need to train a new model for every new style.

Real-Time Performance: Utilizes Adaptive Instance Normalization for incredibly fast inference speeds compared to traditional optimization methods.

Style-Content Control: Easily adjust the alpha weight to control the balance between the original content structure and the applied artistic style.

Pre-trained Weights: (Include this if you are providing weights) Includes pre-trained models on the MS-COCO and WikiArt datasets so you can run inferences right out of the box.
