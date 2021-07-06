# TensorFlow Object Detection API

This project is for easy installing [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) via pip.

The corresponding PyPI project homapages can be seen from: [tf1-tensorflow-object-detection-api](https://pypi.org/project/tf1-tensorflow-object-detection-api/) for TensorFlow 1.x users, and [tf2-tensorflow-object-detection-api](https://pypi.org/project/tf2-tensorflow-object-detection-api/) for TensorFlow 2.x users.

## Installation

#### Simply install the TensorFlow Object Detection API with pip:

```
# for TF 1.x users
pip install tf1-tensorflow-object-detection-api

# for TF 2.x users
pip install tf2-tensorflow-object-detection-api
```

#### For platforms with compiled whls (Linux x86_64, Win amd64 and armv7l(Raspberry Pi)), you can also download the corresponding wheels from the releases and install it with pip:

- v2.2.0 : [TensorFlow Object Detection API for TF 2.x](https://github.com/forskamse/TensorFlow-Object-Detection-API/releases/tag/2.2.0)
- v1.15.0 : [TensorFlow Object Detection API for TF 1.x](https://github.com/forskamse/TensorFlow-Object-Detection-API/releases/tag/1.15.0)

```
# e.g. for Raspbeer Pi 4B
# for TF 1.x users
pip install tf1_tensorflow_object_detection_api-1.15-cp37-cp37m-linux_armv7l.whl
# for TF 2.x users
pip install tf2_tensorflow_object_detection_api-2.2.0-cp37-cp37m-linux_armv7l.whl

```
  
The wheels are built on the following platforms with dependencies:

- Linux x86_64
```
CentOS 7.4.1708
tensorflow 2.5.0/1.15.0
protobuf 3.12.3
python 3.7.6
```

- Windows amd64
```
Windows 10 19042.1052
tensorflow 2.5.0/1.15.0
protobuf 3.17.3
python 3.7.10
```

- Raspberry Pi armv7l
```
Raspbian 10 (buster)
tensorflow 2.2.0/1.15.0
protobuf 3.6.1
python 3.7.3
```

#### Install TensorFlow Object Detection API with compiling the source code:

You may refer to [TensorFlow Object Detection API for TF 2.x Installation](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2.md) and [TensorFlow Object Detection API for TF 1.x Installation](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1.md).

Note that you don't have to download or clone the original [tensorflow/models](https://github.com/tensorflow/models) repository.

---
For the whole story, please refer to [GitHub Pages - 使用pip安装TensorFlow Object Detection API](https://forskamse.github.io/2018/07/24/2018-07-24-%E4%BD%BF%E7%94%A8pip%E5%AE%89%E8%A3%85TensorFlow%20Object%20Detection%20API/#more) or [CSDN - 使用pip安装TensorFlow Object Detection API](https://blog.csdn.net/zbgjhy88/article/details/81183535).
