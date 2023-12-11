## docker-tutorial

[![Maintainability](https://api.codeclimate.com/v1/badges/48b3fe5ffb7e9dd9ffe6/maintainability)](https://codeclimate.com/github/coronarita/docker-tutorial/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/48b3fe5ffb7e9dd9ffe6/test_coverage)](https://codeclimate.com/github/coronarita/docker-tutorial/test_coverage)

## How to run main.py?

```sh
# example port number : 8000

$ export PORT=8000 
$ python lesson2/main.py
```

## How to run test code?
```sh
$ pytest --cov-config=.coveragerc --cov=. lesson2 --cov-report xml --cov-report term-missing:skip-covered
```