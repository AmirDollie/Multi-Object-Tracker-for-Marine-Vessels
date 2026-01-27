# Multi-Object-Tracker-for-Marine-Vessels
This repository contains all the relevant resources and MATLAB files generated in making a Multi-Vessel tracking system, specialized for MIT's SeaGrant AUV database.
This project was conducted under the supervision of Yaaseen Martin for the completion of my EEE3000X vacation work.

To run the relevant MATLAB files on your own computer, you will need to change all the filenames inside the MATLAB files to direct to the ones stored on your PC. Moreover, the SeaGrant AUV dataset must be downloaded from their own website as it is approximately 8GB, please find it here: https://seagrant.mit.edu/auvlab-datasets-marine-perception-2-3/#toggle-id-4

File a1 trains shipDetectorV1 which identifies the ships from one another (does not work well on other videos).

File a3 train the detector on a single class (ship) using YOLOX and an adam solver. 

File a4 is the final output of the system, tracking multiple ships and associating ID's and velocity vectors.
