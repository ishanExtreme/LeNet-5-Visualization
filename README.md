</p>
<h1 align="center">
  LeNet-5-Visualization
</h1>
 <h3 align="center">
  Visualizing each layer output of LeNet-5 model trained on mnist data(digits)
</h3>

## Architecture

<a href='http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf'>Official Paper</a>

<p align="center">
  <a>
    <img src="./index.png"/>
  </a>
  </p>
  
  
## Model Summary

Trained on mnist data
#### Performance
  loss: 0.0189 - accuracy: 0.9938 - val_loss: 0.0562 - val_accuracy: 0.9868
#### Summary
  <a>
    <img src="./summary.png" width="400" height ="500"/>
  </a>

## Visualization

#### Original Image
 <a>
    <img src="./orig.png" width="300" height ="300"/>
 </a>
 
#### Layer-1(conv2d)
 <a>
    <img src="./layer_1.png" width="350" height ="500"/>
 </a>
 
 #### Layer-2(max_pooling2d)
 <a>
    <img src="./layer_2.png" width="350" height ="500"/>
 </a>
 
 #### Layer-3(conv2d_1)
  <a>
    <img src="./layer_3.png" width="550" height ="700"/>
 </a>
 
 #### Layer-4(max_pooling2d_1)
  <a>
    <img src="./layer_4.png" width="550" height ="700"/>
 </a>
 
 ### Try it yourself on different digits on google colab or on local system by using checkpoint.zip and <a href='https://github.com/ishanExtreme/LeNet-5-Visualization/blob/master/LeNet_5.ipynb'>LeNet-5.ipynb</a> in the repository


