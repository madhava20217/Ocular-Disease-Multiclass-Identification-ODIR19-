# README

The project involves multilabel classification using the ODIR dataset.

The following files are of relevance:
1. Datasets/
2. Preprocessing.ipynb: preprocessing the CSV files and downloading the files
3. Histogram_Equi.ipynb: does histogram equalisation and preprocessing for the horizontally flipped images (for INCEPTION) and for histogram equlisation (FOR ENSEMBLED NETS).
4. Plots/ : plots
5. EfficientNet/: files pertaining to efficientnetV3
   -  Efficientb3_Ensemble_Baseline_DL_Project.ipynb: For ensembled, needs files in Saved_Models
   -  Efficientb3_GreyBaseline_DL_Project_Grey.ipynb: model on hist eq images without flipping
   -  Efficientb3_GreyBaseline_DL_Project_Grey_Preprocessed.ipynb: model on hist eq images with horizontal flipped images
   -  Efficientb3_NormalBaseline_DL_Project_Normal.ipynb: model on RGB images without horizontal flipping
   -  Efficientb3_NormalBaseline_DL_Project_Normal_Preprocessed.ipynb: model on RGB images on horizontal flipped images
6. InceptionV3/: files pertaining to InceptionV3
   - Inceptionv3_Baseline_DL_Project.ipynb: for inceptionv3, needs inception_v3.pt in directory for inference only.

The flow is as follows:
