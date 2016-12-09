A collection of notebooks and files related to my work on the [NCFM Kaggle competition](https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring).  I will update this collection until the competition end, unless I somehow manage to place competitively on the leaderboard, in which case this folder will become private.  I will primarily be using [Numpy](http://www.numpy.org/) and [Keras](https://keras.io/) for this project, although I may use some prebaked models from [Caffe's Model Zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo) if I get the chance.  My current trajectory is as follows:

1.  Data Augmentation (Train/Val/Test) (Keras)
2.  Finetune Xception (Keras)
3.  Finetune VGG-16 and 19 (Keras)
4.  Finetune Resnet-50 (Keras)
5.  Ensemble with model averaging (manual or scikit-learn)
6.  Use Bayesian optimization for selecting architecture and training tops of models
7.  Segmentation ([YOLO](https://groups.google.com/d/topic/keras-users/DjclH2L7epU), or something more compatible with Keras, or [something from Caffe](https://github.com/rbgirshick/py-faster-rcnn))
8.  Optimize for complementarity between models (e.g. optimize precision for one and recall for another)
