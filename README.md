## Build a point cloud generator

- Point cloud generator webapp
  * The client can pick an item from a list of items (chair, airplane, car and etc.)
  * A separate model per item has to be trained and saved to be able to render the output.
  * The point cloud will be transformed from pure white gaussian noise until it achieves its final form
  * The point cloud will be rendered in real time
- I will use the model specified in the repo for now.
  * I'll try to improve the model with the equivariant approaches I am working with 
  * I'll be training it using the ModelNet10/ModelNet40 datasets
  * Need to make use of small MLPs such that when it's run in the inference mode, it can utilize the cpu and not a gpu.
- Build a skeleton of the application (Like the User interface and the logic of the application)

