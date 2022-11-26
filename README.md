<div align="center">
  <h1><b>SNV Cancer Evolution Estimation</b></h1>
  <img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/61354833?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d">
  <p>⚡ <b>Code by <a href="https://github.com/TomMakesThings">TomMakesThings</a></b> ⚡</p>
  <p><b><sub>February 2022</sub></b></p>
</div>

---

## About
This repository contains <a href= "https://github.com/TomMakesThings/Cancer-Evolution/blob/main/Mutation-Matrix.ipynb">a Jupyter notebook</a> to estimate the clonal populations of a sequenced neoplastic tumour sample. Given a cell mutation matrix, the code finds common sets of SNVs across cells and approximates likely clonal expansions. From this, a clonal evolutionary tree can be derived. In addition, from uncovering clonal populations, cellular fractions and cancer cell fractions (CCF) are calculated as these statistics are useful to quantify tumor heterogeneity and evolution.

<div align="center">
  <img src="https://github.com/TomMakesThings/Cancer-Evolution/blob/assets/Images/Evolution-Matrix.png" width=700>
</div>

<sub>Figure (A) Example of a clonal evolution matrix derived from a population of SNVs at 23 loci for 42 cells. Each coloured block represents an estimate for a clonal expansion, in which sets of SNV(s) were introduced.</sub>

<div align="center">
  <img src="https://github.com/TomMakesThings/Cancer-Evolution/blob/assets/Images/Evolution-Tree.png" width=700>
</div>
<sub>Figure (B) Left is the clonal evolution tree for the mutation matrix with SNVs at 23 loci for 42 cells. Each clonal population has a distinct genotype and is plotted as a circle with a genotype symbol to the right or underneath. The proportion of the overall cellular mixture with that genotype is shown by the number in the centre. Top right is the column summary plot, which depicts the number of mutated loci per mutation type. Lower right is the row summary plot, which shows how many cells carry each genotype.</sub>
