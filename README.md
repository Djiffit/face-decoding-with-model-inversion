# Resolving faces from a neural network model
Implementation of a model inversion attack as described in https://www.cs.cmu.edu/~mfredrik/papers/fjr2015ccs.pdf on a small facial recognition model.

The dataset consists of 10 images per person, one of which is saved for validation and the model is trained on the remaining 9 images per person. There are a total of 40 people in this dataset.

After training the model we try to recover the face of the person who belongs to a the desired class, which seems to work out up to a point of the person being most likely identifiable from the recovered image.

Here are some examples of recovered images vs the real face of the person, all results can be found in the results folder.

![Some results](https://raw.githubusercontent.com/Djiffit/face-decoding-with-model-inversion/master/results/results.png)
