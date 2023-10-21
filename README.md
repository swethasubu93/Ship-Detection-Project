# Ship Detection 
### Overview
Building a Objection Detection model that can predict the location of a ship in a given satellite image. 
Using a given a set of images for which the location of the ships are provided, the model was trained on this data and used to predict the location of ships on test data. 

![Screenshot 2023-10-20 164547](https://github.com/swethasubu93/Ship-Detection-Project/assets/109064336/fea95634-d3f2-427d-b445-235b43a41d11)

### Model
A U-Net model is built for object detection.

##### Why UNet?
UNet is prominently employed in the domain of ship detection due to its adeptness at capturing intricate details, preserving spatial context, and facilitating segmentation tasks by combining downsampling and upsampling pathways. 
This architectural choice substantiates its suitability for achieving precise object detection, as required for ship detection within images.
The UNet architecture is a convolutional neural network structure known for its effectiveness in image segmentation tasks. It features a contracting path for downsampling, which captures context, and an expansive path for upsampling, which refines spatial information. 
The central bottleneck facilitates the integration of both global and local features, making it a popular choice for tasks that require precise and detailed segmentation - especially fro object detection.

![1_f7YOaE4TWubwaFF7Z1fzNw](https://github.com/swethasubu93/Ship-Detection-Project/assets/109064336/8639d39d-7fdb-492f-a61a-ffad87ee47c0)


### Results
The IOU (Intersection Over Nnion) evaluation metric is used- which is ideal of object detection cases. The trained U-Net model gave an IOU of 0.73.
![output](https://github.com/swethasubu93/Ship-Detection-Project/assets/109064336/5c7882a2-ad3f-403a-871f-8e63065375ea)
