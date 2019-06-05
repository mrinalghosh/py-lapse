# py-lapse

Simple timelapses from .png images.

### Prerequisites

This version of py-lapse was written for Python 3.6 and higher. It uses opencv-python as well as the built in numpy, os and argparse libraries.

Get and install OpenCV:
```sh
pip install opencv-python
```

### API

Load directory of images and return video:
```sh
python py-lapse.py -arguments
```

Supported arguments:
* -w (pixel video width)
* -l (pixel video height)
* -f (frames per second)
* -n (video name)
* -g (gamma - above 1.0 brightens)
