---
layout: post
title: "Production and large databases projects"
date: 2022-01-01
excerpt: "Few production and large databases personal projects"
tags: [database, sql, python, memory, optimization, pipeline]
comments: false
---

This section shows some of the projects I have done as a result of my learning process or hobby.

***

## Production and large databases

***

- Building a database with PostgreSQL in Python for crime reports in Boston

In this project, a simple database is created using PostgreSQL inside a Python environment. For this purpose, the package `psycopg2` is essencial as a PostgreSQL database adapter for the Python programming language.

[GitHub/crime-reports](https://github.com/cadovid/crime-reports)

- Optimizing dataframes' memory usage and processing in chunks

This project demonstrates how to optimise the memory footprint of a dataframe and how to work with dataframe chunks. All these steps make it possible to work with dataframes that, a priori, do not fit within the memory limits of a given storage.

[GitHub/loans-optimization](https://github.com/cadovid/loans-optimization)

- Analyzing wikipedia pages using MapReduce techniques (parallel processing)

In this project a grep-like algorithm is implemented in Python by using MapReduce techniques (parallel processing) for a given dataset. The main functionality of this algorithm is to search the specific location of a target string inside all of the dataset files.

[GitHub/wikipedia-parallel](https://github.com/cadovid/wikipedia-parallel)

- Building a key-value store database through a complex tree data structure

In this project, a B-tree data structure is implemented from scratch as a building block for a fully functioning key-value store. This key-value store will work like a Python dictionary, but it will also allow users to perform range queries, similar to multiple implementations of the key-value store used in production-grade systems worldwide, like Redis, CouchDB, Mongo, or Cassandra. In this way, these queries are performed in a more efficient computation time than in a simpler implementation.

[GitHub/key-value-tree-database](https://github.com/cadovid/key-value-tree-database)

- Building a data pipeline class

In this project, a data pipeline class that schedules the tasks in the correct order is constructed in Python from scratch. This class will be built around a directed acyclic graph (DAG) as the scheduler for it. Instead of a linear ordering, this graph give us the ability to create multiple branches of dependencies.

[GitHub/hn-data-pipeline](https://github.com/cadovid/hn-data-pipeline)
