# BIOMD0000000345: Koschorreck2008_InsulinClearance

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000345.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000345.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000345 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Mathematical modeling and analysis of insulin clearance in vivo. **   
Koschorreck M, Gilles ED. _BMC Syst Biol._ 2008 May 13;2:43. [
18477391](http://www.ncbi.nlm.nih.gov/pubmed/18477391),  
**Abstract:**   
BACKGROUND: Analyzing the dynamics of insulin concentration in the blood is
necessary for a comprehensive understanding of the effects of insulin in vivo.
Insulin removal from the blood has been addressed in many studies. The results
are highly variable with respect to insulin clearance and the relative
contributions of hepatic and renal insulin degradation. RESULTS: We present a
dynamic mathematical model of insulin concentration in the blood and of
insulin receptor activation in hepatocytes. The model describes renal and
hepatic insulin degradation, pancreatic insulin secretion and nonspecific
insulin binding in the liver. Hepatic insulin receptor activation by insulin
binding, receptor internalization and autophosphorylation is explicitly
included in the model. We present a detailed mathematical analysis of insulin
degradation and insulin clearance. Stationary model analysis shows that
degradation rates, relative contributions of the different tissues to total
insulin degradation and insulin clearance highly depend on the insulin
concentration. CONCLUSION: This study provides a detailed dynamic model of
insulin concentration in the blood and of insulin receptor activation in
hepatocytes. Experimental data sets from literature are used for the model
validation. We show that essential dynamic and stationary characteristics of
insulin degradation are nonlinear and depend on the actual insulin
concentration.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


