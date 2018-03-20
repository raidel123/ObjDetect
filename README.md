# ObjDetect
TensorFlow Object Detection (Learning the ropes of TensorFlow)

## Requirements
The installation was performed on a Windows machine using Windows Command Prompt (CMD)

### System Requirements
* Python 2.x
* Pip
* Virtualenv
```
    > pip install virtualenv
```
* [TensorFlow Models](https://github.com/tensorflow/models)
```
    > git submodule update --init --recursive
```

### Install Requirements
#### To install all requirements together:
```
    > pip install -r requirements.txt
```
#### To install certain components individually:
Tensorflow
```
    > pip install tensorflow

    OR

    > python -m pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.7.0rc0-py2-none-any.whl
```

## Run Program:
Create a Virtualenv and activate venv
```
    > virtualenv venv
    > venv\Scripts\activate
```
To Deactivate Virtualenv:
```
    > deactivate
```

## Extra Notes
Using protoc inside of models/research (using bash)
```
    > ../../../Downloads/protoc-3.5.1-win32/bin/protoc.exe object_detection/protos/*.proto --python_out=.
```

## Author
[Raidel Hernandez](https://github.com/raidel123)
