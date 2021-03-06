# examples

Following the old adage that an example is worth a thousand docstrings, we created a set of notebooks that cover many typical Hi-C analyses using the open2c code ecosystem. For users who are new to Hi-C analysis, we recommend going through example notebooks in the following order:
- [viz.ipynb](https://github.com/open2c/open2c_examples/blob/master/viz.ipynb): how to load and visualize Hi-C data stored in coolers.
- [contacts_vs_distance.ipynb](https://github.com/open2c/open2c_examples/blob/master/contacts_vs_distance.ipynb): how to calculate contact frequency as a function of genomic distance-- the most prominent feature in Hi-C maps
- [insulation_and_boundaries.ipynb](https://github.com/open2c/open2c_examples/blob/master/Insulation_and_boundaries.ipynb): how to extract insulation profiles and call boundaries using insulation profile minima. 
- [pileup_CTCF.ipynb](https://github.com/open2c/open2c_examples/blob/master/pileup_CTCF.ipynb): how to create avearge maps around genomic features like CTCF.
These notebooks currently focus on mammalian interphase Hi-C analysis, but are readily extendible to other organisms and cellualr contexts.
