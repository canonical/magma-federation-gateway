# Contributing/Hacking

Testing for each charm is done the same way. First `cd` into the charm directory and then use 
`tox` like so:

```shell
tox -e lint      # code style
tox -e static    # static analysis
tox -e unit      # unit tests
tox -e integration
```

**NOTE:** If you don't have `tox` installed yet, just run: `pip3 install tox`.

Tox creates virtual environment for every tox environment defined in
[tox.ini](tox.ini). Create and activate a virtualenv with the development requirements:

```bash
source .tox/unit/bin/activate
```
