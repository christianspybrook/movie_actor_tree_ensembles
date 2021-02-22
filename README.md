movie_actor_tree_ensembles
=============================

Springboard Capstone 2
----------------------

This repository hosts all of the work for my second capstone project from the February 3rd, 2020 cohort of the Data Science Career Track with Springboard.

The goal of this project was to construct an actor centric dataset by using API requests from the TBDb movie website and build a tree ensemble model that could make accurate predictions on the data.

The hyperparameters were tuned using an informed search method via a Bayesian optimization algorithm, specifically sequential model-based optimization. I chose the Tree Parzan Estimator for the model selection algorithm, which used nonparameteric distributions to guide the search.

Project Workflow:

1. [Project Proposal](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/project_proposal)
: Written proposal describing the problem to be solved, possible clients interested in the results, my dataset source, my solution to the problem, and the format of my final work.
2. [Data Acquisition](https://github.com/christianspybrook/movie_actor_linear_regression/tree/master/data_acquisition)
: Notebooks containing  the code I used to extract and clean the dataset from TMDb.
3. [Data Wrangling](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/data_wrangling)
: Notebooks containing the code I used to munge the dataset into a form appropriate for this project and written reports describing the steps taken.
4. [Data Story](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/data_story)
: Notebooks containing the code I used to classify the actors by their career movie revenue averages and a written report describing the steps taken.
5. [Statistical Analysis](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/statistical_analysis)
: Notebooks containing the code I used to perform hypothesis testing on the distribution of the actors' genders with respect to their ages and career movie revenues and a written report describing the steps taken.
6. [XGBoost](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/xgboost)
: Notebook containing the code I used to find the best tree ensemble model to predict on the dataset and a written report describing the steps taken.
7. [Predictions](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/predictions)
: Notebook containing the code I used to predict on the dataset and a written report describing the steps taken.
8. [Final Report](https://github.com/christianspybrook/movie_actor_tree_ensembles/tree/master/reports/capstone_2_final_report.pdf)
: Written report composed of all the previous reports followed by a conclusion recommending possible next steps to take.