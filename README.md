# dabaxFiles


DABAX (DAtaBAse for X-ray applications) is a compilation of tables for x-ray applications with a collection of computer programs to access, visualize, and process these tables.

DABAX was created to unify the tabulated data (e.g., scattering factors and x-ray atomic cross sections) for different programs. 

It was used in XOP[1] and now in OASYS[2], via the python package DABAX[3]. 

The DABAX data files are well structured and customizable ASCII files. 
The data tables are often sorted by atomic number, nevertheless quantities referring to multi-atomic materials such as compounds and crystals may also be included.

This DABAX data directory contains a set of files that provides the basic data for photon-atom cross sections and scattering factors (dispersive and non dispersive components). It also contains files for atomic constants and atomic composition of compounds and crystals. 

The DABAX concept allows one the flexibility to include new data and to update existing data.  The user can add or change the files to ensure that the basic physical quantities correspond to the chosen model. DABAX can be used to store information from either theoretical computations or experimental measurements (for example, files with experimental XAFS spectra are available). 

[1] XOP: http://dx.doi.org/10.1117/12.893911 http://dx.doi.org/10.1117/12.560903 http://dx.doi.org/10.1117/12.332522 

[2] https://www.aps.anl.gov/Science/Scientific-Software/OASYS

[3] https://github.com/oasys-kit/dabax
