# BostonHacks2018

## Fishvolution

Using machine learning, our project is meant to train a model to swim like a fish towards a destination in Unity. We used Tensorflow and wrote the scripting within Unity using C#. The Tensorflow training is written in Python, then converted into C#. We achieve fish-like motion through dividing our "fish" into a series of rectangular prisms connected by hinge joints. This is then inserted into simulated Unity water physics, and given a "goal" space to swim towards, which rewards the machine learning algorithm during the training stages. The algorithm is discouraged from moving too far away from the goal through assigning negative reward points.
