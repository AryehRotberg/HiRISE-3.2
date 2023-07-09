# HiRISE-3.2

In this project I will be using a pretrained model ResNet50V2 to classify mars landmarks orbital images to replicate the results of the "Deep Mars" paper by Wagstaff et al.

#### Contents:
- map-proj-v3_2/: Directory containing individual cropped landmark images
- labels-map-proj_v3_2.txt: Class labels (ids) for each landmark image
- labels-map-proj_v3_2_train_val_test.txt
- labels-map-proj_v3_2_classmap.csv
- Data/: Directory containing all the landmark images
        - **labels-map-proj_v3_2.txt**: Directory containing individual cropped landmark images
        - **labels-map-proj-v3_2.txt**: Class labels (ids) for each landmark image. File includes two columns separated by a space: filename, class_id
        - **landmarks_map-proj-v3_2_classmap.csv**: Dictionary that maps class ids to semantic names
- Models/ResNet50V2/: Directory containing saved ResNet model used in the project
- HiRISE Jupyter.ipynb - Jupyter notebook containing model training
- HiRISE Presentation.pdf - Presentation containing insights and project explanation

## Author

**Aryeh Rotberg**

## Acknowledgements 
The data used in this project comes from the DOI:
10.5281/zenodo.2538135

Gary Doran, Emily Dunkel, Steven Lu, & Kiri Wagstaff. (2020). Mars orbital image (HiRISE) labeled data set version 3.2 (3.2.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4002935
Idea for this project and the data originates from the following paper: 

Kiri Wagstaff, Steven Lu, Emily Dunkel, Kevin Grimes, Brandon Zhao, Jesse Cai,
Shoshanna B. Cole, Gary Doran, Raymond Francis, Jake Lee, and Lukas Mandrake "Mars Image Content Classification: Three Years of NASA Deployment and Recent Advances" The Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI-21)
