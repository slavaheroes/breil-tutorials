# breil-tutorials
This repo stores implementations of some DL architectures.

## Resnet experiments on the CIFAR-10
Look at the `resnet_implementaion.ipynb` notebook.

## FCN implementation
It consists of 2 notebooks:

1. `implementation-of-fcn8-with-resnet34-backbone.ipynb`: This notebook contains training script and visualization on some random sample of the test dataset. Eventhough the original was based on VGG16 backbone, I found this network extremely large and expensive to train for a such small dataset. The notebook has an implementation of FCN32s-VGG16, however, for fast convergence I trained the model with ResNet34 backbone.
    > Future experiment: To finetune VGG16 based implementation by loading image-net weights to the VGG16.

2. `resnet34-fcn-testing.ipynb`: This notebook was created only for visualization purposes. It contains some successful inference results.