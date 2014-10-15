# BIOMD0000000251: Nakakuki2010_CellFateDecision_Core

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000251.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000251.git@20140916`


# Model Notes


This model describes the activation of immediate early genes such as cFos
after EGF or heregulin (HRG) stimulation of the MAPK pathway. Phosphorylated
cFos is a key transcription factor triggering downstream cascades of cell fate
determination. The model can explain how the switch-like response of p-cFos
emerges from the spatiotemporal dynamics. The model comprises lumped reaction
kinetics of the signal transduction pathway, the transcriptional and the
posttranslational feedback and feedforward loops. The parameter set
implemented here corresponds to that used for generating Figs. 4 B,C,D (red
curves for 10nM HRG) of the below article in Cell (2010). Moreover, we found
that the same model described well the dynamics in different cell types (MCF-7
and PC-12), of different ligands (EGF and HRG) and at different doses (0.1nM,
1nM, 10nM) for a unique set of parameter values (as implemented here and
reported in Table SD4_1 of the article) except for four parameters
characterising the input, cytoplasmic ppERK. These four parameters K1, K2,
tau1 and tau2 are used in the two equations involving species x1 and x2. These
two equations define a phenomenological input module to describe the ligand-,
dose- and cell type-dependent dynamics of ppERKc which are not modelled in
mechanistic detail here. The four parameter values can be adjusted to model a
specific ligand, dose and cell type. 8 parameter sets for different
experiments are given in Table SD4_2 of the article. This SBML file, however,
carries just one such parameter set. We have chosen that of MCF-7 cells
stimulated by 10nM of HRG. To reproduce all simulations from the article,
please replace the parameter values for K1, K2, tau1, tau2 as needed.

**Ligand-specific c-Fos expression emerges from the spatiotemporal control of ErbB network dynamics.**   
Takashi Nakakuki(1), Marc R. Birtwistle(2,3,4), Yuko Saeki(1,5), Noriko
Yumoto(1,5), Kaori Ide(1), Takeshi Nagashima(1,5), Lutz Brusch(6), Babatunde
A. Ogunnaike(3), Mariko Hatakeyama(1,5), and Boris N. Kholodenko(2,4); Cell
_In Press, online 20 May_ 2010, doi:[10.1016/j.cell.2010.03.054
](http://doi.dx.org/10.1016/j.cell.2010.03.054 )  
(1) RIKEN Advanced Science Institute, Computational Systems Biology Research
Group, Advanced Computational Sciences Department, 1-7-22 Tsurumi-ku,
Yokohama, Kanagawa, 230-0045, Japan  
(2) Systems Biology Ireland, University College Dublin, Belfield, Dublin 4,
Ireland  
(3) University of Delaware, Department of Chemical Engineering, 150 Academy
St., Newark, DE 19716, USA  
(4) Thomas Jefferson University, Department of Pathology, Anatomy, and Cell
Biology, 1020 Locust Street, Philadelphia, PA 19107, USA  
(5) RIKEN Research Center for Allergy and Immunology, Laboratory for Cellular
Systems Modeling, 1-7-22 Tsurumi-ku, Yokohama, 230-0045, Japan  
(6) Dresden University of Technology, Center for Information Services and High
Performance Computing, 01062 Dresden, Germany

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


