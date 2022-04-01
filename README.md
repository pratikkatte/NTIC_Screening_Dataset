# NTIC Screening Dataset

## About Niramai 
  [Niramai Health Analytix](https://www.niramai.com/) has developed a novel software-based medical device to detect breast cancer at a much earlier stage than traditional methods or self-examination. The core of  Niramai's solution is Thermalytix, a computer aided diagnostic engine that is powered by Artificial Intelligence. The solution uses a high resolution thermal sensing device and a cloud hosted analytics solution for analysing the thermal.

Niramai holds the ownership of this dataset and is opensourcing the NTIC Screening Dataset in an effort to help research community.


[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
  
## About the Niramai Thermal Imaging for Covid-19 (NTIC) Dataset:
  This dataset consists of thermal images of persons walking with and without wearing mask into public premises like offices, malls and
  railway stations. 
  The NTIC consist of 3 main folders corresponding three differet datasets.
  1. Thermal Surveillance Dataset.
  2. Augmented Surveillance Dataset.
  3. Lighting Dataset
  
## Data Folder:

**`Thermal Surveillance Dataset`** and **`Augmented Surveillance Dataset`**

```bash
.
└── Thermal Surveillance Dataset
    ├── images
    ├── labels
└── Augmented Surveillance Dataset
    ├── images
    ├── labels    
```

The images folder includes thermal images and labels folder includes .txt files containing face bounding boxes and mask labels of the corresponding images in YOLO format.




**`Lighting Dataset:`**
```bash
.
└── Thermal Surveillance Dataset
    ├── images
    ├── labels
└── Augmented Surveillance Dataset
    ├── images
    ├── labels    
```
- The lighting dataset consist of both thermal images and their corresponding visual images of 25 participants with and without wearing mask captured in different lighting conditions.
- For every subject, the dataset consists of images folder and labels folder.
- Images folder consists of visual image and thermal images.
- All the files in the images folder are named in the following format

  **`<file_number>_<NM (non_mask) or WM (with_mask)>_L<Lux intensity>.jpg`**
- Labels folder consist of .txt files containing face annotations and mask labels of the corresponding images. 

For any queries, contact at sivateja@niramai.com
