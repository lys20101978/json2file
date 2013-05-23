json2file
=========

Usage
-----

Install requirements::

    pip install -r requirements.txt

Download json files from following urls::

    http://api.goideas.org/v1/helios/publication/?flat
    http://api.goideas.org/v1/helios/patent/?flat
    http://api.goideas.org/v1/helios/grant/?flat

    Assume you save a file named testdata.json

Run the covert::

    python convert.py

Then you can see the result file
