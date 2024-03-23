# Pneumonia_Detection


# Pneumonia Detection from Chest X-Ray Images
This project aims to detect pneumonia from chest X-ray images using machine learning techniques. Chest X-ray images are important tools for diagnosing pneumonia, and automating this process can help speed up diagnosis and treatment.

## Illustrative Examples
Illustrative examples of chest X-ray images from pneumonia patients

* Normal Chest X-ray: Clear lungs without any areas of abnormal opacification in the image.
Bacterial Pneumonia: Focal lobar consolidation, typically in the right upper lobe.
* Viral Pneumonia: A more diffuse "interstitial" pattern in both lungs.
## Dataset Content
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). It consists of 5,863 chest X-ray images (JPEG) distributed across 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients aged one to five years from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

## Model Used
We utilized the pre-trained VGG16 model to extract features from chest X-ray images. VGG16 is a deep convolutional neural network (CNN) that has been pre-trained on a large dataset of natural images. By using the VGG19 model, we were able to capture important visual features from chest X-ray images, contributing to the accuracy of our pneumonia detection system.

## Acknowledgements
* Link to the data: https://data.mendeley.com/datasets/rscbjbr9sj/2
* License: CC BY 4.0
