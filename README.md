# Alphabet Soup Funding Application Classification

## Project Overview

This project focuses on developing a deep learning model to predict the success of funding applications submitted to Alphabet Soup, a charitable organization. The goal is to create a binary classification model that efficiently classifies applications as either successful or unsuccessful based on various features.

## Project Structure

### Files

- `AlphabetSoupCharity.ipynb`: Jupyter Notebook containing the code for data preprocessing, model development, and evaluation.
- `AlphabetSoupCharityOpt.ipynb`: Jupyter Notebook containing the code for data preprocessing, model development, and evaluation of the optmized model. 
- `checkpoints/`: Directory to save model checkpoints during training.
- `AlphabetSoupCharity.h5`: Saved model file in HDF5 format.

### Dependencies

- `pandas`: Data manipulation and analysis.
- `tensorflow`: Deep learning library for building and training neural networks.
- `scikit-learn`: Tools for machine learning tasks.
- `numpy`: Mathematical operations.

## Instructions

1. **Setup:**
   - Install the required dependencies.

2. **Data Preparation:**
   - Obtain the dataset from the provided link.
   - Run the data preprocessing steps in `AlphabetSoupCharity.ipynb`.

3. **Model Development:**
   - Adjust model architecture and hyperparameters as needed.
   - Train the model using the provided data.

4. **Model Evaluation:**
   - Evaluate the model performance on a separate test set.
   - Save the trained model to `AlphabetSoupCharity.h5`.

## Additional Notes

- The model architecture, preprocessing steps, and results are documented in the Jupyter Notebook.

## References

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [IRS Tax Exempt Organization Search Bulk Data Downloads](https://www.irs.gov/Links)
