# Object Detection for Visually Impaired Individuals

This project leverages the Inception V3 Convolutional Neural Network (CNN) model to detect obstacles in images, providing crucial assistance for visually impaired individuals. The dataset used for training and evaluation is the Flickr8k dataset. In addition, the project incorporates Google Text-to-Speech for audio feedback and WordCloud for visual representation of detected objects.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Navigating the world can be a significant challenge for visually impaired individuals. This project aims to mitigate these challenges by detecting obstacles in images using a deep learning model and providing auditory feedback. The goal is to offer real-time assistance that enhances the mobility and independence of visually impaired people.

## Features

- **Obstacle Detection**: Uses the Inception V3 model to detect and classify objects in images.
- **Auditory Feedback**: Converts detected objects into speech using Google Text-to-Speech, enabling real-time audio descriptions.
- **Visual Representation**: Generates word clouds from detected objects to provide a visual summary of the scene.

## Dataset

The Flickr8k dataset, containing 8,000 images and corresponding captions, is used for training and evaluating the model. This dataset is well-suited for object detection tasks due to its diverse range of scenes and objects.

## Model

The project utilizes the Inception V3 model, a pre-trained deep learning model renowned for its accuracy in image classification tasks. The model is fine-tuned on the Flickr8k dataset to improve its performance in obstacle detection.
