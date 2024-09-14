# Object-detection-used-for-livestock-count

# Livestock Detection using YOLOv8

This project uses the YOLOv8 model for object detection to identify livestock in images and videos. The code is designed to process an entire folder of images and videos, detect livestock in each, and save the detected results. It allows users to upload a dataset, which can contain images and videos, process them using the YOLOv8 model, and then download the results.

## Features

- Batch Processing: Processes all images and videos in a given folder.
- Object Detection: Uses YOLOv8 for livestock detection in images and videos.
- Structured Output: Saves detected results in a structured folder format.
- Downloadable Results: Provides the processed results in a downloadable zip file.

## Requirements

- Python 3.x
- [Ultralytics](https://github.com/ultralytics/ultralytics)
- OpenCV
- Google Colab (for running the code)

## Usage

1. Upload the Dataset: Run the script and upload your dataset as a zip file when prompted.
2. Process the Dataset: The script will automatically detect and process all images and videos in the uploaded dataset.
3. Download the Results: After processing, a zip file containing the detected results will be available for download.

## Code Walkthrough

### Upload and Extract Dataset

The script first allows you to upload a zip file containing your dataset. The zip file is extracted into a directory (`datasets_folder`).

### Processing Images and Videos

- Images: The script iterates through each image file, processes it with the YOLOv8 model, and saves the detected results in a structured folder.
- Videos: Similarly, videos are processed frame-by-frame, and the output is saved in the same structure.

### Download Results

After processing, the script provides a zip file containing all the detected results for easy download.

## Example Output

The processed images and videos will be saved in a folder called `detected_datasets`. Each image will have a corresponding file with detected bounding boxes. Videos will be saved with detected frames.

## Note: If the image or video dataset is not working , There will be a problem in fromat. So use some other video or image datasets of format .mp4 or .jpg

## Contact: skmsince2005@gmail.com

