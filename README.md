# Roboflow Model Inference

This project demonstrates image classification using a Roboflow model. It processes images, draws bounding boxes, and creates a video of the results.

## Project Structure

- `dataset/input_images/`: Directory for input images.
- `dataset/output_images/`: Directory for processed images and video.
- `scripts/roboflow_model_inference.py`: Main script for processing images.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/roboflow_model_inference.git
   cd roboflow_model_inference
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your input images in the `dataset/input_images/` directory.

## Usage

Run the script to process images and create a video:
```bash
python scripts/roboflow_model_inference.py
```

## Results

Processed images and the output video will be saved in the `dataset/output_images/` directory.