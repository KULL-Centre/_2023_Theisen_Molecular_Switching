# Theisen2023MolecularSwitching
This repository accompanies the 2023 manuscript by Theisen et al., titled 'Molecular switching in transcription through splicing and proline-isomerization regulates stress responses in plants.' The study delves into the complex molecular dynamics of transcriptional regulation in plant stress responses, shedding light on the role of proline-isomerization.

Key findings include the identification of a bivalent region in the transcription factor DREB2A, crucial for its interaction with the ACID domain of the Med25 component of the mediator complex. The research innovatively combines NMR and AF2 modeling to elucidate and verify the complex structure of the Med25-ACID and DREB2A interaction. Given the complexity of the Med25-ACID:TF complexes, CEST NMR was pivotal in revealing the bound state nuances of DREB2A. This technique has unearthed a heterogeneous bound state influenced by a specific proline residue within the primary motif. Furthermore, carbon chemical shift data indicate that the secondary motif's structure varies based on the proline conformation, with corresponding differences in affinity and dissociation rates.

The data are foundational in understanding these intricate interactions, offering a valuable resource for advancing our knowledge in the field of plant stress response regulation and mediator interactions.

**Manuscript Status**: Accepted for Nature Communications, 2024

**Preprint**: [Research Square](https://www.researchsquare.com/article/rs-3034274/latest) 

## Data Description
This repository is organized into several sections, each representing a different aspect of our study:

### NMR (Nuclear Magnetic Resonance)
  - DREB2A NMR data contains CEST profiles in a raw format. WT DREB2A was recorded using 500 µM DREB2A and 25 µM Med25ACID. Carbon CEST profiles were recorded at 25 °C.
    - For assistance with processing of CEST data, contact authors.
  - Med25ACID NMR data contains chemical shifts of the unbound state and D2a titrations, relaxation rates and hetNOEs. Assignment and titration data was obtained at 25 °C at pH 6.5 using BestTrosy pulse sequences.
    - Also contains MICS output for free Med25ACID and Med25ACID with DREB2A ABS.
    - Titrations>CSP Excel files contains Med25ACID CSPs for the three DREB2A fragment titrations.

### ITC (Isothermal Titration Calorimetry)
  - Raw .itc files are provided. Concentrations given in file should be correct.
  - Spolar Record structuring analysis data is also provided in an Excel file.

### Stopped-Flow (Fluorescence Kinetics)
  - Contains raw fluorescence traces. Indicated concentrations are post mixing concentations.
  - Contains observed rate constants.
  - Includes biological replicate data for ABS-RIM association: individually fitted trace k_obs of four concentrations between 2 and 3.5 µM.

### SAXS (Small Angle X-ray Scattering)
  - Buffer subtracted scattering curve of Med25ACID_532-680 obtained from SEC-SAXS.

### MD (Molecular Dynamics)
  - 1.7 µs trajectory of Med25-ACID 548-680 as frames at 0.5 ns intervals.

### Med25ACID:DREB2A Complex Models
  - Contains all three AF2 models discussed in the paper.
  - Contains a cis proline version model 2, obtained through a 1 ns MD simulation.
### Bioinformatics
  - AD scores for DREB2A tiles
  - Alignment of DREB2A used to obtain the ABS motif. Some sequences were removed in the paper representation to reduce visual size of alignment.
  - Alignment of plant Med25ACID domains used for surface residue evolutional conservation.
  - Protein sequences of Med25ACID 532-680 and key DREB2A fragments
  - Sequences defining the ABS motif
  
## Source Data
This section contains data essential for replicating most findings presented in the main and supplementary figures and tables of our manuscript. Note that example data such as averaged kinetic traces might not be included but can be derived from the comprehensive datasets in respective directories.

## Accessibility and Use
For questions regarding data access and usage, please contact corresponding author.

## Citation Information
If you use this data in your research, please cite the paper.
This repository can be cited using the 'Latest Release' DOI or DOIs available in under each specific release.

**Latest Release**\
*Static DOI that always points toward the latest release*\
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10376117.svg)](https://doi.org/10.5281/zenodo.10376117)

**Specific Releases**\
*Publication, v2.0*\
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10409674.svg)](https://doi.org/10.5281/zenodo.10409674)

*Preprint, v1.0:* \
[![](https://zenodo.org/badge/DOI/10.5281/zenodo.10376118.svg)](https://doi.org/10.5281/zenodo.10376118)
