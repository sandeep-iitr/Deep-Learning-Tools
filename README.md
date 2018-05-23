# Deep-Learning-Tools

## Nvidia GPU
- ~3500 cores. Cores are individually slower, but are suitable for parallel things.

## Some Languagaes/packages
- cuBLAS: Library implements matrix operations which are optimized for Nvidia GPU's. 
- cuDNN: Convolution forward and backward passes. Batch normalization, RNNs for Nvidia Hardware.
- OpenCL: Runs on Nvidia and AMD hardware. It has less performance but is more general.
- For a large number of models: VGG, ResNet: GPU is 50-60x faster than CPU.
- Optimized libraries are 2-3x faster than the handwritten CUDA code.

## Tools
- Caffe (UC Berkeley), Caffe2 (Facebook)
- Torch (NYU/Facebook), PyTorch(Facebook)
- Theano (Univ. of Montreal), Tensorflow (Google)
- Paddle (Baidu), CNTK (Microsoft), MXNeT(Amazon)

First Generation from academia, and industry later finally adopted and have moved the revolution.

# Computation Graph
- The computation of the entire task in the graph structure, which may become complex.
- Tools: Easy to define the compuation (make the graph), compute gradients, run it efficiently. Less effort to make the system running.
- Codes looks very similar to NUMPY, but it runs on GPU. 
  - NUMPY: Doesn't run on GPU. Have to compute our own gradients.
  - Frameworks: automatically compute gradients and run on GPU.
  

# Examples
- Tensorflow-Example-1
- Tensorflow-Example-2

## Higher Level Libraries Around TensorFlow
- layers in Tensorflow.
- Keras is high level wrapper around TensorFlow. It is easy to use, and have a good community support.
- Different wrappers for TensorFlow are available: Like: Sonnet from DeepMind

## PyTorch
Three different levels of abstractions
- Tensor: It is an array which runs on GPU. Numpy with GPU
- Variable: Builds up computations graph. Equivalent to kind of Tensor, variable, Placeholders in TF
- Module: Neural network layer, which can be combined. Equivalent to higher level frameworks like layers in TF.

## Caffe
- Define network in Prototxt file, and solvers.
- Run the caffe binary. No code to be written.

### Caffe2
- Similar to TF. Core in C++.
- Nice Python Interface.
- Can train model in Python. 


## Sensing, Sensor Data
- ML tools are used a lot for sensor dataset. Ubiquitous computing term was coined by [Prof. Mark Weise](https://en.wikipedia.org/wiki/Mark_Weiser). Today, this capability of computing on every device has made it possible to have ML on every device.
