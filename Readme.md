GLAUCOMA SEGMENTATION using Convolutional Neural Network


Problem: Glaucoma is the second leading cause of blindness all over the world, with approximately 60 million cases reported worldwide in 2010. Glaucoma causes irreversible damage to the optic nerve leading to blindness.

Dataset: DRIONS_DB(110), DRISHTI_GS(50), RIM-ONEv1(169), v2(455) & v3(159)

Total Images: 943

Data Preparation: Cropped the OD area, resized to 128,128,3 and normalized all the images

Model: Tried out different neural network models

Evaluation: IOU score and Dice score

Conclusion: Worked really well with RIM-ONEv2(455) dataset only
