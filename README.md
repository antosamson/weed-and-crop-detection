# weed-and-crop-detection

This project is a Streamlit application that uses the YOLOv8 model to detect fractures, weeds, and crops in images, webcam feeds, and video files. The application provides visual bounding boxes and labels for the detected objects.

## Features
- **Image Upload**: Upload images and detect objects with bounding boxes and labels.
- **Webcam Support**: Real-time object detection using your webcam.
- **Video Input**: Upload a video and process frames every 10 seconds to detect objects.
- **Customizable Bounding Boxes**: Red bounding boxes for seeds and green bounding boxes for weeds.
- **Clear Labels**: Enlarged and clear labels for detected objects.

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Choose the mode of operation from the sidebar:
   - **Image Upload**: Upload an image file (`.jpg`, `.jpeg`, `.png`).
   - **Webcam**: Start the webcam for real-time detection.
   - **Video Input**: Upload a video file (`.mp4`, `.avi`, `.mov`).

3. View the processed output with bounding boxes and labels for the detected objects.

## File Structure
- `app.py`: Main application file.
- `requirements.txt`: List of required Python libraries.
- `best.pt`: YOLOv8 model weights (to be downloaded).

## Example Output

### Image Upload
Bounding boxes and labels for detected objects are displayed on the uploaded image. The detected class names are listed below the image.

### Webcam
Real-time detection with bounding boxes and labels displayed on the video feed.

### Video Input
Frames from the video are processed every 5 seconds, and the detected objects are displayed along with their class names.

## Dependencies
- Python 3.8+
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- Streamlit
- OpenCV
- Pillow


