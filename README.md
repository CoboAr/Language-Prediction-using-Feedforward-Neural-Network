# Language Prediction using Feedforward Neural Network

This project demonstrates the use of a **Feedforward Neural Network (FNN)** to predict the language (Albanian or English) of sentences. The network is trained using four different loss functions, and its performance is evaluated on a set of test sentences in both languages.

## Project Overview

This project includes:
- A **Feedforward Neural Network** for binary classification of sentences into **Albanian** or **English**.
- Training and testing on two text datasets: one for **Albanian** and one for **English**.
- Experimentation with **four loss functions** to observe their impact on model performance.

### Loss Functions Used:
1. **Cross-Entropy Loss**
2. **BCEWithLogits Loss**
3. **KLDivLoss**
4. **SoftMarginLoss**

## Files Included:
- **language_prediction.ipynb**: Jupyter Notebook for running the model on Google Colab.
- **Albanian.txt**: Text file containing sentences in Albanian for training and testing.
- **English.txt**: Text file containing sentences in English for training and testing.

## Dataset
Two datasets were used for training and testing:
- **Albanian.txt** - Contains 1000 sentences in Albanian.
- **English.txt** - Contains 1000 sentences in English.

## Results

The model was tested using different loss functions, achieving varying levels of accuracy for the task. The following results were obtained for each loss function:

- **Cross-Entropy Loss**: 100% accuracy in predicting both Albanian and English sentences.
- **BCEWithLogits Loss**: 90%+ accuracy, with one error in Albanian sentence prediction.
- **KLDivLoss**: 100% accuracy in predicting both languages.
- **SoftMarginLoss**: The performance was inconsistent, with varying accuracy across trials.

## Conclusion

This experiment demonstrates how the choice of **loss function** and **learning rate** affects the performance of the model. **Cross-Entropy** and **KLDivLoss** produced optimal results, while **BCEWithLogits** was a strong alternative. **SoftMarginLoss** underperformed and proved less suitable for this task.

## How to Run on Google Colab

1. Open the **language_prediction.ipynb** file in [Google Colab](https://colab.research.google.com/).
2. Upload the **Albanian.txt** and **English.txt** files to the Colab environment.
3. Run all the cells in the notebook to train and evaluate the model.

## Author

**Arnold Cobo**

## Feedback

Enjoy using this project! If you have any comments, constructive criticism, or bug reports, please feel free to [open an issue]() on this repository. Your feedback is greatly appreciated.
