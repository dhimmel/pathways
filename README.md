# A compilation of pathway gene sets

[![DOI](https://zenodo.org/badge/14475/dhimmel/pathways.svg)](https://zenodo.org/badge/latestdoi/14475/dhimmel/pathways)

This repository compiles pathway gene sets for inclusion into the Rephetio hetnet. Pathways are compiled from [WikiPathways](http://www.wikipathways.org/index.php/WikiPathways) and [Pathway Commons](http://www.pathwaycommons.org/pc2/) into a user-friendly TSV ([`data/pathways.tsv`](data/pathways.tsv)). The resources extracted from Pathway Commons are the [Pathway Interaction Database](https://pid.nci.nih.gov/) (PID) and [Reactome](http://www.reactome.org/).

Only protein-coding human genes (as Entrez Gene IDs) are included. See the corresponding [Thinklab discussion](https://doi.org/10.15363/thinklab.d72) for more information.

Execute the [`merge-resources.ipynb`](merge-resources.ipynb) python notebook to rebuild the dataset.

## License

All original content in this repository is released as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). WikiPathways data is [licensed](http://www.wikipathways.org/index.php/WikiPathways:License_Terms) as [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/). Reactome data is licensed as [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/). PID data is in the public domain.

Reuse of the Pathway Commons download ([`download/Pathway Commons.7.All.GSEA.hgnc.gmt`](download/Pathway Commons.7.All.GSEA.hgnc.gmt)) is subject to the license terms of each contributing database.
