---
layout: post
title: "Production and large databases projects"
date: 2020-01-01
excerpt: "A few web database personal projects with educational purpose."
project: true
tags: [database, sql, python, memory, optimization, pipeline]
comments: false
---

This section shows some of the projects I have done as a result of my learning process or hobby. All these exercises are for purely educational purposes.

<br>

***

## Production and large databases

***

<br>

1. **Building a database with PostgreSQL in Python for crime reports in Boston**

    In this project, a simple database is created using PostgreSQL inside a Python environment. For this purpose, the package `psycopg2` is essencial as a PostgreSQL database adapter for the Python programming language.

    <div markdown="0"><a href="https://github.com/cadovid/crime-reports" class="btn">GitHub/crime-reports</a></div>

2. **Optimizing dataframes' memory usage and processing in chunks**

    This project demonstrates how to optimise the memory footprint of a dataframe and how to work with dataframe chunks. All these steps make it possible to work with dataframes that, a priori, do not fit within the memory limits of a given storage.

    <div markdown="0"><a href="https://github.com/cadovid/loans-optimization" class="btn">GitHub/loans-optimization</a></div>

3. **Analyzing wikipedia pages using MapReduce techniques (parallel processing)**

    In this project a grep-like algorithm is implemented in Python by using MapReduce techniques (parallel processing) for a given dataset. The main functionality of this algorithm is to search the specific location of a target string inside all of the dataset files.

    <div markdown="0"><a href="https://github.com/cadovid/wikipedia-parallel" class="btn">GitHub/wikipedia-parallel</a></div>

4. **Building a key-value store database through a complex tree data structure**

    In this project, a B-tree data structure is implemented from scratch as a building block for a fully functioning key-value store. This key-value store will work like a Python dictionary, but it will also allow users to perform range queries, similar to multiple implementations of the key-value store used in production-grade systems worldwide, like Redis, CouchDB, Mongo, or Cassandra. In this way, these queries are performed in a more efficient computation time than in a simpler implementation.

    <div markdown="0"><a href="https://github.com/cadovid/key-value-tree-database" class="btn">GitHub/key-value-tree-database</a></div>

5. **Building a data pipeline class**

    In this project, a data pipeline class that schedules the tasks in the correct order is constructed in Python from scratch. This class will be built around a directed acyclic graph (DAG) as the scheduler for it. Instead of a linear ordering, this graph give us the ability to create multiple branches of dependencies.

    <div markdown="0"><a href="https://github.com/cadovid/hn-data-pipeline" class="btn">GitHub/hn-data-pipeline</a></div>
