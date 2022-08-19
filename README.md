# Sort-CSpine-LSpine-Xrays-with-Fastai
Sort CSpine &amp; LSpine Xrays with Fastai using data from VinDr-SpineXR

# Sort  CSpine & LSpine Xrays with Fastai

- CSpine: frontal, lateral, oblique
- LSpine: frontal, lateral
- 250 images sorted by A. Stein, MD Radiology

### Original images from: 

### VinDr-SpineXR: An open dataset for spinal lesions detection and classification from radiographs

```Hieu T. Nguyen, Hieu H. Pham, Nghia T. Nguyen, Ha Q. Nguyen, Thang Q. Huynh, Minh Dao, and Van Vu, “VinDr-SpineXR: A deep learning framework for spinal lesions detection and classification from radiographs,” in Proceedings of the 2021 International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2021)```

10 epochs with Resnet34 yielded 100% accuracy.
Test on 300 images had 3 lumbar spine xrays that mistakenly ended up in the prediction dataset and one frontal LSpine that was only labeled as 'frontal' but had no body part designation. All other images were correct on visual validation.
