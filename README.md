## SensUs competition 2021 image acquisition&processing code
The evolution of antibody substrates in the microfluid chip under microscope as \
<img src="https://user-images.githubusercontent.com/58901415/160095690-d2f959de-1879-49bf-b1ac-ebc988ae1b42.gif" width="46%" height="46%" />

The image acquisition&processing code works to
* Remove noise from the captured images, processed experimental data
* Do curve fitting, obtain the calibration curve mapping foreground signal to true concentration of the protein

The code is very effective and our estimation of concentration is the most accurate among all the teams \
<img src="https://user-images.githubusercontent.com/58901415/160096887-7eb374c5-bcb5-4bb1-8b65-a06becdb3c3b.png" width="48%" height="48%" /> \
We are winner of the Analytical Performance Award this year and 2nd Prize of Translation Potential Award \
<img src="https://user-images.githubusercontent.com/58901415/160097188-cca2405d-3a09-4c6c-826b-074f96c559fd.png" width="21%" height="21%" />
### How to use 
* `/images`: put the images to be analysed in this folder 
* `/images_processed`: where the processed images will be saved
* `run_processing_analysis`: file to run to load images, select ROI, do pre-processing and analysis
