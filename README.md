# mfpypkg

This is a collection of python utilities. Nothing particularly fancy, but maybe useuful to someone. 
Please, report bug/suggestions/etc to michele.fumagalli@durham.ac.uk
Also, make sure you check out the relevant readme in each package.

Michele Fumagalli, 2015
michele.fumagalli@durham.ac.uk

*** mfpy_fitsrgb.py ***

    This is a rather simple code that takes a list of x/y positions 
    and generates RGB images with three color stretches. 

    Usage:
    -----

    For default usage, just provide a X/Y formatted list of positions
    and fits images for the three channels.

    python clusters_rgb list.xy Bchannel.fits Gchannel.fits Rchannel.fits

    Dependencies:
    -------------

    Requires the following packages: 
    sys, argparse, numpy, astropy, os, matplotlib

