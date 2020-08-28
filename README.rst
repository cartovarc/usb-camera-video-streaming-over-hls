===================================
usb-camera-video-streaming-over-hls
===================================

USB camera video streaming over HLS

* Free software: MIT license

Dependencies
------------

Gstreamer
~~~~~~~~~
* https://pygobject.readthedocs.io/en/latest/getting_started.html#ubuntu-logo-ubuntu-debian-logo-debian
* https://gstreamer.freedesktop.org/documentation/installing/on-linux.html?gi-language=c#install-gstreamer-on-fedora

.. code:: bash

    $ sudo apt-get update
    $ sudo apt install -y libgirepository1.0-dev gcc libcairo2-dev pkg-config python3-dev gir1.2-gtk-3.0 
    $ sudo apt-get install -y libgstreamer1.0-0 gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav gstreamer1.0-doc gstreamer1.0-tools gstreamer1.0-x gstreamer1.0-alsa gstreamer1.0-gl gstreamer1.0-gtk3 gstreamer1.0-pulseaudio

Install PyPI requirments
~~~~~~~~~~~~~~~~~~~~~~~~

.. code:: bash

    $ pip install -r requirements.txt


Usage
-----

.. code:: bash

    $ python main.py

Then go to http://127.0.0.1:5001
