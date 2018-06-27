# show_attend_tell
Neural ImageCaption Geenerator

# Pre-requisites:
Tensorflow with anaconda,(and conda environment with python 3.6)(https://www.tensorflow.org/install/).
After creating the conda environment, simply install all dependencies from the files:
conda-requirements.txt and pip-requirements.txt.
Use the commands mentioned in these fiies.

# Usage:
1) Download the folder here: [https://drive.google.com/drive/folders/1DeZPUyIWliDrh7IRUYehr2v64uCCd5Bh?usp=sharing] and place it in utils/coco/pycocoevalcap/meteor/data.
2) Download all the files here: [https://drive.google.com/open?id=1Kx37OeRxfysKjE_fpV-lvwKJqNI6YB29] and place all its contents in /models.
3) Place the test images in /test/images, run the command written in com.txt. Results will be stored in /test/results.

# Training: (Incomplete)
1) Download the COCO train2014(~13GB) and val2014(~6.6GB) data here(http://cocodataset.org/#download) along with the annotations(241MB).
2) Put the COCO train images in /train/images and val images in /val/images.
3) Put the file captions_train2014.json in the folder /train.
