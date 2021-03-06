Contains python scripts for getting American Ultimate Disc League (AUDL) statistics information from the www.ultianalytics.com server.

Use
--------------

clone the repository using 

git clone https://github.com/pshriwise/audl_server

in the top directory run the commands:

python server.py -h

This shows all options for running an AUDL stat server instance.

Documentation
--------------

In order to produce documentation for this application:

cd docs/

doxygen Doxyfile

To view the documentation via html:

open ./docs/html/index.html in your favorite browser


Testing
-------

To run tests for the AUDL server:

cd tests/

nosetests

Note: An internet connection is currently required to run the tests!

Dependencies
-------------

Python version 2.7.3 or greater 

Python modules: urllib2, json , feedparser, datetime, SimpleHTTPServer
                SocketServer, matplotlib, tzlocal, apns, csv, traceback,
		threading, apns, subprocess, urlparse, boto (Amazon's aws python package)

