# Devanagari-Letters-DL

#### Goal
The primary goal for this project is to train a deep convolutional neural network that identifies characters of the Devanagari Script with a high level of accuracy (> 85% in testing).

#### Issue(s)
One conflict that arises when developing/training a model for this task is the lack of data (or images in this case) for the 46 individual characters (or classes). 

#### Data Augmentation Techniques
Performing basic transformations (rotations, resclaing, cropping, etc.) help to augment the data but there is a limit to this. 
One other solution I have thought of and developed (with some success) is a Deep Generative Adversarial Network that "creates" new images of the letters. 

#### Current Training Accuracy (updated 08/22): 80.21% 