Aerial Object Detection with YOLOv8 (VisDrone)

A small comparison study of YOLOv8n vs YOLOv8s for detecting pedestrians, vehicles and other objects in drone (aerial) images. Aerial scenes are hard because objects are tiny, crowded and often partly hidden, which makes this a good test of small-object detection.

Results

Both models were trained on the same data subset with the same settings. Metrics are the best epoch on the validation subset.

Model	mAP@50	mAP@50-95
YOLOv8n	0.329	0.118
YOLOv8s	0.420	0.161

Moving from YOLOv8n to YOLOv8s improved mAP@50 by about 0.091 (roughly 27% relative) and mAP@50-95 by about 0.043. Inference on the validation images ran at about 6.5 ms per image on a Tesla T4.
Aerial Object Detection with YOLOv8 (VisDrone)

A small comparison study of YOLOv8n vs YOLOv8s for detecting pedestrians, vehicles and other objects in drone (aerial) images. Aerial scenes are hard because objects are tiny, crowded and often partly hidden, which makes this a good test of small-object detection.

Results

Both models were trained on the same data subset with the same settings. Metrics are the best epoch on the validation subset.

Model	mAP@50	mAP@50-95
YOLOv8n	0.329	0.118
YOLOv8s	0.420	0.161

Moving from YOLOv8n to YOLOv8s improved mAP@50 by about 0.091 (roughly 27% relative) and mAP@50-95 by about 0.043. Inference on the validation images ran at about 6.5 ms per image on a Tesla T4.
