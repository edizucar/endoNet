# endoNet - Image segmentation for diagnosing endometriosis

We use [nnUNet](https://github.com/MIC-DKFZ/nnUNet).
- Needs 10GB GPUs + 64GB RAM. We will need to use Cambridge's compute cluster.
- Using conda for environment.
- Testing using (Breast Cancer Dataset)[https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset]
- We need to be very careful about (dataset format)[https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/dataset_format.md] its really easy to do it wrong.
- We are using the (hippocampus set)[http://medicaldecathlon.com/] to help teach us the formatting. BUT it is in the old format. See (this tool)[https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/convert_msd_dataset.md] also on how to convert an MSD dataset.
