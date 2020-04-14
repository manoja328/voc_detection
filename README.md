# voc_detection
FastRCNN pytorch code for object detection for PASCAL VOC dataset. 
```
Backbone = ResNet50
Region proposals generator = edgeboxes 

Run: python train.py 
```
Put your dataset inside datasets/ folder.

This uses precomputed edgeboxes ( or any other method) as region proposals. You can change few lines in the train.py 
to use faster RCNN's RPN generator instead of edgeboxes or  different backbone.
