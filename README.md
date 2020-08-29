movie_actor_linear_regression
=============================

Springboard Capstone 2
----------------------

This repository hosts all of the work for my second capstone project from the February 3rd, 2020 cohort of the Data Science Career Track with Springboard.

The goal of this project was to construct an actor centric dataset by using API requests from the TBDb movie website and build two tree ensemble models that could make accurate predictions on the data.

The hyperparameters were tuned using an informed search method via a Bayesian optimization algorithm, specifically sequential model-based optimization. I chose the Tree Parzan Estimator for the model selection algorithm, which used nonparameteric distributions to guide the search.

Project Workflow:

1. [Project Proposal](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/project_proposal)
: Written proposal describing the problem to be solved, possible clients interested in the results, my dataset source, my solution to the problem, and the format of my final work.
2. [Data Acquisition](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/data_acquisition)
: Notebooks containing  the code I used to extract and clean the dataset from TMDb.
3. [Data Wrangling](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/data_wrangling)
: Notebook containing the code I used to munge the dataset into a form appropriate for this project and a written report describing the steps taken.
