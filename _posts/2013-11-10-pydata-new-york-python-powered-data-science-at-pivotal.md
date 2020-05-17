---
title: Python Powered Data Science at Pivotal - PyData NYC 2013
author: Srivatsan Ramanujam
date: 2013-11-10
categories: [Talks]
tags: [PyData NYC 2013, Python, Cloud Foundry, Greenplum MPP, Apache MADlib]
---

My colleague [Ian Huston](https://ie.linkedin.com/in/ihuston) and I presented how we leverage Python for data science projects in Pivotal at [PyData New York - 2013](https://pydata.org/nyc2013/abstracts/#106).

Here is a summary of our talk, you can view the slides below.

> The Python data ecosystem has grown beyond the confines of single machines to embrace scalability. Here we describe one of our approaches to scaling, which is already being used in production systems. The goal of in-database analytics is to bring the calculations to the data, reducing transport costs and I/O bottlenecks. The Greenplum Database is now part of the Pivotal Platform and provides super fast analytics capabilities through a shared-nothing architecture and SQL interface (based on Postgres). In addition to running parallel queries across terabytes of data using pure SQL it can also run procedural languages such as PL/Python. MADlib, Pivotal’s open source library for scalable in-database machine learning, uses Python to glue SQL queries to low level C++ functions and is also usable through the PyMADlib package. We will also show how we have used many of the standard tools in the Python data analysis toolkit in this framework, including Pandas, scikit-learn, nltk and of course NumPy and SciPy. In particular combining these tools has allowed us to perform sentiment analysis on large datasets and we will discuss the strategies and issues we have come across along the way.

[![Python Powered Data Science at Pivotal - PyData NYC 2013](https://raw.githubusercontent.com/vatsan/vatsan.github.io/master/assets/img/sample/pydata_nyc_2013.png)](https://www.slideshare.net/SrivatsanRamanujam/python-powered-data-science-at-pivotal-pydata-2013)
