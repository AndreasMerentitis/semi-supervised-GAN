# Semi-supervised GAN example

The goal is to demostrate the effect of using GANs to generate samples for semi-supervised 
learning in case of few labeled samples. It can be shown that this improves performance
over purely superivsed learning in such cases. 

The model has been tested with Tensorflow 1.5, adaptation to Tensorflow 2.x will happen
in the future. 

![relative path 1](/semi_supervised_gan.jpeg?raw=true "semi_supervised_gan.jpeg")
![relative path 2](/synthetic_samples_1D.jpeg?raw=true "synthetic_samples_1D.jpeg")

You can run the notebook locally or go to Google Colaboratory and point to this git
repositery (change runtime type -> select GPU). 

# Extending and reusing the basic idea from these sources:
* https://towardsdatascience.com/semi-supervised-learning-with-gans-9f3cb128c5e
* https://medium.com/@jos.vandewolfshaar/semi-supervised-learning-with-gans-23255865d0a4
* https://www.youtube.com/watch?v=j_-JaMPnhr0
