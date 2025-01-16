# Trash-Detection-in-Ocean
Trash Detection  in Ocean using YOLOv8


**Introduction** 
YOLOv8, or You Only Look Once version 8, is a state-of-the-art deep learning model for object detection and instance segmentation tasks. It combines the efficiency of single-shot detection with the accuracy of instance
segmentation, making it suitable for real-time applications such as ours. Segmentation and detection in Digital Image Processing involve partitioning an image into meaningful regions (segmentation) and identifying specific objects or patterns within those regions (detection). These techniques play a crucial role in various applications, including medical imaging, surveillance,autonomous vehicles, and more.

**Dataset Overview**
The dataset used is the TrashCan 1.0 An Instance-Segmentation dataset to train the YOLOv8models. This dataset consists of underwater imagery to detect and segment trash in and around the ocean floor. The dataset contains 6008 training instances and 1204 validation instances. There are a total of16 classes in the dataset.

**Training YOLOv8 model**
The training process involves feeding the YOLOv8 model with the annotated dataset to learn the features and characteristics of different trash objects. Through iterative optimization algorithms, the model adjusts its parameters to minimize prediction errors and improve accuracy over time.

The model was trained according to the following parameters:
1. Number of epochs: 5
2. Number of batches : 16
3. Dataset: trashcan_inst_material.yaml
4. Model=yolov8m-seg.pt

**Results**
The model performed well in segmenting and detecting large objects such as plastic bottles, trash bags, metal trash, cans, fishing nets, Remote Operated Vehicals (ROVs), sea animals like eel, fishes etc with high precision. The ouput is obtained as segmented images and videos with class detected and its probability to be a correct detection.
