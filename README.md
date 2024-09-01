# Facial-Recognition-Using-CNN

The paper 'Siamese Neural Networks for One-shot Image Recognition' presents a novel approach to the
problem of one-shot learning in image recognition using Siamese neural networks. One-shot learning is a
machine learning paradigm where the model must correctly predict new classes given only a single example of
each class.
These networks are designed to learn similarity metrics between pairs of input images, allowing them to
generalize from learning discriminative features on a small dataset to recognizing new, unseen classes. The
networks leverage convolutional architectures to extract powerful, discriminative features without the need for
extensive retraining for new classes.
The paper outlines the methodology for training these networks on image pairs, using a combination of
convolutional neural network layers and a final layer that computes a similarity metric between the highestlevel feature representations of each image pair. This setup enables the network to generalize well to new
classes by leveraging learned similarities.

Our network (based from thenetwork from the paper) architecture follows the principles of a Siamese Neural
Network, designed for one-shot learning tasks. The network processes two input images in parallel through
shared weights to compute a similarity score indicating whether the images belong to the same person.

![image](https://github.com/user-attachments/assets/04bf4428-339c-42a1-817d-2b69bada5f3c)



