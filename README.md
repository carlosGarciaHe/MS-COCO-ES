# MS-COCO-ES

## Description

MS-COCO-ES is a dataset created from the original [MS-COCO dataset](http://cocodataset.org).
This project aims to provide a small subset of the original image captions translated into Spanish by humans annotators.
This subset is composed by 20,000 captions of 4,000 images (5 captions per image).

Along with the previous subset, there are other subsets of MS-COCO in machine translated Spanish and original English that
have been used along with the main subset to carry out [1].

## Files

### Data

Files with the captions.

- **test.xlsx**: this file contains 5,000 human-translated captions that were used as test set in [1]
- **train_human_spanish.xlsx**: This file contain 10,000 human translated captions that were used as train set in [1]
- **train_machine_english.xlsx**: This file contains 100,000 human originals captions from train set MS-COCO that were used as train set in [1].
- **train_machine_spanish.xlsx**: This file contains 100,000 machine-translated captions (Deepl) that were used as train set in [1]. The captions are the same as those used in train_machine_english.xlsx.
- **validation.xlsx**: This file contains 5,000 human-translated captions that were used as validation set in [1].

### Images

All the images used in the data files for the image captioning.

### manual

A guide for the translators of the captions of test.xlsx, train_human_english.xlsx and validation.xlsx.

## Cite

If you use any of these files to develop your work, please cite this project. An example of valid cite is:
```
García C., MS-COCO-ES, (2020), GitHub repository, https://github.com/carlosGarciaHe/MS-COCO-ES
```

## Bibliography
