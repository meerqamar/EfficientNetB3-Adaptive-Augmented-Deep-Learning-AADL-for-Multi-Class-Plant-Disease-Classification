# Plant Disease Classification

## Comparative Analysis of AlexNet and EfficientNet-B0

This project compares two Convolutional Neural Network (CNN) architectures, AlexNet and EfficientNet-B0, for plant disease classification across three datasets.

## Models
- AlexNet
- EfficientNet-B0

## Datasets
1. New Plant Diseases Dataset
2. PlantDoc Dataset
3. Rice Leaf Disease Dataset

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Validation Results

| Dataset | Model | Accuracy | Macro F1 |
|---|---|---:|---:|
| New Plant Diseases | AlexNet | 98.70% | 98.68% |
| New Plant Diseases | EfficientNet-B0 | 99.74% | 99.74% |
| PlantDoc | AlexNet | 54.11% | 48.44% |
| PlantDoc | EfficientNet-B0 | 68.83% | 66.19% |
| Rice Leaf Disease | AlexNet | 85.92% | 84.66% |
| Rice Leaf Disease | EfficientNet-B0 | 88.27% | 86.68% |

## PlantDoc Official Test Results

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| AlexNet | 49.79% | 44.85% |
| EfficientNet-B0 | 62.66% | 59.93% |

## Repository Structure
- `notebooks/`: Main project notebook
- `results/`: Training curves, confusion matrices and comparison graphs
- `reports/`: Final research report

## Important Notes
- The original datasets are not included in this repository.
- PlantDoc official test results are based on 233 images.
- New Plant Diseases validation results should be interpreted with care until possible augmented-image overlap is audited.

## Author
**meerqamar**

GitHub: https://github.com/meerqamar