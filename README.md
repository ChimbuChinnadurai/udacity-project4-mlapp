<img alt="CircleCI" src="https://img.shields.io/circleci/build/gh/ChimbuChinnadurai/udacity-project4-mlapp?style=for-the-badge">

## Project Overview

You are given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). This project tests your ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

---

## Setup the Environment

* Create a virtualenv and activate it
   
  python3 -m venv ~/.devops
  
  source ~/.devops/bin/activate
  
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`

2. Run in Docker:  `./run_docker.sh`

3. Run in Kubernetes:  `./run_kubernetes.sh`

   I have used minikube to launch a local kubernetes cluster and this script will deploy the application in that cluster
