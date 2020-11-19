# PyTorch-CNN-MNIST
This repo contains a sample code to show how to create a cnn model using pytorch and trained on the mnist.
## Demo
> [http://pytorch-cnn-mnist.herokuapp.com/](http://pytorch-cnn-mnist.herokuapp.com/)

![](https://img-blog.csdnimg.cn/20201116104632753.gif)
## Install
Install pytorch and other necessary module.
```shell
pip install -r requirements.txt
```
## Train
Run train.py to train your cnn model on mnist dataset.
```shell
python train.py
```
## Test
Run test.py to test the trained model on your own handwritten digit.
```shell
python test.py
```
## Deploy
1. register an account of heruku
2. create an app on heruku
3. push the `deploy` folder to heroku master
