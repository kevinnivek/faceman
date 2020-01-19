# Faceman : An interactive art project

## Introduction

"Faceman" was concieved as an art installation project to combine AI based facial and facial expression (or emotion) detection with an immersive experience using multiple chained matrix LED output devices. This repository is an implementation of emotion recognition using [Deep Convolutional Neural Networks](https://github.com/atulapra/Emotion-detection/blob/master/ResearchPaper.pdf).

The objective is to interact with the participant by recognizing their face, potentially matching with a pre-built database of matched faces, then scanning their face to determine what expressive emotion they may be conveying.

A chained set of matrix LED devices will then be used to respond to the participant, based on their detected face and detected emotion. Ultimately the experience by the participant will be immersive in nature by bridging the gap between people and the machines they use in every day life. If a machine can not only recognize their face, but interpret their emotions then the connection between machines and humans deepens to an almost philsophical level.

Because this project utilizes an open source machine learning platform, it can technically learn, evolve and grow to become smarter at not only detecting faces but reading the multitude of expressive emotional tendencies that all humans may have. The intricacies in human emotional expression goes far beyond simply "Angry" or "Sad" and can encompass the endless grey in between.

This project is ultimately intended to encourage everyone to ask themselves where we must draw the line with interpretive recognition and analytics. The structure of privacy and personal protection laws can barely keep up with the evolving (and inexpensive) technology that can be purchased for $20. For $20 anyone can set up and implenent a mass surveilance system to catalog, inventory, recognize and interpret your facial expressions. 

## Hardware Dependencies

The system is designed to utilize the following hardware components :

- Raspberry Pi 4 (2GB or 4GB ram)
- 8 Megapixel NoIR Camera v2
- Four or more 32x32 5mm pitch matrix LED panels

## Dependencies

- Python 3, [OpenCV 3 or 4](https://opencv.org/), [Tensorflow 1 or 2](https://www.tensorflow.org/)


