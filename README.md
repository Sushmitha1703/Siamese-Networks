# Siamese-Networks

Siamese networks are a special type of neural network used for tasks that involve comparing two different inputs, such as images, text, or other data. The key idea is that the network has two identical branches, which share the same architecture and weights. These branches process the two inputs independently but in exactly the same way.

After the inputs pass through their respective branches, the outputs are compared using a function, typically to calculate the distance or similarity between the two outputs. For example, in an image recognition task, if the inputs are two images, the network determines whether they are images of the same person by comparing their outputs. The closer the outputs are, the more similar the inputs are considered to be.

I have take the use case of MNIST number dataset for the experiment purpose do check it out
