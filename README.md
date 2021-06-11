# TactileSensorUI

## Overview

Tactile Sensors' User Interface using Qt5.

Visit [AB-Sens](https://ab-sens.com) for more information about the sensors.

### License

The source code is released under a [GPL-3.0 license](TactileSensorUI/LICENSE).

**Author: Shahbaz Youssefi<br />
Maintainer: Alexandre Bernier, alexandre@ab-sens.com<br />
Affiliation: [AB-Sens](http://ab-sens.com)**

The TactileSensorUI software has been tested on Ubuntu 20.04 with Qt 5.15.

## Installation

### Building from Source

#### Dependencies

You need to install Qt in order to build this project from source. I recommend installing [Qt Creator](https://www.qt.io/download-qt-installer) with the latest version of Qt5.

You also need to install the following debian packages before trying to build this project:
  
    sudo apt install build-essential mesa-common-dev libmgl-dev libfftw3-dev
    
**If QtCreator looks like it doesn't launch, try installation the following library:**

    sudo apt install libxcb-xinerama0

#### Building

To build from source, first launch QtCreator and open this project's .pro file. QtCreator will ask you to setup the project. Once completed, you should be able to build the project without any errors.

### Usage

To run the TactileSensorUI, simply run the project from QtCreator.

## Bugs & Feature Requests

Please report bugs and request features using the [Issue Tracker](https://github.com/alexandre-bernier/TactileSensorUI/issues).
