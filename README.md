# BRA Aptamer Sequence Datasets

This repository contains sample datasets generated using the **Base Randomization Algorithm (BRA)**, as described in our manuscript.

## Files

- **Mseqs_df1.csv**: Contains aptamer-like RNA sequences generated from initial input parameters using BRA. These sequences follow user-defined base distributions and sequence constraints.
- **Mseq_array.csv**: A second BRA-generated dataset, referred to as `Mseq[]` in the manuscript. This dataset serves as a replicate to validate output consistency and reproducibility.

## Purpose

These datasets were used to:

- Analyze base composition and sequence entropy.
- Perform statistical evaluations (ANOVA, normality tests).
- Assess structural properties such as Minimum Free Energy (MFE).
- Demonstrate the robustness and reproducibility of the BRA algorithm.

## Usage

These files can be used as input for:

- Secondary and tertiary structure prediction.
- Integration with tools like T-SELEX for 3D modeling and docking.
- Benchmarking synthetic aptamer libraries for machine learning training.

## Reference

Please cite the following if you use these files in your work:

> Mokgopa, K.P.; Oloniiju, S.D.; Lobb, K.A.; Tshiwawa, T. Benchmarking the Base Randomization Algorithm as a Possible Tool for the Initial Step of Generating a Virtual RNA Aptamers Library. BioTech 2025, 14, 72. https://doi.org/10.3390/biotech14030072 

---

For more details, see the full manuscript and the upcoming [T-SELEX](https://github.com/CMCDD/T_SELEX) tool for large-scale structural modeling and application workflows.
