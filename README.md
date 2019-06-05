# Py-lapse

Simple timelapses from serial .png images.

### Prerequisites

This version of py-lapse was written for Python 3.6 and higher. It uses the opencv-python library as well as several built in libraries.

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
* -w - video width
* -l - video height
* -f - frames per second
* -n - video name
* -g - gamma (>1.0 brightens)
