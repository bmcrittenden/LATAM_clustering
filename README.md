# Brazil State Clustering

Brazil is relatively diverse when it comes to the geographic variance in the health of its citizens. For the purposes of epidemiological review, it is desirable to break Brazil into multiple different regions that show similar health characteristics - this way the healthcheck and triage models will be more appropriate for those regions.

Here we use UMAP for dimensionality reduction of IHME data and HDBSCAN for clustering, to distingish multiple clusters within the US.

## Packages

You will need to install a few modules for the notebooks to work. Apologies for the lack of a requirements file. Please refer to what is imported at the top of each notebook

## Useful files

- latam_clusters.ipynb: file with the pipeline for clustering the data
