# DLAV_project_Raphael_Mathis

# Strucure
We mostly followed the originally given structure, adding a few elements with the code. 

# Changes 
- One-hot encoding for the driving direction
- Added some complexity to the model :
  - A 3 layer to the base CNN + batchnorm + average pooling
  - A history encoder
  - A command embedding
  - A bigger decoder with two fully connected layers
  - Camera input normalizing
 

# Results
After training for 50 epochs, our ADE dropped under 2 almost consistently. The trajectory seems decently correct, with a quite good overall direction, although sometimes going faster or slower than the ground truth (the curve being longer/shorter in the same direction).
