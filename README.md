# RecobundlesX pipeline
===================

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/scilus/rbx_flow)](https://github.com/scilus/rbx_flow/releases)

[![Nextflow](https://img.shields.io/badge/nextflow-21.10.6-brightgreen.svg)](https://www.nextflow.io/)
[![Docker container badge](https://img.shields.io/docker/v/scilus/scilus?label=docker&logo=docker&logoColor=white)](https://hub.docker.com/r/scilus/scilus)

Run the RecobundlesX pipeline.
To access the example atlases:
https://zenodo.org/record/7950602

If you use this pipeline, please cite:

```
Etienne St-Onge, Kurt Schilling, Francois Rheault, "BundleSeg: A versatile,
reliable and reproducible approach to white matter bundle segmentation.",
arXiv, 2308.10958 (2023)

Rheault, Francois. Analyse et reconstruction de faisceaux de la matière blanche.
page 137-170, (2020), https://savoirs.usherbrooke.ca/handle/11143/17255

Kurtzer GM, Sochat V, Bauer MW Singularity: Scientific containers for
mobility of compute. PLoS ONE 12(5): e0177459 (2017)
https://doi.org/10.1371/journal.pone.0177459

P. Di Tommaso, et al. Nextflow enables reproducible computational workflows.
Nature Biotechnology 35, 316–319 (2017) https://doi.org/10.1038/nbt.3820
```

Requirements
------------

- [Nextflow](https://www.nextflow.io)
- [scilpy](https://github.com/scilus/scilpy)
- [ants](https://github.com/ANTsX/ANTs)

Singularity/Docker
-----------
If you are on Linux, we recommend using the Singularity to run rbx_flow pipeline.
If you have Apptainer (Singularity) launch your Nextflow command with:
`-with-singularity scilus/scilus:1.6.0`

Image is available [here](http://scil.dinf.usherbrooke.ca/en/containers_list/scilus-1.6.0.sif)

If you are on MacOS or Windows, we recommend using the Docker container to run rbx_flow pipeline.
Launch your Nextflow command with:
`-with-docker scilus/scilus:1.6.0`

Usage
-----

See *USAGE* or run `nextflow run main.nf --help`

