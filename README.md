# Advanced_programming
Project2: Final Submissions
Date: December 18, 2022 Team: 3 (Mukhtar Amirkumar 221107032)
Selected paper: "Efficient Estimation of Word Representations in Vector Space"

Used Libraries:
from __future__ import absolute_import
from __future__ import division
from __future__ import print_function

import collections
import math
import os
import random
import zipfile

import numpy as np
from six.moves import urllib
from six.moves import xrange
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()


Firstly, I implemented the skip-gram model using tensorflow. After which I have converted my dataset to string  
I then changed my data's textual form into a numerical one so that it could be processed using a tensorflow graph. 
After that, I produced batches for my inputs.
Batches and labels that follow I once made tensorflow graphs. For the centerboard's target and the context words, I made two placeholders.
I used stochastic gradient descent for my optimization, after which I determined how similar these little baths were to the other words. 
After that, I began training my model.
Finally, the model was completed. 
I visualized the outcomes.















