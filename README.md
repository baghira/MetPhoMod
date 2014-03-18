MetPhoMod
=========
MetPhoMod the METeorogy and atmospheric PHOtochemstry mesoscale MODel. A prognostic three-dimensional Eulerian model for the simulation of summer smog was implemented which fully couples meteorological processes and gas phase chemistry. The model includes modules for atmospheric dynamics, atmospheric turbulence, transport, gas-phase chemistry, short- and long-wave radiation transfer, and surface interactions, including emission and deposition of trace gases. (see http://link.springer.com/content/pdf/10.1007%2Fs007030050024.pdf) 

Installing on Debian / Ubuntu
=============================

    $ sudo apt-get install fort77 xutils-dev libc-dev pvm-dev bison \
        libnetcdf-dev flex
    $ make depend
    $ make
