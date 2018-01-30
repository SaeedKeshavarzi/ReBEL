#          ReBEL : Recursive Bayesian Estimation Library

A Matlab toolkit for Recursive Bayesian Estimation

Copyright 2006, Oregon Health and Science University


## 1) WHAT IS ReBEL ?

ReBEL is a Matlab� toolkit of functions and scripts, designed to
facilitate sequential Bayesian inference (estimation) in general state
space models. This software consolidates research on new methods for
recursive Bayesian estimation and Kalman filtering by Rudolph van der
Merwe and Eric A. Wan. The code is developed and maintained by Rudolph
van der Merwe at the OGI School of Science & Engineering at OHSU
(Oregon Health & Science University). 

ReBEL is a 'work in progress' and currently contains most of the
following functional units which can be used for state-, parameter-
and joint-estimation: 

    * Kalman filter
    * Extended Kalman filter
    * Sigma-Point Kalman filters (SPKF)
          o Unscented Kalman filter (UKF)
          o Central difference Kalman filter (CDKF)
          o Square-root SPKFs (SRUKF, SRCDKF)
          o Gaussian mixture SPKFs  (not implemented yet)
    * Particle filters
          o Generic particle filter
          o Sigma-Point particle filter
          o Gaussian sum particle filter
          o Gaussian mixture sigma-point particle filter (beta)
          o Auxiliary sigma-point particle filter (alpha)

The code is designed to be as general, modular and extensible as
possible, while at the same time trying to be as computationally
efficient as possible. It has been tested with Matlab 7.2 (R2006a). 


## 2) INSTALLATION

Unpack the ReBEL distribution archive using either 'tar -xzvf
ReBEL-X.Y.Z.tar.gz' under Unix or unzip the ReBEL-X.Y.Z.zip archive under
Windows. This will create the 'ReBEL-X.Y.Z' directory tree in the current
directory. 


## 3) UPDATE MATLABPATH : Add 'core' and 'netlab' directories

Make sure the 'ReBEL-X.Y.Z/core/' subdirectory is in the Matlab
path by either setting the MATLABPATH environment variable accordingly
or using the 'path' command from the Matlab command line.

(X = major release number , Y = minor release number , Z = buxfix version
number)

In order to use the bundled Netlab neural network toolkit, also add
the 'ReBEL-X.Y.Z/netlab/' subdirectory to your MATLABPATH. This is needed
to use any of the GMM based particle filter and hybrid algorithms.


## 4) DOCUMENTATION

Since ReBEL is an constantly 'evolving' research tool used in the
Machine Learning and Signal Processing Group ( http://choosh.csee.ogi.edu/index.html
), the documentation usually lags behind a bit. For the most up to date
documentation, refer to the online documentation section of the ReBEL
project website (see below). A small 'Quick start Guide' is also
provided. This together with the (hopefully) well documented code 
examples in the 'examples' subdirectory will serve as the initial
minimal set of documentation for the alpha release of ReBEL.

The unofficial accompanying "text" to ReBEL are Chapters 5 and 7 of
"Kalman Filtering and Neural Networks" edited by Simon Haykin and
published by Wiley. These cover dual extended Kalman filter methods
and the Unscented Kalman Filter in great detail. Other algorithms
included in ReBEL are also covered in the rest of the book. See the
ReBEL website for more detail.


## 5) WEBSITE

For latest information and online documentation, always visit
the project website at http://choosh.csee.ogi.edu/rebel/ 


## 6) MAILING LIST AND USER DISCUSSION BOARD

There is a discussion group for users and developers of ReBEL hosted
at Yahoo Groups. Here is the URL:

http://groups.yahoo.com/group/rebel_toolkit/


-----------------------------------------------------------------------
This document was last modified on : September 5th, 2006.
