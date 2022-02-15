# Detection of Breast Cancer Cells

A Kaggle dataset.

Breast cancer detection from microscopy images


## About Data Collection Methodology

(1) "The BreaKHis database contains microscopic biopsy images of benign and malignant breast tumors. Images were collected through a clinical study from January 2014 to December 2014. All patients referred to the P&D Laboratory, Brazil, during this period of time, with a clinical indication of BC were invited to participate in the study. The institutional review board approved the study and all patients gave written informed consent. All the data were anonymized."

(2) "An Olympus BX-50 system microscope with a relay lens with magnification of 3.3× coupled to a Samsung digital color camera SCC-131AN is used to obtain digitized images from the breast tissue slides. This camera uses a 1/3” Sony Super-HAD (Hole-Accumulation Diode) interline transfer charge-coupled device with pixel size 6.5 μm ×  6.25 μm and a total pixel number of 752 ×  582. Images are acquired in three-channel red–green–blue (RGB) TrueColor (24-bit color depth, 8 bits per color channel) color space using magnifying factors of 40× , 100×, 200×, and 400×, corresponding to objective lens 4×, 10× , 20×, and 40×. The camera is set for automatic exposure and focusing is done manually on the microscope looking at the digital image on the computer screen."

Source:

FA Spanhol, LS Oliveira, C. Petitjean and L. Heutte, "A Dataset for Breast Cancer Histopathological Image Classification," in IEEE Transactions on Biomedical Engineering, vol. 63, no. 7, pp. 1455-1462, July 2016, doi: 10.1109/TBME.2015.2496264.


### Description of The Data

Directory description:

```

Root Dir/
  - test
    - benign
    - malignant
  - train
    - benign
    - malignant
  - runs
  - Breast-cancer-detection.ipynb
  - TensorBoard Training Example.png
  - README.md
  - LICENSE.md
  - .gitignore

```


### File Formats

Code is written in Python on Jupyter '.ipynb'.

The data set:

Training data and test data with different folders, each file has a different slide image obtained by light microscope at 400x optical zoom.


## Online Repository link

* [Data Repository](https://www.kaggle.com/forderation/breakhis-400x)


## Author

* [ofir-frd](https://github.com/ofir-frd)


## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](https://github.com/ofir-frd/BreaKHis-400X/blob/main/LICENSE) file for details


## Acknowledgments

* [Kharisma Muzaki from the Informatics Laboratory UMM.](https://www.kaggle.com/forderation)

* [FA Spanhol, LS Oliveira, C. Petitjean and L. Heutte, "A Dataset for Breast Cancer Histopathological Image Classification," in IEEE Transactions on Biomedical Engineering, vol. 63, no. 7, pp. 1455-1462, July 2016, doi: 10.1109/TBME.2015.2496264.](https://ieeexplore.ieee.org/document/7312934)
