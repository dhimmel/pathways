# Pathway Gene Sets

This repository compiles pathway gene sets from [WikiPathways](http://www.wikipathways.org/index.php/WikiPathways) and [MSigDB](http://www.broadinstitute.org/gsea/msigdb/collection_details.jsp) into an easy-to-parse tsv ([`data/pathways.tsv`](data/pathways.tsv)).

Only protein-coding human genes (Entrez GeneIDs) are included. See the corresponding [Thinklab discussion](https://doi.org/10.15363/thinklab.d72) for more information.

Execute the [`merge-resources.ipynb`](merge-resources.ipynb) python notebook to rebuild the dataset.
