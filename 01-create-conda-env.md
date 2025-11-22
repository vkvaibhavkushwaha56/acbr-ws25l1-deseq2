# Create Conda Environment with Miniconda
Created using Windows Subsystem Linux (WSL) for DESeq2 Bioconductor package to analyze RNAseq data

## Code in WSL terminal
- Start the WSL in Windows
- Type the following t create a conda environment for R4.5 names as R4.5WS
```{cmd}
conda create --name R4.5WS
```
- Activate the R4.5WS conda environment as follows
```{cmd}
conda activate R4.5WS
```
- Install R4.5 in the R4.5WS conda environment
```{cmd}
conda install conda-forge::r-base
```
`conda-forge` is the channel from anaconda.org. [conda-forge/r-base-4.5.2] (https://anaconda.org/conda-forge/r-base)





