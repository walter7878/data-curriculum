# Libraries, packages and other [usbale] stuff (WIP).
## (Mainly Python)

## Time series
* [Forecasting Best Practices](https://github.com/microsoft/forecasting). This repository provides examples and best practice guidelines for building forecasting solutions. The goal of this repository is to build a comprehensive set of tools and examples that leverage recent advances in forecasting algorithms to build solutions and operationalize them. By Microsoft!
* [Prophet: Automatic Forecasting Procedure](https://github.com/facebook/prophet). Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.
* [GluonTS - Probabilistic Time Series Modeling in Python](https://github.com/awslabs/gluon-ts). From Amazon! GluonTS provides utilities for loading and iterating over time series datasets, state of the art models ready to be trained, and building blocks to define your own models and quickly experiment with different solutions.
* [sktime](https://github.com/alan-turing-institute/sktime). sktime is a Python toolbox for machine learning with time series. We currently support: Forecasting, Time series classification, Time series regression. sktime provides dedicated time series algorithms and scikit-learn compatible tools for building, tuning, and evaluating composite models. From the Alan Turing Institute.
* [Pmdarima](https://github.com/alkaline-ml/pmdarima). Pmdarima (originally pyramid-arima, for the anagram of 'py' + 'arima') is a statistical library designed to fill the void in Python's time series analysis capabilities. This includes: The equivalent of R's auto.arima functionality.
* [tslearn](https://github.com/tslearn-team/tslearn). A machine learning toolkit dedicated to time-series data.
* [pyts](https://github.com/johannfaouzi/pyts). A Python package for time series classification.
* [CESIUM](https://github.com/cesium-ml/cesium). Open-Source Platform for Time Series Inference.
* [AtsPy](https://github.com/firmai/atspy). Automated Time Series Models in Python (AtsPy). Easily develop state of the art time series models to forecast univariate data series. Simply load your data and select which models you want to test. This is the largest repository of automated structural and machine learning time series models.
* [Stumpy](https://github.com/TDAmeritrade/stumpy). STUMPY is a powerful and scalable library that efficiently computes something called the matrix profile, which can be used for a variety of time series data mining tasks.

## Recommender Systems
* [Surprise](https://github.com/NicolasHug/Surprise). Surprise is a Python scikit for building and analyzing recommender systems that deal with explicit rating data.

## Causal inference
* [DoWhy](https://github.com/microsoft/dowhy). From Microsoft. DoWhy is a Python library for causal inference that supports explicit modeling and testing of causal assumptions. DoWhy is based on a unified language for causal inference, combining causal graphical models and potential outcomes frameworks.
    * [Docs](https://microsoft.github.io/dowhy/).
* [Expan](https://github.com/zalando/expan). From Zalando. A/B tests (a.k.a. Randomized Controlled Trials or Experiments) have been widely applied in different industries to optimize business processes and user experience. ExpAn (Experiment Analysis) is a Python library developed for the statistical analysis of such experiments and to standardise the data structures used.
* [CausalML](https://github.com/uber/causalml). From UBER AI team. Causal ML is a Python package that provides a suite of uplift modeling and causal inference methods using machine learning algorithms based on recent research. It provides a standard interface that allows user to estimate the Conditional Average Treatment Effect (CATE) or Individual Treatment Effect (ITE) from experimental or observational data. Essentially, it estimates the causal impact of intervention T on outcome Y for users with observed features X, without strong assumptions on the model form.
    * [docs](https://causalml.readthedocs.io/en/latest/about.html).
    * [whitepaper/PDF](https://arxiv.org/pdf/2002.11631.pdf).
* [Causal Discovery Toolbox](https://github.com/FenTechSolutions/CausalDiscoveryToolbox). Package for causal inference in graphs and in the pairwise settings. Tools for graph structure recovery and dependencies are included.
* [CausalNex](https://github.com/quantumblacklabs/causalnex). A Python library that helps data scientists to infer causation rather than observing correlation.

## Social Media APIs, scrapers, etc.
* [twitter](https://github.com/sixohsix/twitter). The Minimalist Twitter API for Python is a Python API for Twitter, everyone's favorite Web 2.0 Facebook-style status updater for people on the go. Also included is a Twitter command-line tool for getting your friends' tweets and setting your own tweet from the safety and security of your favorite shell and an IRC bot that can announce Twitter updates to an IRC channel.
* [tweepy](https://github.com/tweepy/tweepy). Classic twitter api adapter.
* [twfollowbot](https://github.com/rhiever/TwitterFollowBot). A Python bot that automates several actions on Twitter, such as following users and favoriting tweets.
* [AutoScraper](https://github.com/alirezamika/autoscraper). A Smart, Automatic, Fast and Lightweight Web Scraper for Python. This project is made for automatic web scraping to make scraping easy. It gets a url or the html content of a web page and a list of sample data which we want to scrape from that page. This data can be text, url or any html tag value of that page. It learns the scraping rules and returns the similar elements. 


## Topic extraction & Knowledge Mining
* [PYthon Automated Term Extraction](https://github.com/kevinlu1248/pyate). Python implementation of term extraction algorithms such as C-Value, Basic, Combo Basic, Weirdness and Term Extractor using spaCy POS tagging.


## Graph and networks
* [Graphbrain](https://github.com/graphbrain/graphbrain). Graphbrain is an Artificial Intelligence open-source software library and scientific research tool. Its aim is to facilitate automated meaning extraction and text understanding, as well as the exploration and inference of knowledge. [Docs here](https://graphbrain.net/overview/hypergraph.html).
* [NetworkX](https://networkx.github.io/). NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks. [Github](https://github.com/networkx/networkx).
* [NERtwork](https://github.com/brandontlocke/NERtwork). NERtwork is a collection of scripts to help you create a network graph of co-occurring named entities using open source tools. This is done by using Stanford Named Entity Recognizer to identify named entities in the documents, then using NetworkX to create a bipartite projected network and exporting the node and edge lists for use in network visualization tools.


## Scalability and Parallelization
* [Pandarallel](https://github.com/nalepae/pandarallel). A simple and efficient tool to parallelize Pandas operations on all available CPUs.
* [swifter](https://github.com/jmcarpenter2/swifter). A package which efficiently applies any function to a pandas dataframe or series in the fastest available manner.
* [MODIN](https://github.com/modin-project/modin). Modin: Speed up your Pandas workflows by changing a single line of code/\.
* [VAEX](https://github.com/vaexio/vaex). Out-of-Core DataFrames for Python, ML, visualize and explore big tabular data at a billion rows per second 🚀
* [Numba](http://numba.pydata.org/). Numba is an open source JIT compiler that translates a subset of Python and NumPy code into fast machine code.


# NLP
## Datasets (English, multilang)
* [NLP Datasets List](https://github.com/niderhoff/nlp-datasets/blob/master/README.md). Alphabetical list of free/public domain datasets with text data for use in Natural Language Processing (NLP).
* [10.000 most used words](https://github.com/first20hours/google-10000-english).
* [LazyNLP](https://github.com/chiphuyen/lazynlp). A straightforward library that allows you to crawl, clean up, and deduplicate webpages to create massive monolingual datasets. Using this library, you should be able to create datasets larger than the one used by OpenAI for GPT-2.


# Data Preparation, wrangling and exploration
* [Missingno](https://github.com/ResidentMario/missingno). missingno provides a small toolset of flexible and easy-to-use missing data visualizations and utilities that allows you to get a quick visual summary of the completeness (or lack thereof) of your dataset.
* [Openrefine](https://openrefine.org/). OpenRefine (previously Google Refine) is a powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data.


## General ML and ML tools
* [Libra. 1 line ML models.](https://github.com/Palashio/libra) Libra automates the end-to-end machine learning process in just one line of code. It is built for both non-technical users and software professionals of all kinds.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen/). (Model 2 Code Generator) - is a lightweight library which provides an easy way to transpile trained statistical models into a native code (Python, C, Java, Go, JavaScript, Visual Basic, C#, PowerShell, R, PHP, Dart, Haskell, Ruby).


## XX Other stuff
* ML toolbox list https://amitness.com/toolbox/


---
Comments? Reach out to me via Twitter [@unbiasedwaldo](https://twitter.com/UnbiasedWaldo) or LinkedIn [/in/walterhgp/](https://www.linkedin.com/in/walterhgp/)
