# DL4WSICompression
Exploring Deep Learning Approaches to Whole Slide Image Compression code repository

1) Use git clone to download the files needed for running the experiments. 
2) Set up a Python environment with the dependencies from requirements.txt file in order to successfully run the code. 
3) Download the 'images.zip' folder from the following link to obtain the WSI files and tiled images for training and testing:
     https://qubstudentcloud-my.sharepoint.com/:u:/g/personal/3056243_ads_qub_ac_uk/EXThZoU8R8dCvNG8vw5EuxgBSmXKZRJmRC4-FQObLL2PTw?e=G4s47F 
4) Unzip and place the images folder at the base level of the DL4WSICompression folder.
5) Run each model from its .ipynb file.

Code available for all 4 models used in the paper is available in this repo as given in Jupyter notebook format. This can be run in Anaconda Navigator or in VS Code. 

Link to the WSI sources from The Cancer Genome Atlas from National Cancer Institute GDC Data Portal for more open source SVS files: https://portal.gdc.cancer.gov/analysis_page?app=Downloads

Link to Histoclean software for file preparation before training to remove tiles with over 50% white space: https://github.com/HistoCleanQUB/HistoClean
