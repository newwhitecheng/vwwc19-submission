# vwwc19_submission

* Team name: QTravelers
* Contact email: Hsin-Pai (Dave) Cheng (hsinpaic@qti.qualcomm.com), Jinwon Lee (jinwonl@qti.qualcomm.com), Parham Noorzad (pnoorzad@qti.qualcomm.com), Jamie Lin (jmlin@qti.qualcomm.com)
* Description of model architecture: We design a hardware-aware neural architecture search (NAS) method to discover the neural architecture that satisfy the constraints. Our searching method using memory, latency and accuracy as hard constraint. Our found neural architecture cell is named SwiftNet Cell. The overall architecture is conv-> SwiftNet cell 1 -> SwiftNet Cell 2 -> SwiftNet cell 3 -> flatten -> fully connected. The Detail hardware is explained in table 1.
* Four performance metrics:
  * Accuracy on the COCO minival set: 95.13%
  * Model size: 249.73KB
  * Peak memory usage: 200.70KB
  * Multiply-adds per inference: 57.40M
