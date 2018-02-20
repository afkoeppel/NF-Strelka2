# NF-Strelka2
This pipeline begins with WGS data in fastq format, aligns the data to a reference with BWA, and calls variants using Strelka2.

[![Build Status](https://travis-ci.org/afkoeppel/NF-Strelka2.svg?branch=master)](https://travis-ci.org/afkoeppel/NF-Strelka2)
[![Nextflow](https://img.shields.io/badge/nextflow-%E2%89%A50.24.0-brightgreen.svg)](https://www.nextflow.io/)


### Introduction
NF-Strelka2: This pipeline begins with WGS data in fastq format, aligns the data to a reference with BWA, and calls variants using Strelka2.

The pipeline is built using [Nextflow](https://www.nextflow.io), a workflow tool to run tasks across multiple compute infrastructures in a very portable manner. It comes with docker / singularity containers making installation trivial and results highly reproducible.


### Documentation
The NF-Strelka2 pipeline comes with documentation about the pipeline, found in the `docs/` directory:

1. [Installation](docs/installation.md)
2. Pipeline configuration
    * [Local installation](docs/configuration/local.md)
    * [Adding your own system](docs/configuration/adding_your_own.md)
3. [Running the pipeline](docs/usage.md)
4. [Output and how to interpret the results](docs/output.md)
5. [Troubleshooting](docs/troubleshooting.md)

### Credits
This pipeline was written by Alexander F. Koeppel ([afkoeppel](https://github.com/afkoeppel)) at [University of Virginia](https://med.virginia.edu/bioinformatics-core/).
