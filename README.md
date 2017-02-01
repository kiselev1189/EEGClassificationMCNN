# EEGClassificationMCNN
Solution for EEG Classification via Multiscale Convolutional Net coded for NeuroHack at Yandex.

[Data and MCNN model dump](https://drive.google.com/file/d/0B6vZMotwvIlqemdQcFMzRlNkb0U/view?usp=sharing "Data and model dump")


# WARNING
Refactoring is in progress, this code is not entirely readable.

# Models
  - **Multifilter Convnet**: Apply 1D Convolutions of various filter size  to input timeseries and concatenate outputs to obtain the embedding
  - **Multiscale Convnet**: Apply 1D Convolution and Global Max Pooling to input timeseries resampled at different scales and concatenate outputs to obtain the embedding
