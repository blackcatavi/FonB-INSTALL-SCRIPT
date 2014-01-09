This Python script can download and install PhoneB and required dependencies.

Usage
------
`python fonb-install.py -i`


Options
-------

  -h, --help            show this help message and exit
  -i, --install         Download and install FonB
  -s /path/to/PhoneB/bin, --init=/path/to/PhoneB/bin
                        Outputs init.d script. This option expects path to bin
                        folder of phoneb installation to be passed as argument
  -p php-cgi, --php=php-cgi
                        Validates php requirements for FonB. Expects php-cgi
                        path as argument.
  -c /path/where/php/will/be/compiled, --prefix=/path/where/php/will/be/compiled
                        Downloads and compiles php with FonB specific
                        requirements.
  -v, --version         Show installation script version
  -f, --freepbx         Install Freepbx module


Requirements
------
- Python 2.x (Tested on Python 2.4, 2.5, 2.6 and 2.7)
- CentOS (Freepbx/Elastix/Stock Asterisks) (Recommended) 
- Should run on any linux installation with yum. Installation will go smooth in other linux distroes too, but you will have to resolve dependencies on your own)
- Internet connectivity
