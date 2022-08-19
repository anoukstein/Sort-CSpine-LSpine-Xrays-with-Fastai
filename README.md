# Sort  CSpine & LSpine Xrays with Fastai using data from VinDr-SpineXR

- CSpine: frontal, lateral, oblique
- LSpine: frontal, lateral
- 250 images sorted by A. Stein, MD Radiology

### Original images from: 

### VinDr-SpineXR: An open dataset for spinal lesions detection and classification from radiographs

```Pham, H. H., Nguyen Trung, H., & Nguyen, H. Q. (2021). VinDr-SpineXR: A large annotated medical image dataset for spinal lesions detection and classification from radiographs (version 1.0.0). PhysioNet. https://doi.org/10.13026/q45h-5h59.```

10 epochs with Resnet34 yielded 100% accuracy.
Test on 300 images had 3 thoracic spine xrays that mistakenly ended up in the prediction dataset and one frontal LSpine that was only labeled as 'frontal' but had no body part designation. All other images were correct on visual validation.


Reference:
```Hieu T. Nguyen, Hieu H. Pham, Nghia T. Nguyen, Ha Q. Nguyen, Thang Q. Huynh, Minh Dao, and Van Vu, “VinDr-SpineXR: A deep learning framework for spinal lesions detection and classification from radiographs,” in Proceedings of the 2021 International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2021)```
