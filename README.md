Synthetic Camera Obstruction Video Dataset
This repository contains a synthetic dataset of videos simulating camera obstructions using semi-transparent overlays (e.g., hand images) on a neutral background. The dataset is created to aid research and development in video analysis, particularly for testing algorithms designed to detect camera obstructions or occlusions.

Dataset Details
Number of Videos: 5

Video Duration: Each video ranges from 3 to 5 minutes in length.

Resolution: 640x480 pixels

Frame Rate: 25 FPS

Obstruction Events: Each video contains 3 to 4 obstruction periods.

Obstruction Duration: Each obstruction event lasts between 5 to 7 seconds.

Overlay: The obstructions are simulated using hand images with alpha transparency, randomly positioned on each frame during obstruction periods.

Background: Videos have a consistent neutral gray background with minor color variation per video.

Included Files
Videos: .mp4 files containing the synthetic obstruction videos.

Annotations: JSON files accompanying each video detailing the start and end frames of obstruction events.

Summary: An Excel spreadsheet summarizing all obstruction events across the dataset for easy reference and analysis.

Purpose
This dataset is designed for:

Evaluating camera obstruction detection algorithms.

Benchmarking occlusion handling techniques in video processing.

Training models that require annotated obstruction scenarios.

Usage
The dataset can be used directly in video processing pipelines or for machine learning experiments. The annotation files and Excel summary facilitate quick matching of obstruction time frames.
