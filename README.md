# RAE_Reproduce
This is a reproduction of RAE (Robust Auto-Encoder).
## Description

In **AddNoise** package we have a method for adding noise into our training data set.  

In **data** folder, the training data are placed inside, and there is a file called data_visualization.ipynb which you can take a look at the format of data and data distribution.  

In **model** package, there are three models including Deep Autoencoder, Variational Autoencoder(VAE), Robust Deep Autoencoder. There is one method called train which we are used to training our model by parameterizing with model, data, and number of epochs.  

In **outputs**, we have put all the result plots into that folder.  

In **shrink** package, it contains ***l_1shrink*** and ***l_{2,1}shrink*** which is used to calculate proximal gradiant.  

**ImShow.py** is used to plot the image in a standard way.  

**RAE_Denoising.ipynb** compares the denoising ability with three models with different numbers of noises.  

**RAE_l21_Anomalous_Feature.ipynb** shows how RAE performs on anomalous feature detection.  

**RAE_l21_Instance_Detection.ipynb** shows how RAE performs on Instance detection by tuning the hyperparameters. 
## Codes
Codes can also be found here: https://drive.google.com/drive/folders/1tI3RLGwdQ20H2Dp7NkzA6Hl9dPJehknF?usp=sharing
## Original Article
***Anomaly Detection with Robust Deep Autoencoders***  
link here: https://dl.acm.org/doi/abs/10.1145/3097983.3098052?casa_token=9s9oAGTjX_cAAAAA:PfkmKNmrPXjPalWWLTfF_CTbEtfFXapsfWiktUmmlt_xIFgcAfCOFQjBmvJXgt9G87YySLhpV17F4A
## Slides of the reproduction
Read it in Slides/DM_Pre.
