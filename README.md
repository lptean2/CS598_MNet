## Usage
To use this implementation, obtain the datasets with instructions shown below.
Run the Brats_dataloader.ipynb sequentially to create the BraTS dataloader, MNet model, and train the model.
Run the Kits_dataloader.ipynb sequentially to create the KiTS dataloader, MNet model, and train the model.


## Datasets
KiTS: https://kits19.grand-challenge.org/data/
The data can be obtained from the Github repository https://github.com/neheller/kits19. After cloning, run /starter_code/get_imaging.py to load original images into the data directory. Move the data directory to /Data/kits19 to obtain the structure /Data/kits19/data
BraTS: https://www.kaggle.com/code/asmahekal/brain-tumor-mri-segmentation/input
This data can be obtained by downloading the BraTS2020_TrainingData directory into the /Data directory and renaming it to brats to obtain the structure /Data/brats
