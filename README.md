[![](https://img.shields.io/pypi/pyversions/public.svg?longCache=True)](https://pypi.org/pypi/public/)
[![](https://img.shields.io/pypi/v/public.svg?maxAge=3600)](https://pypi.org/pypi/public/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/public.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/public.py/)

### Install
```bash
$ [sudo] pip install public
```

### Examples
```python
>>> from public import public

>>> @public
	def func(): pass

>>> @public
	class CLS: pass

>>> print(__all__)
['CLS',func']

# public(*objects) function
>>> public("name")
>>> public("name1","name2")

>>> print(__all__)
['name','name1','name2']
```

### Sources
+   [`public.public(*objects)`](https://github.com/looking-for-a-job/public.py/blob/master/public/__init__.py)