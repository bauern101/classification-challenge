# Background
Let's say I'm working at an Internet Service Provider (ISP) and I've been tasked with improving the email filtering system for our customers. I have been provided with a dataset that contains information about emails, with two possible classifications: spam **(1)** and not spam **(0)**. The ISP wants me to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

I  will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. Staring out, I will use a logistic regression model and a random forest model.

But why stop there.

The model generation will be sectioned off as looping fuctions.  They can be used for compairson in this study, and then suspended seperatly as my own little start to a Teapot syystem from multi-model optiomizations.