# RoseBlooming-Dataset
This repository contains the instruction for the RoseBlooming dataset. The RoseBloomingdataset allows for stage-specific flower detection. 
The dataset, consisting of overhead images, contains two rose cultivars and was filmed over a period of months.
More details can be found in our paper [RoseTracker: A system for automated rose growth monitoring](https://doi.org/10.1016/j.atech.2023.100271).

<img src="roseblooming.png" src="500px">

## Highlights
* 519 images obtained from actual farms
* 2 classes depend on growth stage: rose_small, rose_large
* Include 2 rose cultivars
* provide in coco format

## Dataset Structure
RoseBlooming dataset Google Drive [link](https://drive.google.com/drive/folders/1I7_3vqDzZNIPwwqqOph1MrEqo8ZxAy0r?usp=sharing).  
Non-commercial research purposes only.
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

## Citation
@article{SHINODA2023100271,  
title = {RoseTracker: A system for automated rose growth monitoring},   
journal = {Smart Agricultural Technology},  
volume = {5},  
pages = {100271},  
year = {2023},  
issn = {2772-3755},  
doi = {https://doi.org/10.1016/j.atech.2023.100271},  
url = {https://www.sciencedirect.com/science/article/pii/S2772375523001004},  
author = {Risa Shinoda and Ko Motoki and Kensho Hara and Hirokatsu Kataoka and Ryohei Nakano and Tetsuya Nakazaki and Ryozo Noguchi},  
}
