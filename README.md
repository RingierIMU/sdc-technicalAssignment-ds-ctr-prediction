# Assignment: Click Through Rate Prediction

An assignment for practical and production machine learning.

--------------------------
#### directions for use

- fork this repo
- version control your progress in your personal repository.
- add your documentation to the docs directory
- when you are ready to let us see, add our github users to your repository

-----------------------

## Background

Marketplaces are a vital part of the free commerce eco-system. Historically, they were physical markets. More recently they have been known as classifieds and in present day, digital platforms for supporting the exchange of products and services for money. Fundamentally, we bring buyers to sellers.

Buyers visit our site in search of products and services. Sellers advertise their products and services. And when the buyer finds something they like, they click on the advertisement and show interest. This is known as a click through.

Click Through Rate (CTR) Prediction is a huge powerful tool for marketplaces, as a means to deliver even more value for sellers on our platform.

## Problem Statement

Build a Click Trough Rate (CTR) Prediction ML service.

### Tasks

- Design document with flow charts detailing production system.
- Training script (prepare, train, evaluate model)
- Serving script (serving model on localhost)
- Exploratory Analysis of model performance
- Documenting the Data Science Project [CRISP DM process](https://www.datascience-pm.com/crisp-dm-2/)

### Scope

- Your models predictions must be provided to client sites through an API
- The provided data represents a client sites products database.
- Feel free to make assumptions, as long as you document them.
- Python code is expected.

### Additional Tips

- Do not persist your model. Your training script should create a model given provided data.
- Make your work portable. We may test it on Linux or windows.
- More points are given for successfully modelling and explaining your model.
- All documentation could be conbined in to a single markdown file, similar to this README markdown.


## Data

You have been provided with a train dataset & a test dataset. Where `train` represents ~ 10 days of data where records are subsampled according different strategies based on clicks. Where `test` is 1 day of data with clicks omitted. Use this to test your model and validating ideas.

#### Get Data

Down the data from the link provided in email.

#### Features

| Field Name | Description |
|--|--|
| id | listing Identifier for each listing advertisement |
| unix_timestamp | time when click event occured. |
| ui_component_position | Position on device where listing advertisement was displayed. |
| site_id | partner sites where ad was shown. |
| site_domain | domain/country where partner site operates in. |
| site_category | | 
| app_id | special identifier for app used |
| app_domain | |
| app_category | |
| device_id | special identifier for device used |
| device_ip | |
|device_model | |
| device_type | |
| device_conn_type | type of network connection used by device |
| f0-f8 | anonymized categorical variables |
| click | Target variable (0/1). Where 1 - clicked, 0 - not clicked |

**We're Rooting for you** :+1:

![We are rooting for you.](images/rooting4you.webp)
