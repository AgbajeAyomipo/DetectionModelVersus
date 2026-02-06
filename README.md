# DetectionModelVersus
**A Real-World Benchmark of Modern Object Detection Models**

## Overview
Detector Arena is a long-running benchmark project focused on training, evaluating, and comparing state-of-the-art object detection models using both quantitative metrics and real-world video inference.

Every week, two models are trained under identical conditions, evaluated, and compared. Results are published publicly and discussed on LinkedIn.

## Models Covered
- YOLO11 (n, s, m, l, x)
- YOLO26 (n, s, m, l, x)
- RT-DETR (l, x)
- RF-DETR (Nano, Small, Medium, Large, XLarge, 2XLarge)

## Evaluation Focus

### Accuracy Metrics
- mAP@50
- mAP@50:95
- Precision
- Recall

### Performance Metrics
- Inference FPS
- Latency per frame
- GPU memory usage

### Real-World Video Behavior
- Stability across frames
- Performance on motion blur
- Small object detection
- Occlusion handling

## Weekly Benchmark Format
- Two models trained per week
- Identical datasets, augmentations, and training schedules
- Side-by-side video inference
- Public metrics tables
- Results released every Thursday

## Hardware
All experiments are run on consistent hardware to ensure fair comparison.
See hardware.md for full details.

## Results
- Weekly results are stored in the benchmarks directory
- Aggregate comparisons are available in leaderboard.md
- Video inference outputs are stored in results/videos

## Why This Project?
Most benchmarks focus only on static accuracy metrics. DetectorModelVersus emphasizes:
- Practical deployment behavior
- Compute efficiency
- Visual detection quality in motion

This makes the results more useful for real-world production systems.

## Author
Agbaje Ayomipo  
Data Scientist | Computer Vision Enthusiast

Weekly insights and breakdowns are shared on LinkedIn(
