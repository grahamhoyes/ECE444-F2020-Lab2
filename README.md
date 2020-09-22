# ECE444 F2020 Lab 2
Lab 2 for ECE444: Hello World with Flask.

This repo is adapted from https://github.com/miguelgrinberg/flasky.

## Activity 1: Installation
![image](https://user-images.githubusercontent.com/26036279/93943301-3c32a200-fd00-11ea-9af6-8702a7d5d414.png)
- Environment `ece444-flask` created with conda

## Activity 2: Hello World
![image](https://user-images.githubusercontent.com/26036279/93944797-a7ca3e80-fd03-11ea-8d12-47aa77e0292e.png)

## Activity 3: Flask Context Globals
Flask context globals are objects that act as global imports (i.e. `from flask import request`), but that contain information relevant to only the current request or application, and are not shared between threads. They allow view functions to access the HTTP request, session, etc. data without having to add positional or keyword arguments to all view functions.