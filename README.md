# Skin-Classification-using-Keras-and-Tensorflow
Building a deep learning model that classifies skin images with samples of 8 common skin pathologies and carcinoma.

There are three parts:

1. Classifying the diseases using a deep learning model.
2. Using transfer learning on ResNet, GoogleNet to retrain some part of the network.
3. Using a generative adversarial network(GAN) to generate new images for the diseases.

# Part 1 Conclusion

Model 3 provides training accuracy of 0.992%, test accu-
racy of 0.859% while validation accuracy of 0.867% has
been achieved without using data augmentation while
employing the same model which had provided 0.89%
test accuracy on Cats and Dogs dataset. The model uti-
lizes 1651 training examples while 354 for validation and
357 for test purposes and the results are achieved after
training for 3200 epochs using categorical crossentropy
as loss and accuracy as the metric with 5 convolution
layers with 64, 64, 128, 128, 256 filters of 3x3 each, three
dense layers with 256, 256 and 7 neurons respectively, dropout of 0.5 and rmsprop as the optimizer while using
softmax instead of sigmoid.

# Part 2 Conclusion

Using transfer learning increased accuracy from 0.859 to
0.865 using GoogleNet while it further increased to 0.935
using ResNet.

# Part 3 Conclusion

The images generated after 6400 iterations are better
than random noisy images but it requires more training
iterations to improve the results.
