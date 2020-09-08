
## Latest release of bioconductor. This contains rstudio and a bunch of system dependencies.
FROM bioconductor/bioconductor_docker:latest

RUN R -e "BiocManager::install(c( \
    'GenomicRanges', \
    'rtracklayer', \
    'StructuralVariantAnnotation', \
    'dplyr', \
    'tidyr', \
    'readr'), update=FALSE, ask=FALSE)"

