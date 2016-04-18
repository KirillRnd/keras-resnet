# keras-resnet
Residual networks implementation using Keras-1.0 functional API. 

### The original articles
 * [Deep Residual Learning for Image Recognition](http://arxiv.org/abs/1512.03385) (the 2015 ImageNet competition winner)
 * [Identity Mappings in Deep Residual Networks](http://arxiv.org/abs/1603.05027)

### Residual blocks
The residual blocks are based on the new improved scheme proposed in [Identity Mappings in Deep Residual Networks](http://arxiv.org/abs/1603.05027)

Both bottleneck and basic residual blocks are supported. To switch them, simply provide the block function [here](https://github.com/raghakot/keras-resnet/blob/master/resnet.py#L109)

### 50 Layer resnet model sample
Generated 50 Layer resnet model visualization [here](https://github.com/raghakot/keras-resnet/blob/master/resnet_50.png)
