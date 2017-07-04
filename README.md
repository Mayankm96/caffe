# Changes in the repository
New layers added for the model:
* [pixelwise normalization layer](https://github.com/Mayankm96/caffe/blob/6b2e078d082124a127fa1ce149bd75ebd29a9a4a/include/caffe/layers/normalize_layer.hpp)
* [random concatenation layer (for skip netork)](https://github.com/Mayankm96/caffe/blob/6b2e078d082124a127fa1ce149bd75ebd29a9a4a/include/caffe/layers/rand_cat_layer.hpp)

These layers have been taken from [https://github.com/aayushbansal/caffe](https://github.com/aayushbansal/caffe). However, they are now updated to the latest caffe version.

# Caffe

[![Build Status](https://travis-ci.org/BVLC/caffe.svg?branch=master)](https://travis-ci.org/BVLC/caffe)
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)

Caffe is a deep learning framework made with expression, speed, and modularity in mind.
It is developed by Berkeley AI Research ([BAIR](http://bair.berkeley.edu))/The Berkeley Vision and Learning Center (BVLC) and community contributors.

Check out the [project site](http://caffe.berkeleyvision.org) for all the details like

- [DIY Deep Learning for Vision with Caffe](https://docs.google.com/presentation/d/1UeKXVgRvvxg9OUdh_UiC5G71UMscNPlvArsWER41PsU/edit#slide=id.p)
- [Tutorial Documentation](http://caffe.berkeleyvision.org/tutorial/)
- [BAIR reference models](http://caffe.berkeleyvision.org/model_zoo.html) and the [community model zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo)
- [Installation instructions](http://caffe.berkeleyvision.org/installation.html)

and step-by-step examples.

## Custom distributions

 - [Intel Caffe](https://github.com/BVLC/caffe/tree/intel) (Optimized for CPU and support for multi-node), in particular Xeon processors (HSW, BDW, Xeon Phi).
- [OpenCL Caffe](https://github.com/BVLC/caffe/tree/opencl) e.g. for AMD or Intel devices.
- [Windows Caffe](https://github.com/BVLC/caffe/tree/windows)

## Community

[![Join the chat at https://gitter.im/BVLC/caffe](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/BVLC/caffe?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Please join the [caffe-users group](https://groups.google.com/forum/#!forum/caffe-users) or [gitter chat](https://gitter.im/BVLC/caffe) to ask questions and talk about methods and models.
Framework development discussions and thorough bug reports are collected on [Issues](https://github.com/BVLC/caffe/issues).

Happy brewing!

## License and Citation

Caffe is released under the [BSD 2-Clause license](https://github.com/BVLC/caffe/blob/master/LICENSE).
The BAIR/BVLC reference models are released for unrestricted use.

Please cite Caffe in your publications if it helps your research:

```make
    @article{jia2014caffe,
      Author = {Jia, Yangqing and Shelhamer, Evan and Donahue, Jeff and Karayev, Sergey and Long, Jonathan and Girshick, Ross and Guadarrama, Sergio and Darrell, Trevor},
      Journal = {arXiv preprint arXiv:1408.5093},
      Title = {Caffe: Convolutional Architecture for Fast Feature Embedding},
      Year = {2014}
    }


@inproceedings{Bansal16,
  title={Marr {R}evisited: 2{D}-3{D} Model Alignment via Surface Normal Prediction},
  author={Bansal, Aayush and Russell, Bryan and Gupta, Abhinav},
  booktitle={CVPR},
  year={2016}
}
```
