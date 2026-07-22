## Abstract

This repository provides a Python and Jupyter Notebook workflow for processing and visualizing Angle-Resolved Photoemission Spectroscopy (ARPES) measurements of Bismuth Selenide ($\text{Bi}_2\text{Se}_3$).

* **Dataset Overview:** Uses `BiSe_232deg_38p7nm_static_6.h5` to capture static photoelectron emission intensities mapped across energy and angle dimensions.
* **Experimental Setup:** Features measurements from a SPECS Phoibos electron analyzer using $38.7\text{ nm}$ extreme ultraviolet (EUV) radiation ($\approx 32.04\text{ eV}$ photon energy).
* **Spectrometer Settings:** Records band dispersions centered at a kinetic energy of $28.0\text{ eV}$ with a $30.0\text{ eV}$ pass energy.
* **Workflow Capabilities:** Unpacks the raw HDF5 dataset, calibrates energy and angular axes ($\theta \approx 24.5^\circ \text{ to } 72.1^\circ$), and plots 2D momentum maps to analyze topological surface states.
