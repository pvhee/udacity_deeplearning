# SVHN Number Classifier
> *Objective*: Classify Street View House Numbers

This is part of Udacity's final assignment (Lesson 7) for the Deep Learning course.

### Dataset

Dataset: http://ufldl.stanford.edu/housenumbers/

This is split up as following:

```
('Training set', (30061, 64, 64, 3), (30061, 6, 11))
('Validation set', (3341, 64, 64, 3), (3341, 6, 11))
('Test set', (13068, 64, 64, 3), (13068, 6, 11))
```


### ConvNet training

To train - or rerun a trained network on a saved model - run

    python -m svhn.model