A collection of notebooks and files related to my work on the [NCFM Kaggle competition](https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring).  I will update this collection until the competition end, unless I somehow manage to place competitively on the leaderboard, in which case this folder will become private.  I will primarily be using [Numpy](http://www.numpy.org/) and [Keras](https://keras.io/) for this project, although I may use some prebaked models from [Caffe's Model Zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo) if I get the chance.  My current trajectory is as follows:

1.  Data Augmentation (Train/Val) (Keras)
2.  Finetune Xception (Keras)
3.  Finetune VGG-16 and 19 (Keras)
4.  Finetune Resnet-50 (Keras)
5.  Augmented bagging for each model, then average the models together.  Better yet, stack a softmax classifier on top.  Even further, train nonlinear stacker on combination of original features and model predictions as described [here](http://mlwave.com/kaggle-ensembling-guide/)
6.  Use Bayesian optimization for training stacker
7.  Segmentation ([YOLO](https://groups.google.com/d/topic/keras-users/DjclH2L7epU), or something more compatible with Keras, or [something from Caffe](https://github.com/rbgirshick/py-faster-rcnn))
8.  Optimize for complementarity between models (e.g. optimize precision for one and recall for another)

UPDATE: I abandoned this plan after finding work in order to focus on my research at the Cleveland Clinic.
