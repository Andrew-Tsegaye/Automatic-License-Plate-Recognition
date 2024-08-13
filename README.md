# Automatic License Plate Recognition | Deep Learning

## Data

The video used to test the AI model can be found [here](https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/).

## Models

- **Vehicle Detection:** A YOLOv8 pretrained model was used for detecting vehicles.
- **License Plate Detection:** A license plate detector was trained using YOLOv8 with [this dataset](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/4).
- **Vehicle Tracking:** Utilized the Ultralytics COCO dataset to track vehicles.

## Dependencies

- **SORT Module:** The SORT module is required for tracking and can be downloaded from [this repository](https://github.com/abewley/sort).
