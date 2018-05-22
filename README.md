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
  
