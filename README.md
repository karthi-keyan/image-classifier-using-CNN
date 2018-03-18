image classifier using convolution neural network

convolution layer discription:
==========================================================
convolution layer1 (1, 128, 128, 3)   filter  3X3
relu (1, 128, 128, 3)
==========================================================
convolution layer2 (1, 128, 128, 32)   filter  5X5
relu (1, 128, 128, 32)
maxpool layer (1, 64, 64, 32)   filter  2X2
==========================================================
convolution layer3 (1, 64, 64, 64)   filter  6X6
relu (1, 64, 64, 64)
maxpool layer (1, 32, 32, 64)   filter  2X2
==========================================================
fully connected layer (1, 600)
output layer (1, 2)
==========================================================
