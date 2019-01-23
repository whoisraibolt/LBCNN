# Local Binary Convolutional Neural Network for Facial Expression Recognition of Basic Emotions

## People

Alexandra Raibolt   ( [Lattes](http://lattes.cnpq.br/4144500977095845 "Lattes") | [E-mail](mailto:alexandra.raibolt@gmail.com "E-mail") )

Alberto Angonese    ( [Lattes](http://lattes.cnpq.br/8039229243803003 "Lattes") | [E-mail](mailto:aangonese@faeterj-petropolis.edu.br "E-mail") )

Paulo Rosa          ( [Lattes](http://lattes.cnpq.br/1512717941866097 "Lattes") | [E-mail](mailto:rpaulo@ime.eb.br "E-mail") )

## Overview

This Jupyter Notebook shows step by step, the process of building a Local Binary Convolutional Neural Network for Emotional Expression Recognition in Python using the TensorFlow framework.

In this example we use the [JAFFE](http://www.kasrl.org/jaffe.html "JAFFE") dataset.

**Notice:** 

- The LBCNN model proposed in this work was implemented in Python (version 2.7.12) using the TensorFlow framework (version 1.4.0) using a GPU based architecture, and might not work with other versions.

- The directory where the datasets should stay is not available in GitHub, since it would violate the dataset rules.

## Dependencies

- datetime
- scipy.stats
- sklearn.externals
- sklearn.metrics 
- gzip
- itertools
- matplotlib
- numpy
- os
- tensorflow
- time

You can install missing dependencies with [pip](https://pip.pypa.io/en/stable/ "pip"). And install TensorFlow via [TensorFlow](https://www.tensorflow.org/install/ "TensorFlow") link.

## Usage

1. Install the dependencies;
2. Run Jupyter Notebook in terminal to see the code in your browser.

## Credits

- Juefei-Xu, Felix, Vishnu Naresh Boddeti, and Marios Savvides. "Local binary convolutional neural networks." Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on. Vol. 1. 2017.

- Lyons, Michael, et al. "Coding facial expressions with gabor wavelets." Automatic Face and Gesture Recognition, 1998. Proceedings. Third IEEE International Conference on. IEEE, 1998.

- [Hvass-Labs](https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/02_Convolutional_Neural_Network.ipynb "Hvass-Labs")

## License

Code released under the [MIT](https://github.com/whoisraibolt/LBCNN/blob/master/LICENSE "MIT") license.
