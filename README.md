# setton_hadi_choo_2023
This repository contains code and data to generate the figures presented in Setton, Hadi, Choo et al. Nature 2023.

Most figures (aside from those which rely on random forest training) are found in `./notebooks/figures.ipynb`. 
The remaining figures (Figure 5, Extended Data Figure 8, and Extended Data Figure 9) are found in `./notebooks/random_forest.ipynb`.

We have also made available our OnenessTwoness random forest classifier, which predicts whether a tumor sample is HR-proficient, BRCA1-deficient, and BRCA2-deficient.
This is saved in the file `./models/stash.retrained.model.rds`.
