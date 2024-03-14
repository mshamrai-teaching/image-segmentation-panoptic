# Computer Vision Course Assignment: Panoptic Segmentation with MMDetection

## Overview

Welcome to the Panoptic Segmentation assignment for the Computer Vision course! In this task, your goal is to use [MMDetection](https://github.com/open-mmlab/mmdetection) and a provided [video](https://www.youtube.com/watch?v=Atkp8mklOh0) to create a side-by-side video. This output video should showcase both the original frames and their corresponding frames with panoptic segmentation masks applied, utilizing a model trained for panoptic segmentation.

### Getting Started

1. **Explore the MMDetection framework:**
  - Go to the GitHub repository.
  - Read the docs.
  - Find appropriate tutorials for the task.

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/image-segmentation-panoptic-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd image-segmentation-panoptic-*your-name*
      ```

### Guidelines

* MMDetection:
  * Utilize MMDetection to perform panoptic segmentation on the video frames.
  * Use the pre-trained panoptic segmentation model for inference.
* Video Processing:
  * Download the video from YouTube.
  * Implement a script to process the video frames. You can cut and use any part of the video that is at least 10 seconds long.
  * Generate a side-by-side video with original and masked (predicted) frames. 
* Evaluation:
  * The quality of the side-by-side video will be evaluated based on visual inspection.
 
### Hints

* Model Inference:
  * Refer to the MMDetection documentation for guidance on model inference.
* Video Processing:
  * Explore video processing libraries (e.g., OpenCV) for efficient frame handling.
  * You may want to downscale the original frames for the inference, but make sure to upscale masks after the inference.
  * Also you may want to reduce FPS for the inference (e.g. to 24 frames per second), but don't forget to change it back. 

### Submission

To submit your solution commit your files to the `main` branch. 

Ensure your final submission includes:
* Source code (video_masking_mmdetection.py or similar).
* The generated side-by-side video showcasing original and masked frames.

### Evaluation

Your solution will be evaluated based on the quality of the side-by-side video. Ensure that the panoptic segmentation masks align accurately with the objects in the original frames.

Good luck, and may your panoptic segmentation video creation be a success! If you have any questions, feel free to reach out.
