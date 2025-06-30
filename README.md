## Billiard Game Mapping

The repository holds all processes used for detecting/classifying billiard balls and segmentation of the surface play area of a table.

It contains Jupyter notebooks for:

1. Dataset Preprocessing.
2. YOLO detection/segmentation model training.
3. Mapping of billiard balls from image to numerical form via Homography.

### Ball Classes

- 0 --> cue_ball
- 1 --> 8_ball
- 2 --> stripe
- 3 --> solid

### Table Class

- 0 --> surface play area

### Example

![Mapping_Example](https://github.com/user-attachments/assets/7edc9096-f2cf-4389-acd9-7763d4974103)
