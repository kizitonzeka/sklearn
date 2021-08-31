[![Udacity](https://circleci.com/gh/Udacity/sklearn.svg?style=svg)](https://github.com/kizitonzeka/sklearn)

## Project Overview

This project demonstrates operationalizing a Machine Learning Microservice API. 

With a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. More details on this can be found in [the data source site](https://www.kaggle.com/c/boston-housing).  A Python flask app `app.py` serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`
