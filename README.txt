README.txt

Date: 26/09/2022
Contact: potchara.wongyai@gmail.com
Program: Data Science BootCamp
Institution: BrainStation, Toronto, Ontario



Plant Images Classification (PIC): Identify species of plant seedlings based on images



Project Summary Documents:
1 - Potchara_Wongyai_PIC_summary_report.pdf - This is the final report that summarizes the project
2 - Potchara_Wongyai_PIC_presentation.pdf - This is capstone slide deck used for the final presentation 2022/09/26



Jupyter Notebooks (can be run seperately):
1 - Plant_Images_Import_Clean.ipynb - This notebook imports images, pre-clean, and export dataset as numpy arrays
2 - Plant_Images_Classification_Notebook.ipynb - This notebook contains the workflow for data review, modelling, and evaluation

%%%%% IMPORTANT - TO RUN THE NOTEBOOKS %%%%%
- Plant_Images_Classification_Notebook.ipynb requires large RAM and GPU to run. Recommend a system with 32GB RAM and 24GB GPU.
- Ensure to save all files under Notebook_Files.zip in the same directory as Plant_Images_Classification_Notebook.ipynb
- Plant_Images_Import_Clean.ipynb requires to change working directory in within the notebook to locate 'train' folder in Dataset.zip


Files in Notebook_Files.zip: 
1 - X-Plant-224.npy
2 - y-Plant-224.npy
3 - lv1_model (folder with files)
4 - lv1_model_weight.hdf5
5 - lv1_model_history.pkl
6 - lv2_model (folder with files)
7 - lv2_model_weight.hdf5
8 - lv2_model_history.pkl



Files in Dataset.zip:
1 - test(folder) - contain 794 images
2 - train(folder) - contain 4750 images
(or download from https://www.kaggle.com/c/plant-seedlings-classification)