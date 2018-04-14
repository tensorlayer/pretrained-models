# Some Pretrained Models for TensorLayer

Feel free to add more. 

## CNN for ImageNet

Discussion for network architecture that can be easily use [here](https://github.com/tensorlayer/tensorlayer/issues/367).

|             	| Code      	| Model      	|   Top-1 Accuracy | Top-5 Accuracy  |
|-------------	|------------	|------------	|----------------- |-----------------|
|[VGG 16](http://arxiv.org/abs/1409.1556.pdf)|[code1](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_vgg16.py) [code2](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_models_vgg16.py)|[model](http://www.cs.toronto.edu/~frossard/post/vgg16/)|71.5|89.8|
|[VGG19](http://arxiv.org/abs/1409.1556.pdf)|[code](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_vgg19.py)|[model](https://github.com/machrisaa/tensorflow-vgg)|71.1|89.8|
|[ResNet V1 50](https://arxiv.org/abs/1512.03385)| | |75.2|92.2|
|[ResNet V1 101](https://arxiv.org/abs/1512.03385)||[resnet_v1_101_2016_08_28.tar.gz](http://download.tensorflow.org/models/resnet_v1_101_2016_08_28.tar.gz)|76.4|92.9|
[ResNet V1 152](https://arxiv.org/abs/1512.03385)||[resnet_v1_152_2016_08_28.tar.gz](http://download.tensorflow.org/models/resnet_v1_152_2016_08_28.tar.gz)|76.8|93.2|
[ResNet V2 50](https://arxiv.org/abs/1603.05027)^||[resnet_v2_50_2017_04_14.tar.gz](http://download.tensorflow.org/models/resnet_v2_50_2017_04_14.tar.gz)|75.6|92.8|
[ResNet V2 101](https://arxiv.org/abs/1603.05027)^||[resnet_v2_101_2017_04_14.tar.gz](http://download.tensorflow.org/models/resnet_v2_101_2017_04_14.tar.gz)|77.0|93.7|
[ResNet V2 152](https://arxiv.org/abs/1603.05027)^||[resnet_v2_152_2017_04_14.tar.gz](http://download.tensorflow.org/models/resnet_v2_152_2017_04_14.tar.gz)|77.8|94.1|
[ResNet V2 200](https://arxiv.org/abs/1603.05027)||[TBA]()|79.9\*|95.2\*|
[Inception V1](http://arxiv.org/abs/1409.4842v1)||[inception_v1_2016_08_28.tar.gz](http://download.tensorflow.org/models/inception_v1_2016_08_28.tar.gz)|69.8|89.6|
[Inception V2](http://arxiv.org/abs/1502.03167)||[inception_v2_2016_08_28.tar.gz](http://download.tensorflow.org/models/inception_v2_2016_08_28.tar.gz)|73.9|91.8|
|[Inception V3](http://arxiv.org/abs/1512.00567)|[code](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_inceptionV3_tfslim.py)|[model](https://github.com/tensorflow/models/tree/master/research/slim)|78.0|93.9| 
|[Inception V4](http://arxiv.org/abs/1602.07261)| | |80.2|95.2|
|[Xception](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chollet_Xception_Deep_Learning_CVPR_2017_paper.pdf)|||||
|[Inception-ResNet-v2](http://arxiv.org/abs/1602.07261)| | |80.4|95.3|
|[SqueezeNet V1](https://arxiv.org/abs/1602.07360)|[code1](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_squeezenet.py) [code2](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_models_squeezenetv1.py)|[model](https://github.com/tensorlayer/pretrained-models/blob/master/models/squeezenet.npz)||||
|[SqueezeNet V2](https://arxiv.org/abs/1602.07360)|||||
|[MobileNet V1](https://arxiv.org/pdf/1704.04861.pdf)| [code1](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_mobilenet.py) [code2](https://github.com/tensorlayer/tensorlayer/blob/master/example/tutorial_models_mobilenetv1.py)|[model](https://github.com/tensorlayer/pretrained-models/blob/master/models/mobilenet.npz)||||
|[MobileNet V2_1.4_224](https://arxiv.org/abs/1801.04381)|||74.9|92.5|
|[MobileNet V2_1.0_224](https://arxiv.org/abs/1801.04381)|||71.9|91.0|
[NASNet-A_Mobile_224](https://arxiv.org/abs/1707.07012)#||[nasnet-a_mobile_04_10_2017.tar.gz](https://storage.googleapis.com/download.tensorflow.org/models/nasnet-a_mobile_04_10_2017.tar.gz)|74.0|91.6|
[NASNet-A_Large_331](https://arxiv.org/abs/1707.07012)#||[nasnet-a_large_04_10_2017.tar.gz](https://storage.googleapis.com/download.tensorflow.org/models/nasnet-a_large_04_10_2017.tar.gz)|82.7|96.2|
[PNASNet-5_Large_331](https://arxiv.org/abs/1712.00559)||[pnasnet-5_large_2017_12_13.tar.gz](https://storage.googleapis.com/download.tensorflow.org/models/pnasnet-5_large_2017_12_13.tar.gz)|82.9|96.2|
|DenseNet|||||
|NASNet|||||


## Others

|             	| Code      	| Model      	|   Description   |
|-------------	|------------	|------------	|-----------------|
| SRGAN | [code](https://github.com/tensorlayer/srgan) | [model](https://github.com/tensorlayer/pretrained-models/blob/master/models/g_srgan.npz) | Super Resolution for Image |

- More Examples in [github](https://github.com/topics/tensorlayer) and [docs](http://tensorlayer.readthedocs.io/en/latest/user/example.html)
- References
  - [TF-Slim](https://github.com/tensorflow/models/tree/master/research/slim#pre-trained-models)
  - [Keras](https://keras.io/applications/#applications)
