#   Flux balance analysis for E. coli metabolic model

## Summary
This is a compilation of Jupyter notebook files used to perform metabolic engineering on *E. coli* MG1655 metabolic model (iJO1366) modified to perform synthesis of **beta-carotene**. The aim was to improve the production of the metabolite through gene knockout frameworks and identification of gene expression modulation targets both supplied by the [**cameo**](https://github.com/biosustain/cameo) package.

Besides the IPYNBs, I have also added the two versions of metabolic models used: the base iJO1366, that can be found on bigg.ucsd.edu, titled `iJO1366_MEP`, as it uses the native *E. coli* MEP pathway to synthesise **beta-carotene**, and an edited iJO1366 with the Mevalonate (MEV) pathway from *Saccharomyces cerevisiae* (`iJO1366_MEV`). Both versions also contain the beta-carotene synthesis genes, that are not part of native *E. coli* metabolism.

[KEGG pathway](https://www.genome.jp/kegg-bin/show_pathway?map01062+C16521) for the biosynthesis of terpenoids and steroids, to help illustrate the difference between the MEP and MEV pathway.

Hopefully having these examples will be of some help to others working with **cameo** and **cobrapy**.
