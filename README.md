# naive-stopwords

![Python package](https://github.com/naivenlp/naive-stopwords/workflows/Python%20package/badge.svg)
[![PyPI version](https://badge.fury.io/py/naive-stopwords.svg)](https://badge.fury.io/py/naive-stopwords)
[![Python](https://img.shields.io/pypi/pyversions/naive-stopwords.svg?style=plastic)](https://badge.fury.io/py/naive-stopwords)

Stop words for Chinese.


## Installation

```bash
pip install -U naive-stopwords
```

## Usage

```python
from naive_stopwords import Stopwords

sw = Stopwords()

print(sw.size())
print(sw.contains('hello'))

sw.add('的')
print(sw.size())
print(sw.contains('的'))

sw.remove('的')
print(sw.size())
print(sw.contains('的'))

```
