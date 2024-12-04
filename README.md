This project utilizes YOLOv8 for building footprint detection from satellite imagery, specifically targeting the Indian region. The dataset, sourced from Google Satellite, was preprocessed and converted into the YOLOv8 format using Roboflow to ensure proper annotation structure.

The YOLOv8 segmentation model (yolov8s-seg.pt) was trained on the processed dataset for 10 epochs with an image resolution of 512x512. The model's purpose is to accurately identify and segment building footprints in satellite images. The best-performing weights were saved and used to test the model on unseen data, generating precise predictions stored for further analysis and visualization.

This project demonstrates the effectiveness of YOLOv8 in geospatial tasks, providing a robust solution for building footprint detection in urban planning, disaster management, and similar applications.

output:-
![buildings](https://github.com/user-attachments/assets/1b4f160f-2beb-48aa-9804-bd38bb8b54b3)
