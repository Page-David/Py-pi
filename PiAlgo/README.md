# Py-pi
### Clculate pi to thousands of digits with Python
This project is aim to analye bunch of algorithms for thousands of digits of pi using Python. Also the `main.py` is able to test other algorithms if you like.

## Example output
Time analyse

<img src="https://cdn.rawgit.com/Page-David/PiPy/13d96001/time.svg"/>
So far Gauss Legendre method wins.

Accurancy analyse

<img src="https://cdn.rawgit.com/Page-David/PiPy/13d96001/accurancy.svg"/>
Basicly, every algorithm used output right answer.

## Dependence
Python 2.7

[Sagemath](www.sagemath.org) used for generate data figure

mpmath avaliable on pip: `pip install mpmath` used in reverse tan algo

## Usage
clone the project and run `./main [digits]` for example `./main 1000`

## FAQ
Why Python?

Some people asked why Python is used, why not a language able to compiled?

First of all, effiency and fast are quite different word. The aim of this project is to analyse different algorithms, but not to calculate more digits ASAP. Also, Python is more easier to get algorithms to work as there are many modules like `mpmath`.

## Contribution or feedback
Just send an issue or pull request.

