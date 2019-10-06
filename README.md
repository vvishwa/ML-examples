# ML Examples

Source code for machine learning tutorials and examples used in [Arm's ML developer space](https://developer.arm.com/technologies/machine-learning-on-arm/developer-material).

## Projects and tutorials

### Update with Pi Zero W
Raspbian Stretch already supports Tensorflow 1.9 as of December 2018. However installing could be a challange. So follow below tips to install tensorflow on Pi Zero W running Raspbian Stretch

sudo pip3 install --no-cache-dir tensorflow \# --no-cache-dir will fix OutOfMemory problem
sudo apt install libatlas-base-dev

If you ever get issue related to sh1 checksum, pay attention to what url being used for downloading and change command to
"sudo pip install <.whl file>"

You can use python 2.7 (running python ) for commands like record (python record ..) but for running trained model use python3
Below 3 commands will save you from hassle of running python3 train.py

sudo apt-get install libhdf5 \
sudo apt-get install libhdf5-dev \
sudo pip3 install h5py 

### Arm NN MNIST
Deploy a TensorFlow MNIST model with the Arm NN inference engine.

* [Tutorial on Arm's developer site](https://developer.arm.com/technologies/machine-learning-on-arm/developer-material/how-to-guides/)
* [Source code on GitHub](armnn-mnist/README.md)

### Yeah, World
Explore gesture recognition with TensorFlow and transfer learning on the Raspberry Pi 4 Model B, Pi 3 and Pi Zero.

* [Tutorial on Arm's developer site](https://developer.arm.com/technologies/machine-learning-on-arm/developer-material/how-to-guides/teach-your-raspberry-pi-yeah-world)
* [Source code on GitHub](yeah-world/README.md)

### Multi-Gesture Recognition
Train a convolutional neural network from scratch to recognize multiple gestures in a wide range of conditions with TensorFlow and a Raspberry Pi 4 Model B or Pi 3.

* [Tutorial on Arm's developer site](https://developer.arm.com/technologies/machine-learning-on-arm/developer-material/how-to-guides/teach-your-pi-multi-gesture)
* [Source code on GitHub](multi-gesture-recognition/README.md)

### CMSIS-NN CIFAR10 model
Deploy a Caffe CIFAR10 model on Arm Cortex-M CPUs.

* [Source code on Github](cmsisnn-cifar10/README.md)
