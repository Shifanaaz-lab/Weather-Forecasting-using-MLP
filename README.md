# Weather-Forecasting-using-MLP
This project demonstrates the use of a deep learning MLP model, built with TensorFlow and Keras, to forecast atmospheric data from the ERA5 dataset. The goal is to showcase the application of deep learning techniques to a complex, real-world problem, achieving high prediction accuracy.

Weather Forecasting using Multilayer Perceptron (MLP)
This project demonstrates the development of a deep learning model using a Multilayer Perceptron (MLP) to forecast atmospheric data. The model is built using TensorFlow and Keras and is trained on the ERA5 dataset, which contains high-resolution global weather data.

The goal of this project is to showcase the application of deep learning techniques to a complex, real-world problem and to achieve high prediction accuracy.

Project Highlights
Deep Learning Model: An MLP model was engineered to handle complex meteorological data.

Data Processing: Utilized xarray and netCDF4 to handle large-scale atmospheric datasets from the ERA5 repository.

Performance Metrics: The model's performance was rigorously evaluated using key regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R 
2
  score.

Key Results: The model achieved exceptional performance, as demonstrated by the following metrics on the test set:

Mean Squared Error (MSE): 91.92

Mean Absolute Error (MAE): 7.02

R 
2
  Score: 0.9985

Technologies Used
Python: The core programming language for the project.

TensorFlow & Keras: Used to build, train, and evaluate the deep learning model.

xarray & netCDF4: Essential libraries for handling and processing the large NetCDF format weather datasets.

NumPy & Pandas: For data manipulation and analysis.

Scikit-learn: For data splitting and performance metric calculations.

Matplotlib: Used for data visualization.

Getting Started
Prerequisites
To run this notebook, you will need to have the following libraries installed:

pip install tensorflow xarray netCDF4 scikit-learn numpy pandas matplotlib


Dataset
The model is trained on the ERA5 dataset. Due to the large size of the files, they are not included in this repository. You can download them from the ERA5 Climate Reanalysis website.

Once downloaded, please place the files (data_0.nc, data_1.nc) inside a data/ folder in the root directory of this project.

Usage
Clone this repository to your local machine.

Place the ERA5 dataset files in the appropriate data/ directory.

Open the test_train_mlp_final.ipynb notebook in a Jupyter environment.

Follow the steps in the notebook to load the data, preprocess it, train the model, and evaluate its performance.

Contribution
This project is open for collaboration. Feel free to fork the repository, make improvements, or suggest new features via a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
