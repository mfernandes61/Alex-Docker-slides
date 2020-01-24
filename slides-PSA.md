<!--
author:   Alexander Botzki
email:    Alexander.Botzki@vib.be
version:  0.1.1
language: en
narrator: US English Female

comment:  slides Protein Structure Analysis

logo: img/Logo.png

link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/img/org.css

debug: true

-->

# Protein Structure Analysis

- Sequences, structures and databases
- Experimental methods (X-rays, electrons and NMR)
- Finding and visualising structures from the  Protein Data Bank
- Comparing structures
- Modelling mutations
- Creating homology models

## Sequences and Structures

add one slide over transcription / translation / 

## Amino acids and peptide structure

![](/topics/protein-structure-analysis/images/amino-acids.png)

## The Structure-Function Connection

.pull-left[
- Folded proteins provide a well-defined 3D arrangement of functional groups, creating microenvironments and active sites.
- Structural changes  are often involved in functional  mechanisms  (motor proteins, ...)
]
.image-90[![](/topics/protein-structure-analysis/images/hemoglobin.png)]

## Databases

.pull-left[
**Uniprot** approx. 1100,000 sequences

- mainly determined by large-scale DNA sequencing of individual genes or whole genomes
- increasingly automated annotation

**Protein Data Bank** approx. 141,000 
experimentally determined structures

- Mainly determined by X-ray crystallography and high-resolution NMR spectroscopy
- Automation is increasing, but there are still significant limitations in the rate of solving new structures
]


]
.pull-right[ .image-50[![](/topics/protein-structure-analysis/images/uniprot-logo.png)]
             .image-50[![](/topics/protein-structure-analysis/images/pdb-logo.png)]
]

## X-Ray Crystallography

![](/topics/protein-structure-analysis/images/xray-tech-setup.png)

.pull-left[

.left[In a crystal, a large number  of macromolecules are  packed together in a regular grid, with consistent  orientations and relative  distances. 
When exposed  to an X-ray beam, this  arrangement gives rise to
diffracted rays in specific directions,  resulting in discrete spots on the planar
detector. By rotating the crystal, a series  of images is obtained. From these, the
intensities of all the diffracted rays of the  crystal can be derived.]

]
.pull-right[ .image-90[![](/topics/protein-structure-analysis/images/diffraction-pattern.png)]
]


## X-Ray Crystallography

.pull-left[
.image-50[![](/topics/protein-structure-analysis/images/diffraction-pattern.png)]
]
.pull-right[.image-50[![](/topics/protein-structure-analysis/images/electron-density.png)]]

|              |          |               |
|:-------------|:--------:|--------------:|
| Diffraction Spot Intensities and Phases $$F_{obs}(h,k,l)$$ and $$\phi_{obs}(h,k,l)$$ | $$R_{cryst} = \frac{\sum_{h,k,l}F_{obs}-F_{calc}}{\sum_{h,k,l}F_{obs}}$$ | Electron density $$\rho(x,y,z)$$ |


## The Protein Databank

.pull-left[ .image-80[![](/topics/protein-structure-analysis/images/wwpdb-welcome-page.png)] 


.pull-right[ 
.left[ [http://www.wwpdb.org](http://www.wwpdb.org) ]
- contains structures of  proteins, nucleic acids  and complexes,  determined by X-ray  crystallography, NMR  spectroscopy
- No purely theoretical  or ab initio models  (since 2006)
- Also stores supporting  experimental data
- Full deposition now  required by all peer-reviewed journals
]
]

---

## Exercise 1: Search the PDB

- Use the UniProt site to search for “dnak”.  
- Use the PDB site to search for “dnak”.
 - Compare the UniProt and PDB result lists.
- Use the sequence search function to see if there are structures with sequences similar to that of the  DnaK C-terminal domain.
- Look at the summary pages of a number of  structures and note some interesting properties.
- Select a number of structures and create a report  page.

---

## PDB File Format

![](/topics/protein-structure-analysis/images/pdb-file-format.png)

---

## Occupancy

![](/topics/protein-structure-analysis/images/occupancy.png)


---

## Related Web sites

- Nucleic Acid Database: DNA and RNA structures

.left[[http://ndbserver.rutgers.edu/](http://ndbserver.rutgers.edu/)]

- PDB-REDO: automatically re-refined deposited  structures, using the latest methods

.left[[http://www.cmbi.ru.nl/pdb_redo/](http://www.cmbi.ru.nl/pdb_redo)]

- EBI: many online tools for structure analysis

[http://www.ebi.ac.uk/Tools/structure/](http://www.ebi.ac.uk/Tools/structure/).left[]]

- Replaced Electron Density Server: convenient overview of  quality parameters for crystal structures

.left[[http://www.ebi.ac.uk/pdbe/litemol](http://www.ebi.ac.uk/pdbe/litemol)]

## High-Resolution NMR Spectrometry

.left[Many atomic nuclei, including the ubiquitous hydrogen nuclei,  resonate at specific radio frequencies when placed in a  strong, uniform magnetic field. The chemical environment of each individual atom slightly modulates its exact resonance  frequency.]

.image-80[![](/topics/protein-structure-analysis/images/nmr-peaks-to-structure.png)]

.left[In macromolecules with thousands of atoms, many different  effects combine to generate an extremely complicated pattern of chemical shifts, 
which therefore more or less uniquely  identify each atom. Multidimensional spectra allow these  frequencies to be assigned to specific atoms.]

## High-Resolution NMR Spectroscopy

.left[When two atoms are near each other in 3D space, they can exchange magnetization, giving rise to crosspeaks at the  intersection of their respective frequencies.]

.image-50[![](/topics/protein-structure-analysis/images/nmr-noe.jpg)]

.left[This nuclear Overhauser effect (NOE) is used to effectively measure the distances between pairs of atoms, at least  qualitatively.]

### High-Resolution NMR Spectroscopy

.left[After identification of the atoms by means of their unique chemical shifts, distance restraints are derived from the  Overhauser crosspeaks. An extended model of the protein  is  generated,  
and  then  condensed  into  a  shape  that  is consistent with as many of distance restraints as possible.]

.image-50[![](/topics/protein-structure-analysis/images/nmr-model-example.png)]

## Other methods

- Electron microscopy (and especially Cryo-electron microscopy): Electron crystallography and single particle reconstruction
-Small-angle X-ray and neutron scattering (SAXS and SANS)


.image-80[![](/topics/protein-structure-analysis/images/saxs.png)]

## Related Web sites ###

- BioMagResBank: experimental data for NMR-  derived structures (lists of distance restraints  and other experimentally derived properties)

.left[[http://www.bmrb.wisc.edu/](http://www.bmrb.wisc.edu/)]

- BioIsis: database of SAXS-derived structures

.left[[http://www.bioisis.net](http://www.bioisis.net)]

- EMBL database of SAXS-derived structures

.left[[http://www.sasbdb.org](http://www.sasbdb.org)]

- EM Databank for cryo-EM structures

[http://www.emdatabank.org](http://www.emdatabank.org.left[)]

## Assessing Structure Quality

General geometric properties (bond lengths and angles, Ramachandran distribution, …): MolProbity  [Link](http://molprobity.biochem.duke.edu/)

.left[ **Crystal Structures** ]
- Diffraction data resolution and completeness (PDB)
- Final $$ R_{cryst} $$ and $$ R_{free} $$ factors (PDB)
- Local correspondence to electron density (EDS)

.left[**NMR Structures**]
- Number of distance restraints and additional experimental data sources (BMRB)
- Local restraint density (on-line NMR constraint analyser)
[link](http://molsim.sci.univr.it/bioinfo/tools/constraint/index.html)

.left[**Other techniques**]
- Difficult to generalise: carefully read and consider the  published protocol

## Molecular Graphics Software

- [PyMOL](http://www.pymol.org/): high-quality output,  good examples on [Wiki](http://www.pymolwiki.org/)
- [Chimera](http://www.cgl.ucsf.edu/chimera/): good  documentation on website
- [VMD](http://www.ks.uiuc.edu/Research/vmd/):  excellent for the analysis of MD trajectories
- [Yasara](http://www.yasara.org)  
- [SwissPDBViewer](http://spdbv.vital-it.ch/)

## YASARA

.left[
Yasara View is freely available and provides  basic visualisation functions.

Yasara Model, Dynamics and Structure provide  additional functionality.

An add-on module for NMR structures is  available.

The program can be combined with the WHAT-  IF program for structure validation, and with  FoldX for energy calculations.]

## Exercise 2: show a structure

.left[
Load PDB entry 1TRZ using the File menu.

Compare the default representations (F1-F8)  and use the various controls to change the view  of the protein.

Explore the Edit and View menus to change  various aspects of the graphical representation  of the structure.

Examine the hydrogen bonding patterns.  Display a molecular surface.

Create an interesting view of the molecule and  save it as a high-resolution image.
]

## Protein folds are the structures of domains

.left[
Similarities in assembly of secondary structure elements

So not based on sequence like motifs but on 3D structure

Folds represent the shapes of protein domains!
]

Examples: TODO (add images e.g. alpha solenoid, DNA clamp, thioredoxin fold)

## Databases of protein folds

- SCOP (http://scop.mrc-lmb.cam.ac.uk/scop/)
- CATH (http://www.cathdb.info/)

## check on slides from course Wim Vranken

see also (http://www.ii.uib.no/~slars/bioinfocourse/PDFs/structpred_tutorial.pdf)

## Structure Superposition

.left[
Structures can be superimposed to achieve the best  possible match between corresponding atoms. It is  possible to consider all atoms, or only a subset  (such as the Cα atoms).

When the structures are very similar, determining  which atoms should be matched to each other is  trivial. When there are larger differences, it takes  more preparation.

Different algorithms use different combinations of  sequence- and secondary of tertiary structure-based information.
]

## Exercise 3: Compare Structures

.left[
Download the five provided PDB files and open  them in Yasara.

Use the `Analyze|Align|Objects` with MUSTANG  function to align the four last objects with the first one.

Use the space bar to open the text console and  see the reported root mean square deviations as well as the number of residues matched.
]

$$ rmsd = \sqrt{\frac{1}{N}\sum_{i=1}^{N}R_{i}^{2}} $$ 

.left[
Color all structures by B factor and compare the  distribution to the local variability of the structures.
]
---

## PDB File Surprises

- Missing atoms, residues and loops  
- Multiple molecules in the asymmetric unit
- Incomplete oligomers due to coincident crystal and  oligomer symmetry
- Cα-only models  lternate conformations
- Multiple models, especially for NMR ensembles
- Use of B factors to represent other properties  ther non-standard extensions (PDBQT, ...)

## Force Fields

- Energy terms representing physical interactions

 - Covalent bond lengths and angles
 - Dihedral angles and van der Waals forces (steric effects)
 - Electrostatic interactions and hydrogen bonds
…

- Energy can be minimized, and forces can literally be derived from the potential function.

- Consistency and careful consideration of the  properties to be simulated are essential.

---

### Force Field Terms ###

.left[Each energy term has a functional form, which includes one or more parameters:]

- Covalent bond energy term
 To do: add formula
- Van der Waals contact energy term

.left[The parameters are collectively optimized to  reproduce a chosen set of experimentally observed parameters.

A given force field should be used as a  consistent system, and can only be used to predict properties that are covered by the  training set.
]

## FoldX


.left[
Is designed for quantitative modelling of the contribution of structural interactions to the stability of proteins and protein complexes. It also supports  protein/DNA complexes.

The force field describes the different interactions in a  protein structure or complex in analytical terms. It has  been calibrated using a set of experimentally determined  stabilities.

Applications include the optimisation of structures, the calculation of the stability of complexes, and predicting  the effect of amino-acid or base-pair mutations on these  properties.
]

## The FoldX Plugin for YASARA

.left[
In order to make FoldX more accessible and  integrate its functions into Yasara, dr. Joost van  Durme (SWITCH laboratory) made a Yasara plugin  module that can apply FoldX functions to structures  that are loaded as Yasara objects.

This greatly simplifies the use of FoldX, and allows  for a quick visual analysis of the resulting changes  in the structures.

More information can be found at [wiki](http://foldxyasara.switchlab.org/index.php/) [FoldX](http://foldxsuite.crg.eu/)
]

## Exercise 4a: Repair a PDB File

- Load the 1CRN PDB file.
- Use the “Repair object” option in the Analysis |  FoldX menu to activate the corresponding FoldX  function.
- Select the object to repair.

.left[This exports the object as a temporary PDB file,  starts FoldX with the appropriate options, and loads  the repaired PDB file as a new object in Yasara.]

- Compare the original and repaired objects.  
- Describe the changes that were introduced.

## Exercise 4b: Model a Mutation

- Load the 2AC0.sce Yasara scene file.
- Set an appropriate structure representation.
- Locate residue Ala159 using the sequence view,  and right-click to access the `FoldX|Mutate` residue function. Change it to a Trp residue.
- Look at the effect of the substitution on the  structure, and use the space bar to open the text  console and read the output of the FoldX  calculation.
- Mutate Arg273 to an alanine side chain. Discuss  the effects of this substitution.

## Homology Modelling

- When a structure is available for a protein with a  similar sequences, it is possible to predict the  structure of a new sequence with varying degrees of  confidence.
- Use PSI-BLAST/DELTA-BLAST to detect sequences with similar structures.
- All homology modelling procedures start from an  alignment of the template and target sequences.  The quality of this alignment will have a major  impact on the resulting model.
- Available applications include stand-alone programs  (Modeller, FoldX, …) and web-based services (such as SwissModel).

## Exercise 5: Make a Homology  Model using Swiss Model ###

see []()

## Predict protein structures by fold recognition

1. Search SCOP/CATH for protein with same fold and known 3D structure
2. Align each amino acid of query sequence to a position in the template structure
3. Evaluate how well the sequence fits the fold and select best-fit fold
4. Build structural model of query based on alignment with selected fold

- Phyre (http://www.sbg.bio.ic.ac.uk/phyre2/html/page.cgi?id=index)
- HHpred (http://toolkit.lmb.uni-muenchen.de/hhpred)
- DescFold (http://202.112.170.199/DescFold/)

.left[Works because:
- Number of different folds in nature is fairly small (approximately 1300)
- 90% of new submissions in PDB have similar folds to those already in PDB
- Not always accurate
]

## Guidelines to improve fold recognition results

- Run as many methods as you can
- Run each method on many sequences from your homologous protein family
- After all of these runs, build up a consensus picture of the likely fold
- Compare function of your protein to function of the proteins with the likely fold
- Compare secondary structure of your protein to that of the likely fold


## Similarity searches based on 3D structure

.left[
Similarity on structural level: aligning 3D structures

Structure of query protein is known and aligned to PDB structures
- VAST+ (https://www.ncbi.nlm.nih.gov/Structure/vastplus/vastplus.cgi)
- DALI (http://ekhidna.biocenter.helsinki.fi/dali_server/)

Compare proteins with low sequence similarity:
similar structure implies homology -> same function

Can help to find active sites
]

## Exercise 6: Study Protein-Ligand Interactions

see []()

## On-Line References ###

- Crystallography 101 (Bernhard Rupp):  (http://www.ruppweb.org/Xray/101index.html)
- Protein NMR, A Practical Guide (Vicky Higman) (http://www.protein-nmr.org.uk/)
- Model validation course  (http://xray.bmc.uu.se/gerard/embo2001/modval/index.html)
- Assessing model quality (http://spdbv.vital-it.ch/TheMolecularLevel/ModQual/)

- Lectures by Burkhard Rost on protein structure  prediction (https://www.youtube.com/channel/UCU6j8BG4RbEtTgyIZJ6Vpow)

---