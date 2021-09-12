# Endoscropic-Image-Segmentation

Run training_and_testing.ipynb file for segmentation of endoscopic images.

## Preprocessing Steps:
1. Resize images and masks to (256, 256) using files provided in resizing_images_masks folder.
2. Run train_val_test_split.ipynb file with your original directories to split your dataset.
3. In order to increase your training data use augmentation.ipynb file in Augmnetation folder.

## Sample Image:
![image](https://user-images.githubusercontent.com/33062012/132995576-fdb38d5d-c6fa-4e13-ad08-c69127282938.png)

## Respective Mask (5-channel tif file):
![image](https://user-images.githubusercontent.com/33062012/132995602-dd41afa6-6ff8-4932-be02-74a01942dd2a.png)
