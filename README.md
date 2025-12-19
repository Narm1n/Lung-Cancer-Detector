## Lung Cancer Detector

The lung cancer model was developed using a dataset containing CT scan images classified into four categories: Adenocarcinoma, Large Cell Carcinoma, Squamous Cell Carcinoma, and Normal. These represent different stages and types of lung conditions - three being cancerous and one non-cancerous (normal). To simplify the classification task and make the model clinically relevant, the images were grouped into two broader categories: cancerous (adenocarcinoma, large cell, squamous cell) and non-cancerous (normal).

Before training, the images underwent two main preprocessing steps. First, histogram equalization was applied to improve contrast, making important features more visible. Then, threshold segmentation converted images into binary format to highlight regions of interest while removing irrelevant background details.

The dataset was split using the SplitFolders library into 70% training, 10% validation, and 20% testing, ensuring balanced representation across all classes. But I need to point out that the dataset was too small, consisting of only 800 train and 200 test images. Because it was a little bit hard to find a good dataset.

### Dataset
Mohamed Hany. Chest CT-Scan images Dataset (2020).
https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
