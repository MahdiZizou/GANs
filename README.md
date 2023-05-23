# GANs
## Anime face generation using deep learning
Generative Adversarial Network (GAN) is an unsupervised machine learning model using deep learning. In this project, GAN is used to extract features from Anime 
Face Dataset to train Generative (G) and discriminative (D) networks. In this project, both networks have five transpose convolutional layers. D network helps G to capture the samples distribution and G maximizes the probability of mistake in D. Thus, D tries to minimize mistakes ending to minmax optimization. Both networks contest with each other in a zero-sum game. Pictures developed by G are mimicking inputs having some noise. At the end, D learns to detect fake images too. We found that increasing epochs improve quality of generated images by G. 
