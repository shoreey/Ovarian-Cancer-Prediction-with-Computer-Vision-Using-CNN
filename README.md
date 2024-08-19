# Predicting Per-Surgical Outcomes of Ovarian Cancer Using CNN

## Project Overview
This study develops a deep learning Convolutional Neural Network (CNN) model to predict surgical outcomes for ovarian cancer patients based on pre-operative abdominal CT scans. The goal is to create a tool for stratifying patient outcomes and potentially improving surgical planning and decision-making.

## Dataset
- Approximately 192 patients who underwent surgery for ovarian cancer
- Pre-operative abdominal CT scans

## Methodology

### Data Preprocessing
- Image preprocessing techniques applied to CT scans
- Data augmentation to increase dataset size and diversity

### Model Development
- CNN architecture implemented using TensorFlow or PyTorch
- Multiple convolutional layers, pooling layers, and fully connected layers

### Model Training
- Trained for 100 epochs
- Recorded metrics: train loss, train accuracy, validation loss, validation accuracy

### Model Evaluation
- Performance evaluated on test set
- Metrics: accuracy, precision, recall

## Results
- The model achieved high accuracy on the test set
- Training accuracy increased over epochs
- Validation accuracy initially increased, then decreased (indicating overfitting)

## Key Findings
1. CNN shows potential for predicting surgical outcomes in ovarian cancer patients
2. Model performance suggests effective learning from CT scan features
3. Overfitting observed in later epochs, indicating need for regularization techniques

## Limitations
1. Small sample size (192 patients)
2. Dataset from a single clinic, potentially limiting generalizability
3. Model only considers CT scans, not other relevant factors (age, medical history, cancer stage)

## Future Work
1. Validate results on larger, more diverse datasets
2. Evaluate model performance on different subgroups (e.g., different cancer stages)
3. Incorporate additional patient factors for more comprehensive predictions
4. Implement regularization techniques to address overfitting

## Technologies Used
- Python
- TensorFlow or PyTorch
- Libraries for image processing and data augmentation

This project demonstrates the application of deep learning techniques in medical imaging analysis, specifically for predicting surgical outcomes in ovarian cancer patients. It highlights the potential of AI in improving patient care and surgical planning in oncology.
