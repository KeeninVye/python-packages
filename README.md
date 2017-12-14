# Python Packages
Repo of description of python packages and simple examples on how to use them.


## Argparse
The [argparse](https://docs.python.org/3/library/argparse.html) module makes it easy to write user-friendly command-line interfaces.
```python
import argparse
parser = argparse.ArgumentParser()
parser.add_argument("-s", "--string", type=str, help="String or path.")
parser.add_argument("-i", "--integer", type=int, help="Integer.")
parser.add_argument("-f", "--flag", action="store_true")
args = parser.parse_args()
```

## Requests
[Requests](https://docs.python.org/3/library/requests.html) is the only Non-GMO HTTP library for Python, safe for human consumption.
```python
import requests
r = requests.get('https://api.github.com/user', auth=('user', 'pass'), params={'key1': 'value1', 'key2': 'value2'})
r.json()
r.text
```

