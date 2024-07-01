---
title: Machine Learnign and Constrained Optimization (Part 1)
author: michele.lombardi2@unibo.it
---

# Accessing the Lecture #

## Local Execution (Preferred) ##

Students are strongly encouraged to _run all lectures locally_. Doing this will require to:


* Clone the repository with the tutorial, in this case via the command:
```sh
git clone https://github.com/ml-co-2024/part-1.git
```
* Installing a compatible version of the Python interpreter and all the required dependencies, possibly via a virtual environment
  - The best way to do this is by installing [pyenv](https://github.com/pyenv/pyenv) and [poetry](https://python-poetry.org)
  - `pyenv` is a tool that enable switching between multiple Python versions
  - `poetry` is a package and dependency manager that can greatly simply working with virtual environments
  - If you don't wish to use `poetry`, you can find all the lecture dependencies listed in the `pyproject.toml` file; you can then proceed to install them using any approach of your choice

## Read-only Access and PDF Notes ##

You can inspect the individual notebooks in by just clicking on any `*.ipynb` file in the `notebooks` directory: github provides a notebook viewer that mostly works, though this access method may occasionally have issue when displaying plots.

The repository contains PDF notes for all the notebooks. They can be used for read-only access (with more consistent results compared to the github notebook viewer), but more importantly they can be useful to add annotations. Just keep in mind that in case of updates, cloning the repository will replace the PDF files.
