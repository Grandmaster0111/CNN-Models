# CNN Models

A collection of deep learning object detection experiments using **Convolutional Neural Networks**.

## Models Included

### 1. Drone Detection (YOLOv8-based)
Located in `Dlone-Detection-nd-trackku-1/`
- Real-time drone detection and tracking using a custom-trained YOLO model
- Trained for 300 epochs on a drone detection dataset
- Outputs bounding boxes with tracking IDs across video frames

### 2. Faster R-CNN
Located in `Faster R-CNN/`
- Region-based CNN for object detection
- Two-stage detector: Region Proposal Network (RPN) + classification head
- Higher accuracy than single-stage detectors, suitable for offline analysis

## Prerequisites

```bash
pip install torch torchvision ultralytics opencv-python jupyter
```

## Usage

Open the notebooks in Jupyter:
```bash
jupyter notebook "dataset download.ipynb"
```

## Notes

> `myenv/` is a local virtual environment — do not commit it.  
> If cloning fresh, recreate it with: `python3 -m venv myenv && pip install -r requirements.txt`
