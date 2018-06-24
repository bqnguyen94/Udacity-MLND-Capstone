# MLND-Capstone

My capstone project for Udacity's Machine Learning Nanodegree

**Topic:** TalkingData AdTracking Fraud Detection Challenge

## Dataset

The training and testing datasets for the Fraud Detection Challenge can be downloaded from [Kaggle's competition webpage](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data).

Note: The notebook assumes data files are stored in `./data/` directory.

## Requirements

* Python >= 3.6
* numpy >= 1.14.3
* pandas >= 0.23.0
* scikit-learn >= 0.19.1
* xgboost == 0.72

Note: It is recommended to use XGBoost with GPU support for better performance. To enable GPU support for XGBoost, please build the library from [source](https://github.com/dmlc/xgboost) with flag `-DUSE_CUDA=ON`. See more [here](https://xgboost.readthedocs.io/en/latest/build.html#building-with-gpu-support).
