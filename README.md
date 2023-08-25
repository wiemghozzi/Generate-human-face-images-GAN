# Generate-human-face-images-GAN
Our project embarks on a mission to construct a sophisticated model with the capability to generate images of humans that are not only highly realistic but also representations of individuals that do not and have never existed in the real world. The core technology enabling this pioneering venture is the Generative Adversarial Network, more colloquially known as GAN. Standing distinct from the typical architecture of traditional neural networks, GANs introduce an innovative approach to learning. Central to the GAN framework are two intertwined yet functionally distinct neural networks: the Generator and the Discriminator. Operating collaboratively, these two entities, however, serve different objectives. The Generator, through its intricate algorithms and layers, meticulously constructs images that closely resemble actual human faces. On the other hand, the Discriminator, with its analytical prowess, scrutinizes these crafted images, differentiating the real from the synthesized. The harmony and competitiveness between these two networks are crucial; when they function at their optimum capacity, the images generated are so authentic and detailed that they become almost impossible to differentiate from actual photographs.

![mod](https://github.com/wiemghozzi/Generate-human-face-images-GAN/assets/87756881/3b0430ff-24ce-483f-ba69-33d1c8a5ec25)


Our project utilizes a dataset sourced from [Kaggle](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset?resource=download), focused on facial recognition. This dataset encompasses 202,599 facial images of diverse celebrities, representing 10,177 unique identities (names undisclosed). Each image is enriched with 40 binary attribute annotations and 5 distinct landmarks: left eye, right eye, nose, and both corners of the mouth. This comprehensive collection, originally compiled by MMLAB at The Chinese University of Hong Kong, is structured for training, validation, and testing, and also includes bounding box information and attribute labels. It's a robust foundation tailored for advanced facial detection and attribute recognition tasks.

## Repository for Our Project:

### .ipynb_checkpoints: 

An auto-generated folder by Jupyter Notebook containing saved checkpoints of notebook iterations.

### .vs:

Associated with Visual Studio, this directory primarily houses user-specific settings and cached configurations. It's not typically accessed directly during AI or machine learning workflows.

### archive (1): 

This file encompasses our foundational dataset, comprising facial images and their pertinent annotations.

### gan model: 

Within this directory, our refined GAN models are securely stored as ".h5" files. Leveraging the HDF5 format, this setup guarantees streamlined storage and retrieval for extensive data elements.

### img_align_celeba:

A repository of the faux images crafted by our GAN model. These depictions illustrate the model's capability to emulate genuine human faces.

### README.md: 
A foundational markdown document that demystifies our project. It furnishes visitors with a comprehensive view of the project's objectives, its application, and guidelines on utilization or contribution.

### Untitled1.ipynb:

This Jupyter Notebook delves into the mechanics of our GAN model. It offers insights into the stages of data manipulation, blueprinting the model architecture, its training, and the resultant image generation.
