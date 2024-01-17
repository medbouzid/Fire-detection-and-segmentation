# Fire-detection-and-segmentation
This project addresses the critical issue of efficient and accurate fire detection and segmentation using advanced computer vision and deep learning techniques. The proposed novel architecture combines YOLOv5 and U-net models to overcome existing limitations and enhance performance.

## Motivation
Uncontrolled fires pose a global threat, causing extensive damage annually. Traditional detection methods fall short in coverage and real-time responsiveness. Leveraging deep learning, this project aims to provide a robust solution for precise fire detection and segmentation.

## Methodology
The project introduces a unique architecture that sequentially integrates YOLOv5 and U-net models. YOLOv5 identifies fire areas, and U-net precisely segments them. The resulting binary mask represents fire pixels, and bounding lines are overlaid on the original images.


## Implementation and Results
**Dataset**: Utilizes the Corsican fire database.
**Data Augmentation**: Applies flipping, cropping, image translation, MixUp, and Mosaic.
**Training**: YOLOv5 trained using PyTorch, U-net trained using TensorFlow.
**Metrics**: Precision, accuracy, mAP, and Dice coefficient.
**Results**: Highlights performance for YOLOv5s, YOLOv5x, and segmentation.
