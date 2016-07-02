Readme

# Requirements
- TensorFlow
- Python 2.7.x
- Numpy
- SciPy.io (For loading .mat files)
- PIL or Pillow
- Six (Python 2 and 3 Compatibility Library) 

# Data preparation

```
python GetLSPData.py
```

Dataset:

- [LSP Dataset](http://human-pose.mpi-inf.mpg.de/#download)

# Start training

Just run:

```
python TrainLSP.py
```


## To Follow Progress

```
tensorboard --logdir=/path/to/log-directory   #path is '~/Desktop/LSP_data/TrainData' if LSPGlobals.py is unchanged
```

