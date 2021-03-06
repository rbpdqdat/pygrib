Python module for reading and writing GRIB files (edition 1 and edition 2).

GRIB is the World Meteorological Organization (WMO) standard
file format for the exchange of weather data.

Provides a interfaces for the ECWMF GRIB_API C library and
the NCEP grib2 C library, including 
command line utilities for listing (grib_list) and repacking (grib_repack)
GRIB files.

Quickstart:

* Clone the github repository, or download a source release from https://pypi.python.org/pypi/pygrib.

* Copy setup.cfg.template to setup.cfg, open in text editor, follow instructions in
comments for editing.

* Run 'python setup.py build'

* Run 'python setup.py install' (with sudo if necessary)

* Run 'python test.py' to test your pygrib installation.

For full installation instructions and API documentation, see https://jswhit.github.io/pygrib.

Questions or comments - contact Jeff Whitaker <jeffrey.s.whitaker@noaa.gov>
or use https://github.com/jswhit/pygrib/issues.
