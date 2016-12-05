# EEGClassificationMCNN
Solution for EEG Classification via Multiscale Convolutional Net coded for NeuroHack at Yandex.

# WARNING
This code is totally unreadable in its current state. Refactoring will occur in February'17

# Models
  - **Multifilter Convnet**: Apply 1D Convolutions of various filter size  to input timeseries and concatenate outputs to obtain the embedding
  - **Multiscale Convnet**: Apply 1D Convolution and Global Max Pooling to input timeseries resampled at different scales and concatenate outputs to obtain the embedding
