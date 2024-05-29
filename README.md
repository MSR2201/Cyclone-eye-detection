# Cyclone Eye Detection
Detecting the cyclone eyes plays a vital role in predicting their tracks accurately, especially in tropical regions. The primary source of data for such predictions is satellite images. To teach computer systems to identify cyclone centers, we need a vast amount of data to train deep learning models. This project introduces a new technique called Image Augmentation-based Object Translation. Here, the 'object' refers to the cyclone itself.
The method involves extracting the cyclone from images andrelocating it to various positions within the same image. By carefully replacing the cyclone's original position, we significantly expand the dataset, providing more diverse examples for the computer to learn from.
The developed technique aims to augment the datasetphenomenally, enhancing the information available for training models. With this expanded dataset, we trained a sophisticated model called YOLO (You Only Look Once). YOLO is renowned for its exceptional object detection capabilities and is widely used today. Using this model, we achieved an impressive accuracy rate of above 89% in pinpointing the cyclone's eye. This accurate identification of the cyclone's eye signifies a crucial step forward in improving our ability to predict cyclone tracks, contributing to more reliable and precise weather forecasting techniques.
