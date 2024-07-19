# Youtube Challenge - Python

The Python Youtube Challenge uses Python3.
The below commands use Python3 specifically, to account for users that might
have Python2 installed alongside Python3.

NOTE: **Please do not edit videos.txt as it will cause tests to break. There is no need to modify this file to complete this challenge.**

## Installing Python and pytest

[This guide](https://realpython.com/installing-python/) explains how to check if you already
have Python installed, and if not, how to install it on your machine.
Please make sure you install Python 3.7 or higher.

The tests are using `pytest`, if you don't have `pytest` installed yet, you can do so by running:

```shell script
python3 -m pip install pytest
```

pip should be installed already if you installed Python from the official source. If not, you
can find many guides online on how to install pip for your operating system.

## Setting up

You can write code in any editor you'd like. However, different editors have
different ways of dealing with Python code, so in case of doubt we recommend
you run the code and tests from the command line as shown below.

## Running and testing from the Commandline

To run the command-line application:

```shell script
python3 -m src.run
```

You can close the app by typing `EXIT` as a command.

#### Running the tests

To run all the tests:

```shell script
python3 -m pytest
```

For more verbose test output you can use

```shell script
python3 -m pytest -v
```

```shell script
python3 -m pytest test/part1_test.py
python3 -m pytest test/part2_test.py
python3 -m pytest test/part3_test.py
python3 -m pytest test/part4_test.py
```

For more information on pytest commandline options, such as only running a specific test,
you can read more [here](https://docs.pytest.org/en/6.2.x/usage.html#).
