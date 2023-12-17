# Dataset Overview
This dataset comes with 5000 quality images for training. The images are from superficial fungal infections caused by yeasts, moulds, or dermatophyte fungi. The images have been manually labelled into five classes and curated with a subject matter expert assistance. The images have been cropped with automated algorithms to produce the final dataset.

You can find the reference article of the dataset at P456 Defungi: direct mycological examination of microscopic fungi images. There are 5 subfolders, representing the following fungi types:

* H1: Candida albicans
* H2: Aspergillus niger
* H3: Trichophyton rubrum
* H5: Trichophyton mentagrophytes
* H6: Epidermophyton floccosum

# Results
* The model showed the highest precision score for the H6 class and the lowest for the H2 class.
* If we consider f1 score as a measure for the overal performance of the model, our model's performance is as follow: H6, H5, H1, H3, and H2. for H2, the model's performance was just a little bit higher than 0.5.
* The overall accuracy, as discussed, was 76.8% after 30 epochs.

# Future actions
* We can run the tuned vgg16 model for a higher number of epochs like 50 or more
* In addition, we can add a more advanced top to the base model. The top layers i used were the simplest ones for the structure.
* We can test other base models like InceptionV3, MobileNet and ... and compare the results.
