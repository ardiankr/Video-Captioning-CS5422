# Video-Captioning-CS5422
Automatic video captioning, a final project for CS5422 Neural Networks and Deep Learning.
This project uses neural network to produce a simple fixed 3-words caption (\<noun\> \<verb\> \<noun\>) for each sequence of video frames.

## Neural network architecture
The neural network is composed of 4 main components:
  - Feature extractor using pretrained EfficientNet
  - Object classifier, a linear layer which sole purpose is to capture the presence of objects in each frame
  - Encoder, a linear layer which helps capture the action happening in each frame
  - Decoder, a RNN which produces the caption
  
  ![image](https://user-images.githubusercontent.com/40619020/158053073-f9fae73b-4b75-4721-9cb2-94c6c73b4458.png)

