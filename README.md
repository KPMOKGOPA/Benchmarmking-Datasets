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

> Kabelo, P. et al. *Benchmarking Base Randomization Algorithm as Possible Tool for the Initial Step of Generating Virtual RNA Aptamer Libraries*. (2025, under review)

---

For more details, see the full manuscript and the upcoming [T-SELEX]((https://github.com/CMCDD/T_SELEX) tool for large-scale structural modeling and application workflows.
