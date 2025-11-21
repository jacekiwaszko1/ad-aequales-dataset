[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17666341.svg)](https://doi.org/10.5281/zenodo.17666341)

# Compositions _ad aequales_ in the Music Collections of Wawel Cathedral: A Digital Approach to Repertoire Extraction

## The dataset

This repository contains the dataset used as the basis for the analytical study of ad aequales compositions preserved in the music collections of Wawel Cathedral. The source corpus consists of more than 2,000 works included in the digital editions published through the [_Polish Digital Scores_](https://polishscores.org) portal. For the purposes of the present study, the corpus was narrowed to 884 complete four-voice compositions, counting each movement of a mass cycle as an independent item. Limiting the dataset to fully preserved four-part settings was essential, as incomplete materials would have prevented the application of several analytical procedures and could have obscured the interpretation of their outcomes.

The dataset is provided as a tab-separated values (TSV) table, designed to facilitate transparent inspection, reproducibility, and computational processing. A concise description of all fields included in the dataset is given below.

### Fields in the dataset

| field | description |
| ---: | :--- |
| Composer | Composer's name |
| Cycle | Title of a cycle (if applicable) |
| Title | Title of the composition |
| Shelfmark | Shelfmark in Kraków Cathedral Archives (PL-Kk) |
| cenid | ID in the [_Polish Digital Scores_](https://polishscores.org) portal |
| filename | The name of file from the [_Polish Digital Scores_](https://polishscores.org) portal |
| Clefs | The set of clefs used to notate the composition from top part to the bottom |
| Tessitura | the range between the highest and the lowest pitch in the whole composition |
| P[n]-name  | Name of part no. [n] (counting from bottom to the top) |
| P[n]-top | The highest pitch in part no. [n]|
| P[n]-bottom | The lowest pitch in part no. [n] |
| P[n]-tess | The range of notes within part no. [n] |
| topP[n]-P[n+1] | The difference between the top notes of adjacent parts expressed in semitones |
| P[n]-P[m]% | The percentage of crossing notes in two parts |
| P[n]-P[m]# | The count of crossing notes in two parts |
| R? | Manually added marking stating if the piece was clasified as a part of rorantist's repertoire |
