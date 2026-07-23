# Binary Image Classification with a CNN

A TensorFlow/Keras notebook that trains a convolutional neural network to
classify images into two labeled categories and evaluates predictions on
sample images.

## Reported experiment

- 10 training epochs
- Best training accuracy: 98.83%
- Best validation accuracy: 95.05%

These values are notebook results for the original split and should not be
interpreted as performance on a broader population.

## Run

```bash
git clone https://github.com/CHAITANYA2605/man-and-women-classifier-using-cnn.git
cd man-and-women-classifier-using-cnn
python -m venv .venv
source .venv/bin/activate
pip install jupyter tensorflow numpy matplotlib opencv-python
jupyter notebook main.ipynb
```

Update dataset paths in the notebook before training. The `test/` directory
contains sample images used for inference.

## Responsible use

Inferring gender from appearance is reductive, can encode dataset bias, and
does not represent a person's gender identity. This repository should be
treated as a limited image-classification exercise, not as a system for
high-stakes or real-world identity decisions.
