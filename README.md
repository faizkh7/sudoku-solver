### Preprocessing

The initial preprocessing steps involve cleaning up the image and preparing it for analysis.

![Preprocessing](screenshots/ss1.jpg)

---

### Adaptive Median Filtering

Adaptive median filtering is applied to remove noise while preserving edges.

![Adaptive Median Filtering](screenshots/ss2.jpg)

---

### Gaussian Blur and Adaptive Thresholding

To enhance contrast, Gaussian blur is combined with adaptive thresholding.

![Gaussian Blur and Adaptive Thresholding](screenshots/ss3.png)

---

### Contouring and 4-Point Transform

Contours are detected, and a 4-point perspective transform is applied to isolate the region of interest.

![Contouring and 4-Point Transform](screenshots/ss4.png)
![Contouring and 4-Point Transform](screenshots/ss5.png)

---

### Cell Extraction and Digit Masking

#### Number 8 - Cell and Mask
![Number 8 - Cell and Mask](screenshots/ss6.png)

#### Number 1 - Cell and Mask
![Number 1 - Cell and Mask](screenshots/ss7.png)

#### Empty Cell - No Mask Generated
This step shows how empty cells are identified with no mask generated.

![Empty Cell](screenshots/ss8.png)

---

### Optical Character Recognition (OCR)

OCR is used to recognize digits or characters from each extracted cell.

![OCR Results](screenshots/ss9.png)

---

### Output Superimposed (Image Write)

The recognized digits are superimposed onto the original image as an output, showing the results of the entire pipeline.

![Output Superimposed](screenshots/ss10.png)
