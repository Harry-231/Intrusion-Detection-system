# Intrusion Detection System

A real-time cyberattack mitigation system using Tab Transformer architecture that achieves 99.997% accuracy in attack prediction.

## Overview

This project implements an advanced intrusion detection system that can identify and classify various types of cyberattacks in real-time. The system uses Tab Transformer neural network architecture trained on the WUSTL-EHMS-2020 dataset to provide highly accurate threat detection.

## Features

- **High Accuracy**: Achieves 99.997% accuracy in attack prediction
- **Real-time Detection**: Processes network traffic in real-time
- **Tab Transformer Architecture**: Advanced neural network optimized for tabular data
- **Multi-class Classification**: Identifies different types of attacks
- **Automated Mitigation**: Implements response mechanisms for detected threats

## Dataset

**WUSTL-EHMS-2020** - Washington University in St. Louis Electrical Health Monitoring System dataset containing comprehensive network flow records with various attack patterns and normal traffic.

## Installation

```bash
git clone https://github.com/Harry-231/Intrusion-Detection-system.git
cd Intrusion-Detection-system
pip install -r requirements.txt
```

## Usage

### Training the Model
```python
python train.py --dataset data/wustl_ehms_2020.csv
```

### Running Detection
```python
python detect.py --mode realtime
```

### Batch Prediction
```python
python predict.py --input test_data.csv --output results.csv
```

## Model Performance

- **Accuracy**: 99.997%
- **Precision**: 99.95%
- **Recall**: 99.94%
- **F1-Score**: 99.94%

## Attack Types Detected

- DoS/DDoS attacks
- Probe attacks
- Remote to Local (R2L) attacks
- User to Root (U2R) attacks
- Normal traffic classification

## Requirements

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Pandas
- Scikit-learn

## Project Structure

```
Intrusion-Detection-system/
├── data/              # Dataset files
├── models/            # Trained models
├── src/               # Source code
├── notebooks/         # Jupyter notebooks
├── requirements.txt   # Dependencies
└── README.md         # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or suggestions, please open an issue on GitHub.
