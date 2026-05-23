# Millicharged-Dark-Matter Haloscope Recast

This repository contains the manuscript sources for a master thesis project. The code is used to recast published axion-haloscope limit data into constraints on millicharged dark matter. C and power.ipynb also compute the mDM response to different cavity modes of a circular cylindrical cavity.

The recast is intended to reproduce the haloscope sensitivity data shown in previous haloscope experiments. Configurations that require a dedicated mode-specific millicharged-dark-matter overlap, such as the QUAX dielectric-cavity runs, are listed in the code but skipped by the simple TE011-cylinder conversion.

The output files contain two columns: the millicharged-dark-matter mass `m_phi` in eV and the corresponding fractional-charge limit `epsilon_m = e_m/e`.

IMPORTANT: The Axion-photon limits come from https://cajohare.github.io/AxionLimits/, as some of the base code.
