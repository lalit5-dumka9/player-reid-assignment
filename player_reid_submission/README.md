# Player Re-Identification in Sports Footage

This project solves the task of identifying the same player across two different video feeds using object detection and feature-based matching.

## Project Structure

```
├── main.py
├── utils.py
├── data/
│   ├── broadcast.mp4
│   └── tacticam.mp4
├── weights/
│   └── yolov8_player.pt
├── README.md
└── report.md
```

## Setup Instructions

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install ultralytics opencv-python numpy scikit-learn
```

## Run the Code

```bash
python main.py
```

## Requirements

- Python 3.8+
- OpenCV
- PyTorch (via Ultralytics)
- Numpy
- scikit-learn