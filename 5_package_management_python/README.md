# Example Package

hello-world
|---hello world
    |---__init__.py
    |---main.py

# Virtual Environments

```
virtualenv hellodemo
source hellodemo/bin/activate
pip install setuptools twine
python setup.py sdist
twine upload --repository-url https://test.pypi.org/legacy/ \
  dist/hello_world_akjshya-0.0.1.tar.gz
```