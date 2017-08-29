# README

## Install ##
This app relies on the *web2py* framework, which can be [downloaded here](http://web2py.com/init/default/download) and is [documented here](http://web2py.com/book).

In the shell the installation instructions are as follows:
```
#!bash

    # first download web2py
    wget http://www.web2py.com/examples/static/web2py_src.zip
    unzip web2py_src.zip
    # now download the app
    cd web2py/applications
    git clone git@github.com:lbias/places.git
    # now start the web2py server with a password for the admin interface
    cd ..
    python web2py.py --password=<password>

```

The places app can now be accessed in your web browser at [http://127.0.0.1:8000/places]([http://127.0.0.1:8000/places).
