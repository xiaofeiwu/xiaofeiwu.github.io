# Reading List
* Nerf
* NeuralBody
* Pifu (2021.1.3)
* DynamicFusion
* DeformationTransfer
* Non-Rigid ICP

# Comparison of Pifu and Nerf
* Both work on single pixel, and use MLP to infer the result
* Nerf introduces positional encoding
* Pifu use 3D data for training, while Nerf use differential rendering, which takes 2D image as GT
* Pifu works on multiple people, while Nerf works on multiple images, but single scene
* Acceleration method on Nerf should also work on Pifu
* 
