# retail-video-analytics
A Proof of Concept (PoC) system that transforms retail surveillance camera feeds into actionable business insights through video analytics.

## Overview
This project demonstrates the capability to:
- Process overhead retail surveillance video footage
- Detect and track multiple people simultaneously in the video frame
- Generate structured JSON data containing:
  - Precise positioning of each person (using bounding boxes)
  - Temporal tracking with timestamps
  - Unique identification of individuals across frames

## Files
- `people-tracking.ipynb`: A demo Jupyter notebook that detect and track multiple people in the video clip. Generate output as annoated video and JSON data file.
- `heatmap.ipynb`: A demo Jupyter notebook that generate people heatmap from the video clip. Generate output as annoated video.
- `analytics.ipynb`: A demo Jupyter notebook that shows how to perform analytics with the JSON data file for visualization and findings.
- `genai-vision.ipynb`: A demo Jupyter notebook that leverage Generative AI vision capability to get description from the frame sequences of the video clip.