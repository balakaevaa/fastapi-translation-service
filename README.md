# Project Overview

In this project, we'll build a translation API using deep learning.  Using FastAPI, we'll create a web server that exposes a `/translate` route and a `/results` route.  Clients will post their translation request to the `/translate` route, and get the translation results from `/results`.  The server will use a sqlite database to store the translations.  On the backend, we'll use async and a pretrained deep learning language model to run the translation job.

By the end, we'll have a web server that can run translation jobs quickly.  This server can easily be extended to translate more languages, or add more options.

**Project Steps**
* Build API routes
* Add in models to store data to database
* Create tasks to run the translation


# Prerequisites

To complete this project, you'll need to have a good understanding of:

* Python syntax, including functions, if statements, and data structures
* Data cleaning
* Pandas syntax
* Using Jupyter notebook
* APIs
* The basics of machine learning.

