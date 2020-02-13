# Machine Learning Web System for predicting income in the USA

Build a machine learning web system for predicting income in the USA. 

The machine learning models are trained by [Adult income dataset] (https://archive.ics.uci.edu/ml/datasets/Adult). 

And the prediction can be pulled from the web service using REST API.

## Getting Started

```
git clone https://github.com/northernjay885/Machine-Learning-Web-System-for-predicting-income-in-the-USA.git
```

### Prerequisites


Install [anaconda distribution](https://www.anaconda.com/distribution/).

### Installing

Set up a virtual environment by
```
conda create --name dml python=3.7
```
Activate the environment
```
source activate dml
```
Conda install libraries and dependencies:

Scikit-learn, Xgboost, Pandas, JupyterLab, Django-RestFramework,

Django, Psycopg2, Postgresql, Joblib, Django-filter, Request

For example:
```
conda install -c conda-forge xgboost
```

## Running the tests

```
python manage.py test apps/endpoints/tests
```
```
python manage.py test apps/ml/tests
```

## Deployment

For deployment you need to intall [docker](https://www.docker.com/)
```
docker-composed up
```

## Built With

* [Django](https://www.djangoproject.com/) - The web framework used
* [Django-restframework](https://www.django-rest-framework.org/) - RESTful API

