# Helmet-Detection

## Task Description

The project aims to train a neural network to detect two classes in images and videos:
- Safety helmets
- Human heads without helmets

## Dataset

The [Hard Hat Universe](https://universe.roboflow.com/universe-datasets/hard-hat-universe-0dy7t) dataset was utilized, containing 4912 images in the train set. The dataset includes 5 label types: 'head', 'helmet', 'hi-viz helmet', 'hi-viz vest', and 'person'. During data preparation, the dataset was cleaned by removing unnecessary labels and empty images without labels, resulting in only images with 'head' and 'helmet' labels remaining.

## Model

A pre-trained YOLOv8 model was used, which was fine-tuned on the cleaned dataset to improve detection accuracy.

## Repository Contents

- Video_helmet_detection.ipynb: Contains the code for the entire process, including data preparation, model training, and prediction.
- weights/best.pt: Contains the weights for the fine-tuned YOLOv8 model.

## Detection Examples

![val_batch2_pred (2)](https://github.com/user-attachments/assets/5c42cec8-a8de-4a4a-ab82-b81dbda33f4a)

![image_2024-07-29_23-31-48](https://github.com/user-attachments/assets/dc2ce29f-07ed-4755-aad9-dca073058cd2)

