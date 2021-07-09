simplePCA:

	- loads 30-Dimensional breast cancer data.

	- reduces the dimensionality along 2 principal components.

	- plots the reduced data.

PCAwithNN:

	- same as above with an added DNN to predict if tumors are 
		malignant or benign.

	- 2-D breast cancer data is split into 66% training data,
		and 33% testing data.

	- A Classification DNN is instantiated using TensorFlow
		with 2 hidden layers (with 10 nodes and 6 nodes, respectively).

	- The model outputs the accuracy after each epoch.
		(the model achieves 91% accuracy on testing data).

	- Hyperparameters:
		- learning rate = 0.01
		- epoch size = 20
		- batch size = 50
		- classification threshold = 0.8

	- hyperparameters can be tuned in the last cell.
