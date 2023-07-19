# Visualizing-ConvNets

I wanted to try out the code that Francois wrote for visualizing what the convNets learn in his book (https://www.manning.com/books/deep-learning-with-python)

I used Pytorch and the Cifar-10 dataset.
The repository has two networks - the standard pytorch site code training for cifar-10, that gave 59% accuracy (https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html) and the second network is partly VGG-16 arch kinda network.
I have just added the visualising the convolutional layers for now.
<p float="left">
  <img src="/activations.png" width="300" />
  <img src="/conv2.png" width="300" /> 
</p>

Will add the grad cam activation maps in a later commit.
