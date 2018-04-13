## Introduction to Machine Learning
[![How Machines Learn](https://i.ytimg.com/vi/R9OHn5ZF4Uo/hqdefault.jpg?sqp=-oaymwEXCPYBEIoBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLBhawh-kkvwCIxcM7ig24ZdO3nGGg)](https://www.youtube.com/watch?v=R9OHn5ZF4Uo)

## Installing Python and TensorFlow Package
1. Install the latest 64-bit version of python.<br>[python-3.6.4-amd64.exe](https://www.python.org/downloads/release/python-364/)<br>
>**NOTE:** When installing, select the option to add python and pip to PATH.
2. Open a Command Prompt, and install the tensorflow package<br>
`pip3 install --upgrade tensorflow`

### Validating Install
1. Invoke python from a Command Prompt<br>
`python`
2. Enter the following short program inside the python interactive shell
```
import tensorflow as tf
hello = tf.constant('Hello, TensorFlow!')
sess = tf.Session()
print(sess.run(hello))
```
3. If the system outputs the following, then you are ready to begin writing TensorFlow programs:<br>
`Hello, TensorFlow!`

## Short Demo (TensorFlow For Poets)
1. Download and install a version of git for Windows<br>
[https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Execute the following demo in the **git bash** terminal<br>
[https://codelabs.developers.google.com/codelabs/tensorflow-for-poets](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets)

## Getting Started
[https://www.tensorflow.org/get_started/](https://www.tensorflow.org/get_started/)
