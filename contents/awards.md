In this work, we propose a general framework for inversely predict-
ing the structure type and the material thickness for each layer from
the input white light interferometry data with noise. We propose
a combination of UNet for denoising, CNN for classification and
MLP for layer thickness regression to address the problem.\


We can get an accuracy of 93.14% in the classification for no noise one and get an MSE from 0.0001 to 0.0036 in eight structures. \

The results are acceptable as we can get a very good estimation of the thicknesses of each layer, to further improve the performance, we can use some local optimization algorithms to fine-tune the thickness to a very precise level. It would be impossible to apply those algorithms without this fine estimation provided by our network. 


