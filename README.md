# Trim Galore!
_Trim Galore!_ is a wrapper around [Cutadapt](https://github.com/marcelm/cutadapt) and [FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/) to consistently apply adapter and quality trimming to FastQ files, with extra functionality for RRBS data.

[![Build Status](https://travis-ci.org/FelixKrueger/TrimGalore.svg?branch=master)](https://travis-ci.org/FelixKrueger/TrimGalore)
[![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg)](http://bioconda.github.io/recipes/trim_galore/README.html)
[![container ready](https://quay.io/repository/biocontainers/trim-galore/status)](https://quay.io/repository/biocontainers/trim-galore)


## Installation
_Trim Galore!_ is a a Perl wrapper around two tools: [Cutadapt](https://github.com/marcelm/cutadapt) and [FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/). To use, ensure that these two pieces of software are available and copy the `trim_galore` script to a location available on the `PATH`.

For example:
```bash
# Check that cutadapt is installed
cutadapt --version
# Check that FastQC is installed
fastqc -v
# Install Trim Galore!
curl -fsSL https://github.com/FelixKrueger/TrimGalore/archive/0.4.3.tar.gz -o trim_galore.tar.gz
tar xvzf trim_galore.tar.gz
mv TrimGalore-0.4.3/trim_galore /usr/bin
```

## Documentation
For instructions on how to use _Trim Galore!_, please see the [User Guide](Docs/Trim_Galore_User_Guide.md).

## Credits
_Trim Galore!_ was developed at The Babraham Institute by [@FelixKrueger](https://github.com/FelixKrueger/). You can find it's project page here: [bioinformatics.babraham.ac.uk](http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/)
