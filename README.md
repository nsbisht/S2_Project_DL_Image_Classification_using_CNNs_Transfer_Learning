# Age_Detection_Practice_Problem

Problem: https://datahack.analyticsvidhya.com/contest/practice-problem-age-detection/

- Approach Used: Transfer Learning
- Pre-trained Model Used: VGG19
- Accuracy Achieved: 89.90%

Key Points:

-	All images in the training and test dataset were resized to 64 x 64.
-	The pretrained VGG19 model available in TensorFlow was used.
-	All layers of VGG19 were retrained with the given training dataset.
-	Categorical Cross-Entropy was used as the loss function.
-	Stochastic gradient descent (SGD) was used as the optimizer.
-	The model was trained for 50 epochs with a validation split of 20%.

References:

[1] Top 4 Pre-Trained Models for Image Classification with Python Code
https://www.analyticsvidhya.com/blog/2017/06/hands-on-with-deep-learning-solution-for-age-detection-practice-problem/?utm_source=practice-problem-age-detection&utm_medium=Datahack

[2] Benchmark solution for this Problem
https://www.analyticsvidhya.com/blog/2017/06/hands-on-with-deep-learning-solution-for-age-detection-practice-problem/?utm_source=practice-problem-age-detection&utm_medium=Datahack
