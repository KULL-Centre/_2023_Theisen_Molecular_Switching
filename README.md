# _2023_Theisen_Molecular_Switching
This repository contains the data files related to our manuscript "Molecular switching in transcription through splicing and proline-isomerization regulates stress responses in plants" by Theisen et al., 2023. This study explores the molecular mechanisms of transcriptional regulation in plant stress responses, offering new insights into proline-isomerization and its impact on regulation.

**Manuscript Status**: Under review.

**Preprint**: [Research Square](https://www.researchsquare.com/article/rs-3034274/latest) 

## Data Description
This repository is organized into several sections, each representing a different aspect of our study:

### NMR (Nuclear Magnetic Resonance)
  - DREB2A NMR data contains CEST profiles in a raw format. WT DREB2A was recorded using 500 µM DREB2A and 25 µM Med25ACID. Carbon CEST profiles were recorded at 25 °C.
    - For assistance with processing of CEST data, contact authors.
  - Med25ACID NMR data contains chemical shifts of the unbound state and D2a titrations, relaxation rates and hetNOEs. Assignment and titration data was obtained at 25 °C at pH 6.5 using BestTrosy pulse sequences.
    - Also contains MICS output for free Med25ACID and Med25ACID with DREB2A ABS.

### ITC (Isothermal Titration Calorimetry)
  - Raw .itc files are provided. Concentrations given in file should be correct.
  - Spolar Record structuring analysis data is also provided in an Excel file.

### Stopped-Flow (Fluorescence Kinetics)
  - Contains raw fluorescence traces. Indicated concentrations are post mixing concentations.
  - Contains observed rate constants.
  - Includes biological replicate data for ABS-RIM association: indivudally fitted trace k_obs of four concentrations between 2 and 3.5 µM.

### SAXS (Small Angle X-ray Scattering)
  - Buffer subtracted scattering curve of Med25ACID_532-680 obtained from SEC-SAXS.

### MD (Molecular Dynamics)
  - 1.7 µs trajectory snapshots at 0.5 ns intervals.

### Med25ACID:DREB2A Complex Models
  - Contains all three AF2 models discussed in the paper.
  - Contains a cis proline version model 2, obtained through a 1 ns MD simulation.
### Bioinformatics
  - AD scores for DREB2A tiles
  - Alignment of DREB2A used to obtain the ABS motif. Some sequences were removed in the paper representation to reduce visual size of alignment.
  - Alignment of plant Med25ACID domains used for surface residue evolutional conservation.
  
## Source Data
This section contains data essential for replicating most findings presented in the main and supplementary figures and tables of our manuscript. Note that example data such as averaged kinetic traces might not be included but can be derived from the comprehensive datasets in respective directories.

## Accessibility and Use
For questions regarding data access and usage, please contact corresponding author.

## Citation Information
If you use this data in your research, please cite the paper.
This repository can be cited using DOIs available in under each specific release.

**Releases**\
*Prepublication, v1.0:* \
[![](https://zenodo.org/badge/DOI/10.5281/zenodo.10376118.svg)](https://doi.org/10.5281/zenodo.10376118)
