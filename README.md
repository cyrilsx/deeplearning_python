# deeplearning_python

## Getting Started  
Jupyter notebooks are great to experiment using data science.

Google provides Colab that allows to start right away: https://colab.research.google.com/

Else, you can also install Jupyter notebooks on your machine. Be sure to [python3](https://www.python.org/) installed.
I personally used [venv](https://docs.python.org/3/library/venv.html) to have a better control of the installed package.

````bash
$ apt install python3.10-venv
$ mkdir -p $where_you_want/deep_learning
$ source $where_you_want/deep_learning/bin/activate
```

Right now, you are in a lightweight python environment. We can install our notebook and others dependencies required to play with deeplearning.

````bash
(deep_learning)$ pip install jupyterlab
(deep_learning)$ pip install tensorflow 
```

To start Jupyter lab in order to create notebooks, just launch `jupyter lab` in the command line and go to [http://localhost:8888](http://localhost:8888/lab/) with the specified token.
