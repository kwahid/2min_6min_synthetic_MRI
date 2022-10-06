# Deep-Learning-Based Generation of Synthetic 6-Minute MRI from 2-Minute MRI for Use in Head and Neck Cancer Radiotherapy

## Repo for code related to Synthetic MRI project. Pre-print available at: https://www.medrxiv.org/content/10.1101/2022.06.19.22276611v1. Manuscript currently under peer-review, when accepted link will be updated here. Corresponding image sets used for this project are avaliable on Figshare (doi: 10.6084/m9.figshare.20099252). All data has been anonymized to remove patient PHI. <br>

### This repo contains the following files in the directory titled "Code": <br>
Jupyter notebook of DICOM to NIfTI file conversion scripts (DICOM_to_nifti.ipynb) - This notebook contains all the code neccessary to generate NIfTI version of the source image files so they are easier to use in anayses scripts. <br>

Jupyter notebook of auto-segmentation analysis (Autoseg_analysis.ipynb) - This notebook contains all the code neccessary to replicate Figure 3 of the manuscript and associated results. <br>

Jupyter notebook of manual segmentation analysis (Manual_segmentation_analysis.ipynb) - This notebook contains all the code neccessary to replicate Figure 4 of the manuscript and associated results. <br>

Jupyter notebook of image similarity analysis (Image_similarity_analysis.ipynb) - This notebook contains all the code neccessary to replicate Table 1 and Figure 6 of the manuscript and associated results. <br>

Jupyter notebook of visual Turing Test analysis (Turing_test.ipynb) - This notebook contains all the code neccessary to replicate Table 1 and Figure 5 of the manuscript and associated results. <br>

CSV files associated with Turing test analysis (Turing_test_slice_key_v2_FULLYANONYMIZED_FINAL.csv, Turing_test_subset_information_withanonkey_v2_FULLYANONYMIZED_FINAL.csv) - CSV files that were used as intermediates in generating Turing test results. <br>

Excel files associated with Turing test analysis (Turing_test_v2_obs1.xlsx, Turing_test_v2_obs2.xlsx, Turing_test_v2_obs3) - Excel files that each observer produced when perfomring the visual Turing test; used for analysis. <br>

### Utilized the following core Python (version 3.9.7) libraries in project: <br>

DicomRTTool version 0.4.2. <br>
SimpleITK version 2.1.1.<br>
Pydicom version 3.3.2.<br>
Matplotlib version 3.3.2.<br>
Pandas version 1.3.4. <br>
Pinguoin version 0.5.1. <br>
Radiomics (pyradiomics) version 3.0.1. <br>
Seaborn version 0.11.2. <br>
Rpy2 version 3.5.0. <br>
Scipy version 1.7.1. <br>

### Note: The Jupyter Notebook is quite large, which may present difficulties when trying to view it through the online Github browser preview. To successfully view it in the online Github browser you may need to download the notebook and then navigate back to the corresponding page.  

### For more information on the Fuller lab and associated projects please visit: https://www.mdanderson.org/research/departments-labs-institutes/labs/fuller-laboratory.html. 
