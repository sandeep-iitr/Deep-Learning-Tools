# Deep-Learning-Tools

## Nvidia GPU
- ~3500 cores. Cores are individually slower, but are suitable for parallel things.

## Some Languagaes/packages
- cuBLAS: Library implements matrix operations which are optimized for Nvidia GPU's. 
- cuDNN: Convolution forward and backward passes. Batch normalization, RNNs for Nvidia Hardware.
- OpenCL: Runs on Nvidia and AMD hardware. It has less performance but is more general.
- For a large number of models: VGG, ResNet: GPU is 50-60x faster than CPU.
- Optimized libraries are 2-3x faster than the handwritten CUDA code.
