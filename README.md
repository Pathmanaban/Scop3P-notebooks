# Scop3P-notebooks
Jupyter Notebook examples of Scop3P REST API services.

## About Scop3P[^1]

**Scop3P: A Comprehensive Resource of Human Phosphosites within Their Full Context**

Protein phosphorylation is a key post-translational modification in many biological processes and is associated to human diseases such as cancer and metabolic disorders. The accurate identification, annotation, and functional analysis of phosphosites are therefore crucial to understand their various roles. Phosphosites are mainly analyzed through phosphoproteomics, which has led to increasing amounts of publicly available phosphoproteomics data. Several resources have been built around the resulting phosphosite information, but these are usually restricted to the protein sequence and basic site metadata. What is often missing from these resources, however, is context, including protein structure mapping, experimental provenance information, and biophysical predictions. We therefore developed Scop3P: a comprehensive database of human phosphosites within their full context. Scop3P integrates sequences (UniProtKB/Swiss-Prot), structures (PDB), and uniformly reprocessed phosphoproteomics data (PRIDE) to annotate all known human phosphosites. Furthermore, these sites are put into biophysical context by annotating each phosphoprotein with per-residue structural propensity, solvent accessibility, disordered probability, and early folding information. Scop3P, available at https://iomics.ugent.be/scop3p, presents a unique resource for visualization and analysis of phosphosites and for understanding of phosphosite structure–function relationships.

[^1]: Scop3P: A Comprehensive Resource of Human Phosphosites within Their Full Context, Pathmanaban Ramasamy, Demet Turan, Natalia Tichshenko, Niels Hulstaert, Elien Vandermarliere, Wim Vranken, and Lennart Martens
Journal of Proteome Research 2020 19 (8), 3478-3486. [DOI: 10.1021/acs.jproteome.0c00306](10.1021/acs.jproteome.0c00306).

**HTTP REST API**

Open the **Scop3P API** using the Swagger UI click [here](https://iomics.ugent.be/scop3p/swagger-ui/index.html)

## Jupyter Notebook index

This section contains the links to our online Jupyter Notebooks. We would like to invite you to contribute to our repository if you want to share your Jupyter Notebooks related to Scop3P. Please contact us at [pathmanaban.ramasamy@ugent.be](mailto:pathmanaban.ramasamy@ugent.be).

### Modifications endpoint (GET `scop3p/api/modifications`)
Simple notebook fetching modifications for UniProt ID [O00571](https://www.uniprot.org/uniprotkb/O00571/entry) (O00571 · DDX3X_HUMAN) and plotting some matplotlib charts.

<p align="center">
<img width="750" alt="image" src="https://github.com/Bio2Byte/Scop3P-notebooks/assets/1646576/8d61c88e-4bd7-48e0-856d-f3d70ed238dc">
</p>

Click on the next link to open the Jupyter Notebook in an executable environment:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Bio2Byte/Scop3P-notebooks/main?labpath=Scop3P_+O00571.ipynb)

### Modifications endpoint (GET `scop3p/api/modifications`) with 3D structure visualization
Simple notebook fetching modifications for UniProt ID [O00571](https://www.uniprot.org/uniprotkb/O00571/entry) (O00571 · DDX3X_HUMAN) and rendering the modifications on the 3D structure [4PXA](https://www.rcsb.org/structure/4PXA).

<p align="center">
  <img width="750" alt="image" src="https://github.com/Bio2Byte/Scop3P-notebooks/assets/1646576/13a5876e-35a1-451e-b942-7b027e5721c5">
</p>

Click on the Google collab icon to open the Jupyter Notebook in an executable environment:

<img src="https://upload.wikimedia.org/wikipedia/commons/archive/d/d0/20221103151253%21Google_Colaboratory_SVG_Logo.svg" width=90% height=90%>(https://colab.research.google.com/github/Bio2Byte/Scop3P-notebooks/blob/main/Scop3P_%20O00571.ipynb)


### Modifications endpoint (GET `scop3p/api/modifications`) with biophysical predictions
Simple notebook fetching modifications for UniProt ID [O00571](https://www.uniprot.org/uniprotkb/O00571/entry) (O00571 · DDX3X_HUMAN), predicting the biophysical properties and visualizing the results using different strategies.

#### Biophysical properties mapped onto AF structures in multi-panel view

<p align="center">
  <img width="750" alt="image" src=https://github.com/Bio2Byte/Scop3P-notebooks/assets/16449092/8c59e844-b607-4c2c-b827-7c014af397ce>
</p>

#### Biophysical properties and P-sites mapped onto 1D amino acid sequence position

<p align="center">
  <img width="750" alt="image" src=https://github.com/Bio2Byte/Scop3P-notebooks/assets/16449092/3a366740-2d1c-4ceb-9917-d7f1faaf65ec>
</p>

#### Biophysical properties linearized version of the online "RING" plot

<p align="center">
  <img width="750" alt="image" src="https://github.com/Bio2Byte/Scop3P-notebooks/assets/1646576/9792d23a-6838-4d84-81c8-815103549b71">
</p>

Click on the next link to open the Jupyter Notebook in an executable environment:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Bio2Byte/Scop3P-notebooks/main?labpath=Scop3P_O00571_4PXA-b2btools.ipynb)

## About

The repository was created by the [Bio2Byte research group](https://bio2byte.be) at Vrije Universiteit Brussel and is maintained in collaboration with [Compomics](https://www.compomics.com) at the VIB-UGent Center for Medical Biotechnology.

- [Compomics](https://www.compomics.com): Computational Omics and Systems Biology Group
- [IBsquare](https://ibsquare.be): The Interuniversity Institute of Bioinformatics in Brussels
- [VIB](https://vib.be/en): Vlaams Instituut voor Biotechnologie
- [UGent](https://www.ugent.be): Universiteit Gent
- [VUB](https://vub.be): Vrije Universiteit Brussel
- [Elixir BE](https://www.elixir-belgium.org): Elixir Belgium


<img width="962" alt="image" src="https://github.com/Bio2Byte/Scop3P-notebooks/assets/1646576/e2348f29-6b9b-4d0c-bbb4-1d309d34e46f">

<p align="center">
Made in Belgium :belgium:
</p>
