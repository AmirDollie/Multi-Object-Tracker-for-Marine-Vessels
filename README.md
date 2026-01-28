# Multi-Object-Tracker-for-Marine-Vessels
This repository contains all the relevant resources and MATLAB files generated in making a Multi-Vessel tracking system, specialized for MIT's SeaGrant AUV database.
This project was conducted under the supervision of Yaaseen Martin for the completion of my EEE3000X vacation work.

To run the relevant MATLAB files on your own computer, you will need to change all the filenames inside the MATLAB files to direct to the ones stored on your PC. Moreover, the SeaGrant AUV dataset must be downloaded from their own website as it is approximately 8GB, please find it here: https://seagrant.mit.edu/auvlab-datasets-marine-perception-2-3/#toggle-id-4

File a1 trains shipDetectorV1 which identifies the ships from one another (does not work well on other videos).

File a3 trains the detector on a single class (ship) using YOLOX and an adam solver.  

File a4 is the final output of the system, tracking multiple ships and associating ID's and velocity vectors. It contains multiple iterations of the program, showing the new implementations and improvements made sequentially.

To download the video outputs, download the onedrive folder with password M@r1t1m3: https://uctcloud-my.sharepoint.com/:f:/g/personal/dllami004_myuct_ac_za/IgAU7fUjqsoZQ74M2-6ClDUnATT4MTytZAEgOfmUam7VxM8?e=Dfhgpg

