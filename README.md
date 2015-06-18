Bib2Web
-------
-------

The bib2web/bibtexparser is the following package: https://github.com/sciunto/python-bibtexparser.  
I just made a small alteration, it now ignores lines syartin with '%' and '//'. Which are comments in BibTeX.

Installation:
------------

### Install Dropbox:
Install Dropbox using https://www.dropbox.com/install?os=lnx

### Install dependencies:

    sudo apt-get install python-pip build-essential python-tk python-levenshtein

### Install package:
The package is installed using this command:

    sudo pip install bib2web
All the needed dependencies from pip are installed

Running the app:
---------------

### Make alias:

    alias bib2web='python /usr/local/lib/python2.7/dist-packages/bib2web'
    
### Run the app:

    bib2web path/to/settings.conf

There is an example configuration file in the repository (example_config.conf)
Caution: Use absolute paths in the config!

