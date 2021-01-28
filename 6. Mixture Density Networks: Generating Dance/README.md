The model can generate its own version of dancing based on the given input data. Unfortunately, the input has to be void of distracting background or the dancer has to be easily distinguishable by having a mask of either 0 or 255 value pixels (white or black). I've used a dancing video that I found on YouTube that is shown in the clip. The mask is all black.

The implementation is using variational encoder with Mixture Density Layer. I'm using three LSTM layers with three dropout layers with the activation function RELU and output with Mixture Density Layer.
