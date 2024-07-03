# Image classification for recognize breed Jack Russell Terier from others 🐶
Implemented Inception v3 architecture with data preprocesing and further testing of the model on test samples.

## Dataset and its structure
Dataset was created using *bing_image_downloader* library. After automeded downloaded the images, they were checked for duplicates and conformity with the requests (manually). Some images have added manually to increase dataset. Checking the correct image format (.jpg) is implemented in the code. **The final dataset contains 536 samples and has such structure of data:**
- images
  - jack_russell
  - other_dog
- test_images

## 
