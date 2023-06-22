# Clustering Workshop

Welcome to the Clustering Workshop! This workshop is designed to introduce participants to the fundamentals of clustering in machine learning. In this workshop, we will explore the K-Means clustering algorithm and learn how to apply it to real-world datasets. We will also discuss the evaluation of unsupervised models, specifically focusing on evaluating clustering results.

## Notebooks

This repository contains two Jupyter notebooks:

1. **Exercise 1 - Applying K-Means**: This notebook guides participants through the process of applying the K-Means clustering algorithm. It covers data loading, preprocessing, implementing K-Means using scikit-learn, visualizing clustering results, and interpreting the outcomes.

2. **Exercise 2 - Evaluating Clustering Results**: In this notebook, participants will learn how to evaluate clustering results. It demonstrates the calculation of evaluation metrics such as silhouette score and inertia using scikit-learn. Participants will analyze the metrics and interpret the quality of the clustering outcomes.

## Environment Setup

To set up the environment for running the workshop notebooks, you can follow these steps:

1. Clone the repository:

```bash
git clone git@github.com:neuefische/ds-meetups.git
cd ds-meetups/05_Clustering
```
2. Install pyenv using your preferred method (refer to the official pyenv documentation). (Only do this if necessary)

2. Set up the required Python version (e.g., Python 3.11.3) using pyenv:

```bash
pyenv install 3.11.3
pyenv local 3.11.3
```

2. Create and activate a virtual environment using venv:

```bash
python -m venv .venv
source .venv/bin/activate
```


3. Install the required dependencies:

```bash
pip install -upgrade pip
pip install -r requirements.txt
```

## License

This workshop is provided under the [MIT License](LICENSE).

Feel free to explore the notebooks and adapt them according to your needs. Happy clustering!
