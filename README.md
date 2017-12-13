# python-packages
Repo of description of python packages and simple examples on how to use them.


##Argparse
The [argparse](https://docs.python.org/3/library/argparse.html) module makes it easy to write user-friendly command-line interfaces.
```python
parser = argparse.ArgumentParser()
parser.add_argument("-c", "--config", type=str, help="Path to the configuration file.")
args = parser.parse_args()
```
