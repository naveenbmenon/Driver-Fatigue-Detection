# Driver Fatigue Detection Using EEG Signals

## Overview
Driver fatigue is a major cause of road accidents worldwide. This project aims to detect driver fatigue using EEG (Electroencephalography) signals and machine learning models. By analyzing EEG data from subjects in different driving states, our system predicts signs of drowsiness and alerts the driver.

## Dataset
- EEG data collected from **twelve healthy subjects** using a **40-channel Neuroscan amplifier**.
- Data stored in **`.cnt` files** containing continuous EEG signals, timestamps, and metadata.
- Two states of driving process recorded: **alert (awake) and fatigued (drowsy).**

## Methodology
1. **Data Preprocessing**
   - Load and process **`.cnt` files**.
   - Filter noise and extract relevant EEG features.
2. **Feature Extraction**
   - Extract power spectral density (PSD), wavelet coefficients, and other EEG features.
3. **Model Training & Evaluation**
   - Machine learning models used:
     - **Support Vector Machine (SVM)**
     - **Logistic Regression**
     - **Random Forest**
     - **K-Nearest Neighbors (KNN)**
     - **Artificial Neural Networks (ANNs)**
   - Evaluation Metrics:
     - Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Techniques: Hyperparameter tuning, Cross-validation, Feature importance analysis
4. **Fatigue Detection & Alert System**
   - Real-time classification of EEG signals.
   - Generates an alert when fatigue is detected.

## Installation & Setup
### Prerequisites
- Python 3.x
- Required Libraries:
  ```bash
  pip install numpy pandas scipy scikit-learn tensorflow mne matplotlib seaborn
  ```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/driver-fatigue-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd driver-fatigue-detection
   ```
3. Run the data preprocessing script:
   ```bash
   python preprocess.py
   ```
4. Train the models:
   ```bash
   python train.py
   ```
5. Evaluate the models:
   ```bash
   python evaluate.py
   ```
6. Run the real-time detection system:
   ```bash
   python detect.py
   ```

## Results
- **Accuracy Achieved**: (To be filled after model evaluation)
- **Best Performing Model**: (To be determined)
- **Confusion Matrix & ROC Curves**: Included in `results/` directory.

## Contributors
- **[Harish J ]** ([@GitHub](https://github.com/harishjanarth)) 
- **[Aditya Varma]** ([@GitHub](https://github.com/justvarma)) 

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- References: Research papers on EEG-based fatigue detection.

## Contact
For queries, open an issue or reach out at [naveenbijulalmenon@gmail.com , harishjanarth@gmail.com].

