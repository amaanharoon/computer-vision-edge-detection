# Computer Vision Hackathon

A computer vision notebook covering classic edge detection, image segmentation, feature
extraction, and CNN-based classification techniques, built for the CST4245 Computer Vision
module.

## Contents

- **Task 1** — Loading and displaying an image, first edge detection pass
- **Task 2** — First-order derivative edge filters (e.g. Sobel) and second-order derivative filters
- **Task 3** — Multi-stage edge detection algorithm (Canny)
- **Task 4** — Image segmentation using thresholding
- **Task 5** — Feature extraction using Histogram of Oriented Gradients (HOG)
- **Task 6** — Image segmentation using K-Means clustering
- **Task 7** — CNN for image classification (MNIST / CIFAR-10)
- **Task 8** — Additional independently explored technique

## Files

| File | Description |
|---|---|
| `MISIS_M01106791-AmaanHaroon.ipynb` | Main notebook with all tasks |
| `image.jpg` | Sample image used for the edge detection / segmentation tasks |
| `requirements.txt` | Python packages needed to run the notebook |

## Getting started

Clone the repo and install the dependencies:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
jupyter notebook MISIS_M01106791-AmaanHaroon.ipynb
```

## Requirements

- Python 3.9+
- See `requirements.txt` for the full package list (OpenCV, NumPy, Matplotlib, Pandas,
  TensorFlow, scikit-image, scikit-learn)

## Notes

- Task 7 downloads its dataset (MNIST/CIFAR-10) automatically via TensorFlow/Keras the first
  time it runs, so an internet connection is needed for that cell.
