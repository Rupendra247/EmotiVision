# EmotiVision

Real-time facial emotion detection using Python.

Detects faces via webcam (or from an image) and classifies the emotion — e.g., happy, sad, angry, fear, surprise, neutral — using [DeepFace](https://github.com/serengil/deepface) with OpenCV's Haar Cascade for face detection.

## Requirements

- Python 3.10+
- Webcam

## Installation

```bash
pip install opencv-python deepface matplotlib
```
## use conda environment
 install anaconda 
 create conda environment  -------> conda create --name myenv
 activate the environment  -------> conda activate myvemnv



## Usage

Run the notebook:

```bash
jupyter lab final.ipynb
```

Then run all cells (`Shift+Enter`). The last cell opens your webcam and overlays the detected emotion live. Press `q` to quit.

<!--  ## Files

| File | Description |
|------|-------------|
| `final.ipynb` | Main notebook |
| `Untitled.ipynb` | Development / testing notebook | -->
