# Millicharged-Dark-Matter Haloscope Recast

This repository contains the manuscript sources for a master thesis project. and the analysis code used to recast published axion-haloscope limit data into constraints on millicharged dark matter. In particular, `scripts/rescale_admx.py` converts AxionLimits axion--photon limits from ADMX, HAYSTAC, ADMX Sidecar, and the simple cylindrical QUAX configurations into limits on the fractional millicharge `epsilon = e_m/e`, using the frequency relation `m_phi = m_a/2` and the cavity-overlap assumptions described in the manuscript.

The recast is intended to reproduce the haloscope sensitivity data shown in previous haloscope experiments. Configurations that require a dedicated mode-specific millicharged-dark-matter overlap, such as the QUAX dielectric-cavity runs, are listed in the code but skipped by the simple TE011-cylinder conversion.

The output files contain two columns: the millicharged-dark-matter mass `m_phi` in eV and the corresponding fractional-charge limit `epsilon_m = e_m/e`.

IMPORTANT: The Axion-photon limits come from https://cajohare.github.io/AxionLimits/, as some of the base code.
