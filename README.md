# The Oracle of Kevin Bacon - code edition
> For my project idea I was wanting to create a visualisation using Gephi of the 6 degrees of Kevin Bacon. The game's name is a reference to "six degrees of separation" phenomenon, a concept that posits that any two people on Earth are six or fewer acquaintance links apart. I will be visualising this using Hollywood actors. 

> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)


## General Information
- In order to create a web of celebrities that connect to Kevin Bacon I attempted to use python with networkx to make the process easier after seeing it done in another repository. After running into problems due to my limited code literacy I have had to rely on gephi to visulise my code. 
- My project aims to debunk the theory of seperation. Although left incomplete I was successfully able to apply theoretical information and strengthen my literacy.


## Technologies Used
- Kaggle - version 2.0 for access to data sets
- Python 3 and NetworkX
- Gephi - version 3.0c for visualising 


## Features
List the ready features here:
- Awesome feature 1
- Awesome feature 2
- Awesome feature 3


## Setup
What are the project requirements/dependencies? Where are they listed? A requirements.txt or a Pipfile.lock file perhaps? Where is it located?

Proceed to describe how to install / setup one's local environment / get started with the project.
Firstly I began with Python 3 using CloudStor Swan, after then pip installing Network X 1.10 I imported the data set 'TMBd 5000 Movie Dataset' from Kaggle. After having this in place and manipulating the data to draw a relationship with actors and Kevin Bacon I began to trial how NetworkX could visualise the code by realising the shortest path between Bacon and a random sample of actors. I ran into problems having such a large data set. Despite trying to create limitations and playing around with the langauge as advised by sites such as stackoverflow and geeksforgeeks. Despite asking some friends studying computer engineering, changing to an updated verison of Networkx, I had no luck. So in the end I manually inputted as much data as I could into Gephi so that I could have atleast something to show for my efforts.

## Usage
How does one go about using it?
Provide various use cases and code examples here.

import pandas as pd
import ast  # fantastic package (https://docs.python.org/3/library/ast.html)
import networkx as nx
import random
import matplotlib.pyplot as plt

%matplotlib inline

df = pd.read_csv('tmdb_5000_credits.csv')
df['cast'] = df.cast.apply(ast.literal_eval)
df.head()

df['has_bacon'] = df.cast.apply(lambda c: bool([y for y in c if y['name']=='Kevin Bacon']))
df.head()

df[df.has_bacon]

G = nx.Graph()
added_actor = []

def add_movie_and_actors_to_graph(row):
    G.add_node(row.title, {'type': 'movie', 'color': 'blue'})
    for actor in row.cast:
        if actor['name'] not in added_actor:
            G.add_node(actor['name'], {'type': 'actor', 'color': 'red' if actor['name']=='Kevin Bacon' else 'green'})
            added_actor.append(actor['name'])
        G.add_edge(row.title, actor['name'])


_ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
Cell In [306], line 13
      9             added_actor.append(actor['name'])
     10         G.add_edge(row.title, actor['name'])
---> 13 _ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)

File /usr/local/cloudstor/python/pre/pandas/core/frame.py:8848, in DataFrame.apply(self, func, axis, raw, result_type, args, **kwargs)
   8837 from pandas.core.apply import frame_apply
   8839 op = frame_apply(
   8840     self,
   8841     func=func,
   (...)
   8846     kwargs=kwargs,
   8847 )
-> 8848 return op.apply().__finalize__(self, method="apply")

File /usr/local/cloudstor/python/pre/pandas/core/apply.py:733, in FrameApply.apply(self)
    730 elif self.raw:
    731     return self.apply_raw()
--> 733 return self.apply_standard()

File /usr/local/cloudstor/python/pre/pandas/core/apply.py:857, in FrameApply.apply_standard(self)
    856 def apply_standard(self):
--> 857     results, res_index = self.apply_series_generator()
    859     # wrap results
    860     return self.wrap_results(results, res_index)

File /usr/local/cloudstor/python/pre/pandas/core/apply.py:873, in FrameApply.apply_series_generator(self)
    870 with option_context("mode.chained_assignment", None):
    871     for i, v in enumerate(series_gen):
    872         # ignore SettingWithCopy here in case the user mutates
--> 873         results[i] = self.f(v)
    874         if isinstance(results[i], ABCSeries):
    875             # If we have a view on v, we need to make a copy because
    876             #  series_generator will swap out the underlying data
    877             results[i] = results[i].copy(deep=False)

Cell In [306], line 13, in <lambda>(r)
      9             added_actor.append(actor['name'])
     10         G.add_edge(row.title, actor['name'])
---> 13 _ = df.apply(lambda r: add_movie_and_actors_to_graph(r), axis=1)

Cell In [306], line 5, in add_movie_and_actors_to_graph(row)
      4 def add_movie_and_actors_to_graph(row):
----> 5     G.add_node(row.title, {'type': 'movie', 'color': 'blue'})
      6     for actor in row.cast:
      7         if actor['name'] not in added_actor:

TypeError: add_node() takes 2 positional arguments but 3 were given
random_actors = random.sample(added_actor, 5)
random_actors
---------------------------------------------------------------------------
ValueError                                Traceback (most recent call last)
Cell In [307], line 1
----> 1 random_actors = random.sample(added_actor, 5)
      2 random_actors

File /cvmfs/sft.cern.ch/lcg/releases/Python/3.9.12-9a1bc/x86_64-centos7-gcc8-opt/lib/python3.9/random.py:449, in Random.sample(self, population, k, counts)
    447 randbelow = self._randbelow
    448 if not 0 <= k <= n:
--> 449     raise ValueError("Sample larger than population or is negative")
    450 result = [None] * k
    451 setsize = 21        # size of a small set minus size of an empty list

ValueError: Sample larger than population or is negative

## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.


## Room for Improvement
As you can see my last two commands have many value errors that I am still unsure how to fix. 
Room for improvement:
- Having a smaller datase

To do:
- Grow profiency in python, networkx and gephi

## Acknowledgements
- This project was inspired by the exsisting theory surrounding Kevin Bacon
- This project was based on https://oracleofbacon.org/ and https://github.com/brad-do/charts
- Many thanks to Nick and Cameron for trying to help me code and my tutor Andrew for being supportive
