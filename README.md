# 项目

基于tensorflow2.0实现的梵高画作风格的图像迁移

基于吴恩达在 Coursera 上《深度学习》课程讲义实现图像风格迁移

## 说明

### 环境配置

```html
python3.6.5
```

依赖：

- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [Keras](https://keras.io/#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

### 迁移学习

- [迁移学习](https://sqdxwz.top/post/nUZlZ-2OR/)
- 使用预训练模型`VGG19`

### 仓库

本仓库包括以下：

- `utils.py`；
- `main.py`：主程序；
- `images`文件夹：放风格图片、转化图片；


## 使用

配置相应环境：
```python
pip install numpy

pip install tensorflow

pip install keras

pip install opencv-python
```

下载预训练的 VGG19 [模型](https://github.com/foamliu/Neural-Style-Transfer/releases/download/v1.0/imagenet-vgg-verydeep-19.mat) 放入 `pretrained-model` 目录，然后执行：

```bash
$ python main.py
```
