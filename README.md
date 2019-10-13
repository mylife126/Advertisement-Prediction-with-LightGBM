# Advertisement Demand Prediction
Special thanks Kaggle. The project utilizes its dataset and it is designed to predict demand for an online advertisement based on an advertisement's different features, such as price, descriptions, its context (geographically where it was posted, similar ads already posted) and historical demand for similar ads in similar contexts.

Thus, for this project, we have many features, denoted as the Xs, including the numerical feature- price, and many categorical/ non- numerical data, such as descriptions. Thus, the first part of this project would include two major parts:

1. Feature Extraction Engineering
2. Text Data NLP Engineering
3. And, then the model to be used is LightGBM, a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages:
	- Faster training speed and higher efficiency.
	- Lower memory usage.
	- Better accuracy.
	- Support of parallel and GPU learning.
	- Capable of handling large-scale data.
	- A quick referece I adviced is from： https://medium.com/@pushkarmandot/https-medium-com-pushkarmandot-what-is-lightgbm-how-to-implement-it-how-to-fine-tune-the-parameters-60347819b7fc
	
The dataset can be found at https://www.kaggle.com/c/avito-demand-prediction/data
