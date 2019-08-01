# NMT (NeuroTechX Machine Learning Tools)

### Installing requirements
`pip install requirements.txt`

### Running the code
```from NMT.BrainActivity import *
X = [0,0,0,0] 	# dummy data
rf_predict(X)	# returns either "left", "right", or "rest" using random forest classifier
knn_predict(X)	# returns either "left", "right", or "rest" using knn classifier
```
