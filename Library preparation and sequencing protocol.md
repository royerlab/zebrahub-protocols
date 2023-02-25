# Library preparation and sequencing protocol

This experimental protocol outlines the steps to perform single-embryo single-cell RNA sequencing on zebrafish embryos using the Chromium Single Cell Controller and scRNA-seq libraries constructed with the Chromium Next GEM Single Cell 3’ Reagent Kit v3.1 and Single Cell 3’ Reagent Kit v3.1 HT.

## Materials:

- Zebrafish embryos (10 hpf to 10 dpf)
- Cellometer auto T4 Cell Counter
- Chromium Single Cell Controller (10x Genomics)
- Chromium Next GEM Single Cell 3’ Reagent Kit v3.1
- Single Cell 3’ Reagent Kit v3.1 HT
- BioRad C1000 Touch Thermal Cycler
- Agilent 4200 TapeStation / High Sensitivity D5000 Screentape
- Kapa Library Quantification kit for Illumina
- NovaSeq run kits with either single or dual index plates
- PhiX control library

## Procedure:

1. Prepare single cell suspensions from zebrafish embryos (e.g. conduct protocol above).
2. Count the cells using the Cellometer auto T4 Cell Counter and adjust the concentration to be between 700-1200 cells/ul.
3. Process the single cell suspensions through droplet emulsions using Chromium Single Cell Controller according to the manufacturer’s instructions.
4. Construct scRNA-seq libraries using Chromium Next GEM Single Cell 3’ Reagent Kit v3.1 for 10 hpf to 1 dpf and Single Cell 3’ Reagent Kit v3.1 HT for 2 dpf to 10 dpf, following the manufacturer’s instructions.
5. Load single cells into each channel of the Chromium Single Cell Controller with the appropriate amount of diluted RT master mix based on the measured cell concentration and targeted cell recovery per sample.
6. Perform Fragmentation, Ligation and PCR Amplification using BioRad C1000 Touch Thermal Cycler with thermal profiles specified in the 10X Genomics User Guide CG000204.
7. Evaluate amplified cDNA and final libraries using Agilent 4200 TapeStation / High Sensitivity D5000 Screentape and qPCR with Kapa Library Quantification kit for Illumina.
8. Normalize each library to 4 nM and pool for each NovaSeq sequencing run.
9. Add PhiX control library at 1% to the pools.
10. Sequence the libraries on the NovaSeq 6000 Sequencing System (Illumina) using NovaSeq run kits with either single or dual index plates.
