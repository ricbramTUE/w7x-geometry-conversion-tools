# W7-X DAGMC Geometry Tools

This repository contains Python utilities developed to support the generation and management of DAGMC geometry models for Wendelstein 7-X (W7-X).

## Overview

The repository currently contains two scripts.

### 1. STEP to DAGMC

This script assesses whether a STEP geometry can be successfully converted into valid DAGMC files.

The workflow consists of:

1. Importing STEP geometry.
2. Validating geometry integrity.
3. Generating DAGMC-compatible H5M files.
4. Exporting VTK representations for visualization and verification.

The script was developed to support geometry preparation for neutronics simulations.

### 2. DAGMC Merging

This script merges H5M and VTK files originating from:

1. Different CAD components.
2. Separate geometry generation procedures.
3. Volume-by-volume DAGMC generation workflows.

The resulting merged geometry can be used directly in simulation workflows requiring a unified DAGMC model.

## Relation to Documentation

This repository accompanies the documentation:

*W7X OpenMC geometry documentation*

The scripts provided here correspond to the workflows described in that document.

## Status

This repository is intended as supplementary research software.

The tools are under active development and may be updated as the geometry workflow evolves.

## Author

**Riccardo Brambilla**
