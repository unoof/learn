[Stanford CS229: Machine Learning Lecture 1 - Andrew Ng (Autumn 2018)](https://www.youtube.com/watch?v=jGwO_UgTS7I&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=2)

Summary:
	Supervised learning:
		- X is input and Y is output
		- Dataset of (X, Y): which is from X -> Y
		- Base on that data to predict Y from a new X
		- Regression:
			- A continuous line that fit the data: can be a straight line or a curve line
			- Better the fit better the predict on new input
		- Classification:
			- Not liner
			- Example: multiple input X only give 0 or 1 as output Y
	Unsupervised learning:
		- X is input
		- Dataset of (X): multiple X then group it up
		- The model itself doesn't know the output but it group the inputs then predict base on it
		- Example: 2 dataset of 100 pictures about a ball and other about a cat, the model find the different in the dataset, the give it a picture of a ball it can guess it is a ball
	Reinforcement learning:
		- Make model do something:
			- If this what we want: reward it and keep doing
			- If not what we want: punish and make it do it again
			- Like train a dog:
				- Give treat when it do good
				- Slap it when it do something bad
			=> After train again and again, the more good things come and less bad things