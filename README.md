# Lung-Opacities-identification-using-Mask-RCNN

A Mask-RCNN was implemented to automatically detect pneumonia and locate lung opacities on chest radiographs. 26684 chest radiographs were obtained from the Radiological Society of North America for this purpose. 

This basic model gave an IoU value for test set of 0.063 on Mask-RCNN with Resnet50 as backbone and an IoU value for test set of 0.067 with backbone as Resnet101.

![Chest XRay with detected lung opacities](https://github.com/dhivyas93/Lung-Opacities-identification-using-Mask-RCNN/blob/master/Chest%20XRays%20with%20detected%20lung%20opacities.png)


### References
  * https://www.kaggle.com/drt2290078/mask-rcnn-sample-starter-code)
  * https://www.kaggle.com/hmendonca/mask-rcnn-and-coco-transfer-learning-lb-0-155
  * Matterport Mask-RCNN implementation : https://github.com/matterport/Mask_RCNN/tree/master/mrcnn
