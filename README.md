# Image classification for recognize breed Jack Russell Terier from others 🐶
Implemented Inception v3 architecture with data preprocesing and further testing of the model on test samples.

## Dataset and its structure
Dataset was created using *bing_image_downloader* library. After automeded downloaded the images, they were checked for duplicates and conformity with the requests (manually). Some images have added manually to increase dataset. Checking the correct image format (.jpg) is implemented in the code. **The final dataset contains 536 samples and has such structure of data:**
- images
  - jack_russell
  - other_dog
- test_images

Input image size: 299x299x3.
## Performance
After evaluating, the final model has metrics:
- Train accuracy: 92.79%
- Train loss: 0.2336
- Test accuracy: 65.09%
- Test loss: 1.4785.

This model hasn't high accuracy on test values. The problem may be the small number of images in the dataset and overfitting after epoch 13. Eventually, *Test.ipynb*  implements prediction logic.

## Example
<p align = "center">
<img width="321" alt="Знімок екрана 2024-07-10 о 18 08 34" src="https://github.com/karkhotin/dogs-classification-inceptionV3/assets/54355397/e04cadbd-f5e1-4e0e-9727-6c5cbd8967c6">
</p>
