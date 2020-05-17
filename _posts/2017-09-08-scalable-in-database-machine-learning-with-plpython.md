---
title: Scalable in-database machine learning with PL/Python (Postgres Open Silicon Valley 2017)
author: Srivatsan Ramanujam
date: 2017-09-08
categories: [Talks, Conference]
tags: [Apache MADlib, PL-Python, in-database ML, Greenplum MPP]
---

I presented a talk on scalable in-database machine learning using PL/Python at [Postgres Open Silicon Valley](https://postgresql.us/events/pgopen2017/schedule/session/343-scalable-in-database-machine-learning-with-plpython/). As a fan and long time Postgres users, I have greatly benefited by leveraging PL/Python User Defined Functions (UDFs) and User Defined Aggregates (UDAs). These tools greatly enhance the power of a SQL database like Postgres by bringing all the nimbleness of Python and it's rich ecosystem of libraries.

Below is a short summary of my talk, a link to the source code if you want to take it for a spin yourself and a video recording of my talk.

[Scalable in-database ML (GitHub)](https://github.com/vatsan/postgresopen-2017)

[![Scalable in-database ML (GitHub)](https://img.youtube.com/vi/_f3URz9RlCY/0.jpg)](https://www.youtube.com/watch?v=_f3URz9RlCYD)

> Enterprises who wish to build data driven machine learning applications should have access to technology that enables processing large volumes and flavors (structured, unstructured) of data efficiently and economically. There are vast collections of libraries for several specialized domains in the PyData ecosystem that are almost universally adopted by data scientists and engineers. Harnessing these libraries on a scalable platform/computation framework would help enterprises rapidly derive value from their data. In-database analytics brings computations to where the data resides, thereby reducing transport costs and I/O bottlenecks. PL/Python is a glue that binds the rich set of libraries in the PyData stack with the data residing in a Postgres database. In this talk I'll demonstrate how to harness the power Python and it's ecosystem of data science and machine learning libraries to build statistical models for machine learning applications, in database on Postgres. I will begin with an overview of PL/Python on Postgres and describe concepts such as User Defined Functions (UDF) and Aggregates (UDA) in detail. I will then describe data parallel and model parallel machine learning problems with real world applications in Natural Language Processing (NLP) and illustrate with examples how to leverage libraries such as numpy, scipy, scikit-learn for solving them through PL/Python.


