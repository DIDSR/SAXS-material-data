# SAXS-material-data

>> INTRODUCTION TO THE SAXS MATERIAL DATABASE

The files in this repository are small-angle x-ray scattering (SAXS) cross section data of materials obtained with a laboratory SAXS system.

>> FORMAT

Each individual file contains a header section with relevant material information (eg. material, thickness, density, concentration for colloids) and a SAXS instrument section that details the energy of the x-ray source, wavelength, sample-to-detector distance, and exposure time used to obtain the data contained in the file.

Below the header is tab-delimited data, organized into two columns. The data is in the format of intensity, I(q) vs. scattering vector, q.
All data is on the absolute scale with I(q) units of cm^-1 and q units of A^-1.
The first column contains values for q. The second column contains values for I(q).

>> REFERENCE

A full study detailing the motivation for this work, the methods for obtaining the data, and implications and potential applications can be found in the cited:

Alam, N., Choi, M., Ghammraoui, B., Dahal, E., & Badano, A. (2017). Small-angle x-ray scattering cross-section measurements of imaging materials. Biomedical Physics & Engineering Express, 3(2), 025023. doi:10.1088/2057-1976/aa6720

