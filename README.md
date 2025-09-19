This is my first Image classification project WITH CNN.
I used a dataset from kaggle.com.
I used Google collab to write the code. I had to first mount my drive to collab

    from google.colab import drive
    drive.mount('/content/drive')

Language used : PYTHON
Libraries : matplotlib, numpy, seaborn, tensorflow, keras, warning, os

OBSERVATION
There are notable confusions between certain classes, as indicated by the off-diagonal values in the confusion matrix. For instance, some images of one flower type are frequently misclassified as another. This suggests that the model may not be effectively learning the distinct features that differentiate these confused classes.

Further improvements could involve data augmentation, using a more complex model architecture, or fine-tuning a pre-trained model.

Enjoy reading my code.
