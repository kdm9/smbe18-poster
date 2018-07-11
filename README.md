# Genomic divergence and diversity in woodland Eucalypts

**Kevin D. Murray**, Jasmine Janes, Justin O. Borevitz, Rose L. Andrew

The Australian National University, Canberra, Australia, and University of New England, Armidale, Australia

> NB: this poster describe very preliminary results, so take any inference with a grain of salt

## Abstract

Eucalypts are key tree species in most Australian ecosystems. Grassy woodland Eucalypts are predominantly from the section Adnataria, a group of ~100 species that diverged approx. 20Mya[1]. Using low-coverage whole-genome sequencing, we re- sequenced the genomes of 600 individuals across 14 Eucalyptus species from section Adnataria. This poster presents preliminary results of the study. We confirmed previous findings of very high genetic diversity, and found little genome-wide divergence between species. We also found signals of ongoing inter-species gene flow and discovered many cryptic hybrids. We found only weak signs of population structure, and varying extents of genome-wide isolation by landscape among species.

## Contact

Kevin can be contacted at `FIRSTNAME at kdmurray.id.au`.

## Methods

Whole-genome sequencing using a modified tagmentation-based protocol was used on 588 accessions collected from across south-eastern Australia. Reads were quality controlled using AdapterRemoval, mapped to the *E. grandis* reference using BWA-MEM. Genetic distances were estimated using Mash, and genomic covariance was estimated with PCAngsd. Genomic covariances were converted to euclidean distances using the Gower transform. PCA, mantel tests and GDM were performed in R.


## Reference

[1]:  Mike Crisp, Lyn Cook and Dorothy Steane (2004) **Plant Phylogeny and the Origin of Major Biomes**, *Philosophical Transactions: Biological Sciences* Vol. 359, No. 1450, pp. 1551-1571 
