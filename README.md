# RoseBlooming-Dataset
This repository contains the instruction for the RoseBlooming dataset. The RoseBloomingdataset allows for stage-specific flower detection. 
The dataset, consisting of overhead images, contains two rose cultivars and was filmed over a period of months.

## Highlights
* 519 images obtained from actual farms
* 2 classes depend on growth stage: rose_small, rose_large
* Include 2 rose cultivars
* provide in coco format

## Dataset Structure
RoseBlooming dataset Google Drive [link](https://drive.google.com/drive/folders/1I7_3vqDzZNIPwwqqOph1MrEqo8ZxAy0r?usp=sharing) 
```
├── train
│   ├── train_annotations.coco.json
│   ├── train_{image_id}.jpg
├── valid
│   ├── valid_annotations.coco.json
│   ├── valid_{image_id}.jpg
├── test
    ├── test_annotations.coco.json
    ├── test_{image_id}.jpg
```

* RoseBlooming consist of three files {train / valid / test}
* The .jpg files are the input images, and the .json files contain annotation information.
