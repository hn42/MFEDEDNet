# MFE-DEDNet
Multi-dimensional Feature Extraction based Deep Encoder-Decoder Network for Automatic Surface Defect Detection 


Abstract
The control of surface defects is of critical importance in manufacturing quality control systems. Today, automatic defects detection using imaging and deep learning algorithms has produced more successful results than manual inspections. Thanks to these automatic applications, manufacturing systems will increase the production quality, and thus financial losses will be prevented. However, since the appearance and dimensions of the defects on the surface are very variable, automatic surface defect detection is a complex problem. In addition, very few surface defect images in the data sets are available to use in the training of deep models. This situation creates an insufficiency for training deep learning architectures containing millions of parameters. In this study, Multi-dimensional Feature Extraction based Deep Encoder-Decoder Network (MFE-DEDNet) network developed to solve such problems. The proposed network contains far fewer parameters than the state-of-the-art methods based on deep learning in the literature. In addition, thanks to the 3D Spectral and Spatial Features Extract (3DFE) module included in the proposed model, deep spectral and spatial features as well as deep semantic features are obtained. In this way, high success has been achieved with surface-defect-detection datasets containing few images. Experimental studies were conducted using MVTec and MT datasets to evaluate the performance of the MFE-DEDNet network. The experimental results achieved 80.01% and 56% mean Intersection over Union (mIoU) scores for the MT and MVTec datasets, respectively, using the proposed MFE-DEDNet network. In these results, it was observed that the proposed model achieved excellent success compared to other state-of-the-art methods. 



The Python code for our proposed method


MT Dataset: https://github.com/abin24/Magnetic-tile-defect-datasets
MVTec dataset: https://www.mvtec.com/company/research/datasets/mvtec-ad
