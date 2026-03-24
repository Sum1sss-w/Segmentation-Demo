# Segmentation-Demo
# Abstract
AML is a type of leukemic disease featuring mutation of myeloid lineage resulted in characteristic abnormality in myeloid cells and myeloblast. Diagnosis of AML are dependent on evaluation of flow cytometry and peripheral blood smear and marrow biopsy (with immunohistochemistry). With this in mind, we want to summit a prototype idea for using deep learning (CNN) model for screening and segmentation of blast and abnormal cells before being inspected by hematopathologist.
# Objective
The main task of this model is to perform a segmentation of a specified cells, these are: Promyelocyte, Myeloblast, Eosinophil, and Basophil. These are cells type that can be seen in normal and abnormal patient which required inspection of hematopathologist; we want to segment margin of these cells for hematopathologist to be able to inspect them without needing to scroll through the entire slide.
# Dataset
The dataset are obtained from 2 source: 
BCCD (Blood Cell Count and Detection) which is a small size open access data set of abnormal white blood cells found in peripheral blood smear [BCCD contain around 364 file of WBC in jpeg format]. 

The data are license under MIT, furthur information can be found in https://github.com/Shenggan/BCCD_Dataset/tree/master. 

TCIA AML(The Cancer Imaging Archive cases of AML) which is a large archive of cancer medical imaging around the world. 
In this case we downloaded archive of cells found in AML (acute myeloid leukemia) cases. The database contain 200 patients and 18,365 images; for this demonstration we use only a few images from the whole dataset. 

Additional Information can be found at https://doi.org/10.7937/tcia.2019.36f5o9ld Matek, C., Schwarz, S., Marr, C., & Spiekermann, K. (2019). A Single-cell Morphological Dataset of Leukocytes from AML Patients and Non-malignant Controls [Data set]. The Cancer Imaging Archive. https://doi.org/10.7937/tcia.2019.36f5o9ld.

# END REMARK

The notebook featured within this github repositories cannot be preview due to metadata output cell featuring slider and interactive prompt. Please download the raw file for notebook inspection or refered to original google colab file: https://colab.research.google.com/drive/1PAF3XGXV-3kl-2gNn-rx0JEC_8IJK2Ti?usp=sharing
