# monkey-species-transfer-learning
# 🔍 Exploratory Analysis: ANN Limitations on Image Data
## Objective
This notebook performs a structured exploratory analysis to evaluate how different image preprocessing techniques impact the performance of a standard Artificial Neural Network (ANN) on an image classification task.

## Motivation
Rather than optimizing for maximum accuracy, the goal of this exercise is to understand the limitations of ANN architectures when applied to image data.

We intentionally vary the input representations:
- RGB (full information)
- Grayscale (reduced color information)
- Gaussian Blur (noise reduction / smoothing)
- Laplacian (edge-only features)

## Key Question
Can preprocessing alone enable an ANN to effectively learn image features?

## Hypothesis
Even with feature engineering, ANN models will struggle due to their inability to preserve spatial relationships between pixels.

This experiment sets the foundation for understanding why Convolutional Neural Networks (CNNs) are more effective for image tasks.
