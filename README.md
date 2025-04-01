# Fluorescence Correlation Spectroscopy Notebooks

This repository provides Jupyter notebook tutorials, written in Python, to guide researchers through key aspects of Fluorescence Correlation Spectroscopy (FCS) analysis. These notebooks cover fundamental principles and calibration techniques necessary for accurate FCS measurements.

This resource will be updated and expanded over time to include additional tutorials and tools for FCS data analysis.

If you're new to Jupyter Notebooks, start here: [Jupyter Notebook Beginner Guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/).

## Content
- **FCS_Calibration_Diffusion_Coefficients.ipynb** - This Jupyter notebook examines the temperature-dependent changes in fluorophore diffusion coefficients, providing values required for calibrating the confocal volume in Fluorescence Correlation Spectroscopy (FCS). The diffusion coefficients are calculated by accounting for temperature variations and solvent viscosity.

- **FCS_Determining_the_Confocal_Volume.ipynb** - This notebook provides a step-by-step approach to determining the effective confocal volume in FCS by analyzing a sample with a known diffusion coefficient. We begin by loading and fitting an autocorrelation curve of Fluorescein in water, then use the fit results to derive the effective confocal volume. This calibration is essential for obtaining accurate diffusion coefficients in quantitative FCS experiments.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- SciPy

## Contact
@author: Joel A. Crossley <br />
@email: j.a.crossley@leeds.ac.uk <br />
@institution: University of Leeds <br /> 
@department: Astbury Centre for Structural Molecular Biology, School of Molecular and Cellular Biology, Faculty of Biological Sciences
