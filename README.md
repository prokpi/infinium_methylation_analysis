# infinium_methylation_analysis
DNA/RNA Dynamics course project. The pipeline analyses DNA methylation data generated from the Illumina HumanMethylation450 BeadChip platform.

### Install required packages
```
# BiocManager
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install(version = "3.10")

# minfi
BiocManager::install("minfi")

# Illumina manifest
BiocManager::install("IlluminaHumanMethylation450kmanifest")
BiocManager::install("IlluminaHumanMethylation450kanno.ilmn12.hg19")

# factoextra
install.packages("factoextra")

# qqman
install.packages("qqman")

# gplots
install.packages("gplots")

# future.apply (optional for parallelization)
install.packages("future.apply")

# viridis
install.packages("viridis")
```
