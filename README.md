# MODEL1111190000: MODEL1111190000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1111190000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1111190000.git@20140916`

## Usage

Importing the model package.

`import MODEL1111190000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A genome-scale metabolic model of the lipid-accumulating yeast Yarrowia lipolytica**   
Nicolas Loira, Thierry Dulermo, Jean-Marc Nicaud and David J Sherman _BMC
Systems Biology_ 2012, 6:35 doi:
[10.1186/1752-0509-6-35](http://dx.doi.org/10.1186/1752-0509-6-35) ,  
**Abstract:**   
Background Yarrowia lipolytica is an oleaginous yeast which has emerged as an
important microorganism for several biotechnological processes, such as the
production of organic acids, lipases and proteases. It is also considered a
good candidate for single-cell oil production. Although some of its metabolic
pathways are well studied, its metabolic engineering is hindered by the lack
of a genome-scale model that integrates the current knowledge about its
metabolism. Results Combining in silico tools and expert manual curation, we
have produced an accurate genome-scale metabolic model for Y. lipolytica.
Using a scaffold derived from a functional metabolic model of the well-studied
but phylogenetically distant yeast S. cerevisiae, we mapped conserved
reactions, rewrote gene associations, added species-specific reactions and
inflected specialized copies of scaffold reactions to account for species-
specific expansion of protein families. We used physiological measures
obtained under lab conditions to validate our predictions. Conclusions Y.
lipolytica iNL895represents the first well-annotated metabolic model of an
oleaginous yeast, providing a reference for future metabolic improvement, and
a starting point for the metabolic reconstruction of other species in the
Yarrowia clade and other oleaginous yeasts.

**Note:** This SBML representation of the Yarrowia lipolytica metabolic network is made available under the Creative Commons Attribution-Share Alike 3.0 Unported Licence (see www.creativecommons.org). 

Nicolas Loira (loira@inria.fr, nloira@gmail.com); based on S.cerevisiae model
yeast_4.36.xml (Herrgard, 2008)


