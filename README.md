
# Industrial Defect Detection using Computer Vision

A computer vision project for detecting potentially defective industrial products using anomaly detection, developed for the Kaggle **Defect Vision – Industrial Defect Detection Challenge**.

## Project Overview

Industrial quality inspection often requires identifying products whose appearance differs from normal products. This project explores an image-based anomaly detection approach to distinguish normal samples from potentially defective ones.

The project is implemented in a Jupyter notebook and developed in the Kaggle competition environment.

## Project Details

- **Domain:** Computer Vision and Machine Learning
- **Task:** Industrial anomaly and defect detection
- **Approach:** PatchCore-style visual anomaly detection
- **Environment:** Kaggle, Python, Jupyter Notebook
- **Notebook:** [`LATEST.ipynb`](./LATEST.ipynb)

## Dataset

The competition covers the following product categories:

- Bottle
- Cable
- Hazelnut
- Screw

The dataset is provided through the Kaggle competition. The original competition data is not included in this repository.

To reproduce the work, obtain access to the competition dataset and configure the notebook's data paths for your Kaggle environment.

## Methodology

The notebook implements an image-based anomaly detection workflow. The general approach is to:

1. Load and prepare the industrial product images.
2. Extract visual features for anomaly analysis.
3. Calculate anomaly scores to identify samples that differ from normal examples.
4. Apply category-aware decision thresholds to classify samples.
5. Generate predictions in the format required by the competition.

See the notebook for the implementation details and configuration.

## Results

The best competition result reported during development was an **F1 score of 0.88**.

This is a reported competition-submission result, not an independently reproduced benchmark. Results may depend on the exact notebook version, parameters, and submitted prediction file.

## Repository Structure

```text
defect-vision-industrial-defect-detection/
├── LATEST.ipynb    # Main detection notebook
├── README.md       # Project documentation
├── .gitignore      # Files excluded from Git
└── LICENSE         # Repository license, if selected
```

## Tools and Technologies

- Python
- Jupyter Notebook
- Kaggle
- Computer Vision
- Image Feature Extraction
- Anomaly Detection
- Git and GitHub

## Limitations

- Competition test labels are not available for local evaluation.
- The reported F1 score should be verified against the corresponding Kaggle submission.
- Predictions and thresholds may need recalibration when the model or dataset changes.
- This project is an experimental competition solution and is not a validated industrial safety system.

## Future Improvements

- Add visual examples of normal and anomalous products.
- Document model parameters and dependencies.
- Evaluate performance separately for each product category when ground-truth labels are available.
- Improve reproducibility with configuration files and saved evaluation results.

## Author

**Umair Shaikh**

GitHub: [MD-Umair-Shaikh2005](https://github.com/MD-Umair-Shaikh2005)

---

*Developed as a machine learning and computer vision project for industrial defect detection.*
