# CypherCNN — CIFAR-10 from scratch

A convolutional network trained on CIFAR-10 with TensorFlow/Keras, written up in
`Recognition of image on cifar-10.ipynb` with the augmentation setup, the learning-rate
schedule and the training curves that came out of those runs.

`CNN.py` holds the model definition and the scheduler used for the long runs; the `img/`
folder collects the plots from the experiments (filter visualisations, sample
predictions, accuracy/loss traces).

Nothing pre-trained is involved — the point was to see how far augmentation and a
schedule would take a small hand-built CNN on this dataset.
