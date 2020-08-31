RDKit ANI Weights
=================
This repository was created as a supplement to the addition of ANI style neural networks to the RDKit library. 
<br>
It contains the weights for the ANI-1x and ANI-1ccx ensembles for predicting the energy of molecules containing H, C, N and O atoms. 
All the weights and biases were obtained from the [torchani model zoo](https://github.com/aiqm/ani-model-zoo). They were then stored as binary boost serialized Eigen float matrices for the least amount of size along with ease of data loading.
<br>
These are pulled and extracted into the repository during build if the ```RDK_BUILD_ANI``` flag is set to true.