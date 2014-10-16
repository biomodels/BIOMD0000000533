# BIOMD0000000533: MODEL1407300001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000533.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000533.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000533 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Steckmann2012 - Amyloid beta-protein fibrillogenesis (kinetics of secondary
structure conversion)

This model is described in the article:

[Kinetics of peptide secondary structure conversion during amyloid ?-protein
fibrillogenesis.](http://identifiers.org/pubmed/22586726)

Steckmann T, Awan Z, Gerstman BS, Chapagain PP.

J. Theor. Biol. 2012 May; 301: 95-102

Abstract:

Amyloid fibrils are a common component in many debilitating human neurological
diseases such as Alzheimer's (AD), Parkinson's, and Creutzfeldt-Jakob, and in
animal diseases such as BSE. The role of fibrillar ?? proteins in AD has
stimulated interest in the kinetics of ?? fibril formation. Kinetic models
that include reaction pathways and rate parameters for the various stages of
the process can be helpful towards understanding the dynamics on a molecular
level. Based upon experimental data, we have developed a mathematical model
for the reaction pathways and determined rate parameters for peptide secondary
structural conversion and aggregation during the entire fibrillogenesis
process from random coil to mature fibrils, including the molecular species
that accelerate the conversions. The model and the rate parameters include
different molecular structural stages in the nucleation and polymerization
processes and the numerical solutions yield graphs of concentrations of
different molecular species versus time that are in close agreement with
experimental results. The model also allows for the calculation of the time-
dependent increase in aggregate size. The calculated results agree well with
experimental results, and allow differences in experimental conditions to be
included in the calculations. The specific steps of the model and the rate
constants that are determined by fitting to experimental data provide insight
on the molecular species involved in the fibril formation process.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000533](http://identifiers.org/biomodels.db/BIOMD0000000533).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


