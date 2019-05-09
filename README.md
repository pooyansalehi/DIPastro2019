# Digital Image Processing 2019

## Purpose

This repository contains the exercises for the course [Digital Image Processing in Astronomy](http://theosolid.qipc.org/KomVV_SS2019.pdf) in the summer semester 2019 of University of Potsdam (Germany). The exercises will be released biweekly. To attend the course it is necessary to sign up in the course [Moodle](https://moodle2.uni-potsdam.de).


## Setup

In order to setup the repository and the exercises a working Anaconda is necessary. The instructions for the installation of Anaconda for the operating system of your choice can be found [here](https://www.anaconda.com/distribution/)

Afterwards, clone this repository by either using `git clone git@github.com:adiercke/DIPastro2019.git` or by downloading a zip-snapshot from [github.com/adiercke/DIPastro2019](https://github.com/adiercke/DIPastro2019).

Next, go into the directory and execute `conda env create -f environment.yml` in order to obtain an environment which will contain all the right versions and dependencies for this course. Unless the environment will be updated, you do not need to execute this again. Then type `conda activate dip2019` followed by `jupyter notebook .` . Navigate to the exercise folder, open the notebook and start hacking away.


## Update: 10/05/2019

1. Rename your personal lab1.ipynb in the repository
2. Use `git pull` to update the repository
3. The environment file was updated. Update your python environment with `conda env update -f=environment.yml`
4. Create a renamed copy of lab2.ipynb and solve the exercises in the copy
