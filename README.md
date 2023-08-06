# Generative-Task-Autoencoders--GAN

In this test task we assume the following setup:

We have a small number of samples we actually want to generate;
We have some more samples that are closely related to the samples we want to generate;
And some more samples, that are completely unrelated structurally but share the same imaging modality.
For the sake of simplicity, we will use FashionMNIST dataset as an example. We want to generate images of sandals, having only 100 training examples, having 6k training images of ankle boots and sneakers, and more images of other wearables. We assume a simple task of classification as the downstream analysis task. We will classify all shoes into three classes (ankle, sneaker and sandal). As a baseline solution of this task, we use the simple oversampling of the data before the classifier training.

