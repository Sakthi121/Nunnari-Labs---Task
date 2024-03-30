# Video Analysis Internship Assignment

## Overview

Welcome to the Video Analysis Internship Assignment repository! This project aims to analyze a provided video dataset within the time period from March 26, 2023, to April 2, 2024. The main objective is to extract valuable insights from each frame of the video, including identifying distinct faces, detecting text using Optical Character Recognition (OCR), generating descriptive captions for each frame, and crafting a narrative based on the extracted information.

## Tasks

### Facial Recognition

Utilizing a frame extraction rate of one frame per second (FPS), the script extracts each frame from the video and identifies unique faces appearing in the footage. It also counts the occurrences of each unique face throughout the video and determines the most frequent face.

### Text Detection and OCR

Each frame of the video is analyzed to detect and extract text content using OCR techniques. If a specific text is provided for search, the script retrieves the timestamps when it appears in the video.

### Image Captioning

Descriptive captions are generated for each frame using advanced image captioning techniques, ensuring accurate representation of the visual content.

### Story Generation

By leveraging the captions generated for each frame, the script engages in prompt engineering using a large language model (LLM) to craft a compelling narrative. The narrative seamlessly weaves together the individual captions to form an engaging storyline.

## Deliverables

- **Detailed Report:** A comprehensive report outlining the analysis results, including occurrences of each unique face and identification of the most occurring face, extracted text with timestamps, generated image captions, and narrative construction details.
- **Code Implementation:** The repository includes code showcasing the methodology used for facial recognition, text detection, OCR, image captioning, and narrative generation.
- **Dataset:** The video dataset used for this analysis is available [here](https://www.youtube.com/watch?v=d2g9HlwoC-s).
- **Documentation:** Additional documentation explaining the code structure, usage instructions, and any dependencies required.

## Dataset

The video dataset used for this analysis is available [here](https://www.youtube.com/watch?v=d2g9HlwoC-s).

## Usage

To run the code and reproduce the analysis:

1. Clone this repository to your local machine.
2. Install any necessary dependencies as outlined in the documentation.
3. Execute the main script for video analysis, following the provided instructions.


