# Installing

## Dependencies
Linux: libsdl1.2, python-dev

Python:
```
pip install -U cffi
pip install libtcod-cffi
pip install tdl
pip install flask
pip install flask-compress
git clone git@github.com:DerPferd/little-python.git lp
cd lp
pip install .
```

## Setup
Clone this repo and add the path to the repo to your path variable.

Ex. export PYTHONPATH=$PYTHONPATH:/path/to/add/CYLGameServer

## Serve a game
Find a game repo and clone it then run:
```
python game.py serve
```

# TODO
 - Figure out how to do sensors.
 - Add real time playing from web.
