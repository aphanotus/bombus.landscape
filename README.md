**This repository holds code associated with *Seasonally increasing parasite load is associated with microbiota dysbiosis in wild
bumblebees. mSystems (2025)***

**16S amplicons, *C. bombi* qPCR, and associated metadata are included for all 639 samples in the Maine Bumblebee Atlas**
- 16S: `data/qiime` (in qiime2 format)
- qPCR: `data/qpcr` (with `notebooks/QPCR.ipynb` for processing)
- metadata: `data/BombusMetadata.tsv`


All analyses and figures presented in the paper can be reconstructed from jupyter notebooks in the `notebooks/` directory. 
The intended order of the analysis notebooks is: 

1. `QPCR.ipynb`
2. `Group_Sites.ipynb`
3. `Process_OTUs.ipynb`
4. `fig1_diversity.ipynb`
5. `phylogenetic_correlation_strain_level.ipynb`
6. `crithidiapglmm.ipynb`

