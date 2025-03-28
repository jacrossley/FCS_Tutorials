# Fluorescence Correlation Spectroscopy Notebooks

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

