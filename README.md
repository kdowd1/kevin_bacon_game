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

## Project Status
Project is: _in progress_ / _no longer being worked on_. 
I cannot tell if the project is salvagable. So right now I am taking a pause, but most definetly determined to figure out what went wrong.


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
