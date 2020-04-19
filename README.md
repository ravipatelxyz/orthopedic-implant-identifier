# orthopedic_implant_identifier
## Developing a neural network to identify the model of orthopedic implant in an x-ray image

#### Context

Accurate identification of orthopedic implant design is essential to pre-operative planning of revision arthroplasty and verification of magnetic resonance imaging compatibility. Current systems are inadequate, associated with poorer patient surgical outcomes, significant time burdens on clinical staff, and increased healthcare costs.

We have therefore developed a neural network classifier for identifying the model of metallic joint implants from plain film radiographs (x-ray images), and have published our findings. Our Kaggle Kernel entitled "OrthopedicImplantIdentifier" allows readers of our publication to try using our model to identify implants in radiographs.

#### Content

This dataset contains:
implantxraystest_dataset - The classification test dataset used in our published study, containing radiographs (x-ray images) of 8 models of orthopedic hip implant and 4 models of orthopedic knee implant. There are 15 radiographs of each implant model. This was used as a test set to evaluate the accuracy of our final network during the study.
Three networks (two classification, one segmentation) that are ensembled together to produce our final network model (see how this is achieved in our associated "OrthopedicImplantIdentifier" Kaggle Kernel.
Please note that we do also intend to make radiographs from our full training and validation datasets available in due course.

#### For full details of how the dataset was collated, our network, and our study

Please see our associated peer-reviewed publication.

#### Authors and acknowledgements
Authors and acknowledgements can be seen in our associated peer-reviewed publication.
