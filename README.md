# BIOMD0000000084: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000084.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000084.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000084 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS
Online](http://bioinformatics.oupjournals.org/cgi/content/abstract/20/13/2143)
, Bioinformatics, 20:2143-2144 **

_Biomodels Curation_ The model reproduces the time series depicted in Fig 2 of
the paper. Also, by varying the values of Vmax for the second kinase (k5) the
time series of X3P as shown in Fig3 can be reproduced. The model was
successfully tested on MathSBML and Jarnac.


