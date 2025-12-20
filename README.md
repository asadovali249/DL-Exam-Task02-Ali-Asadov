# Task 2: Fashion-MNIST Classification

**Student:** Ali Asadov 
**ID:** 2 
**Seed:** 20240102 

## Presentation
[View Presentation Slides](https://docs.google.com/presentation/d/1S1WwYaZn2fi9xcm7OEqnYJtkX_Kwy7es/edit?usp=sharing&ouid=107458438931588601641&rtpof=true&sd=true)

## Dataset
- **Name:** Fashion-MNIST
- **Classes:** 10 (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)
- **Training samples:** 60,000
- **Test samples:** 10,000

## Model Architecture
- **Type:** CNN 
- **Convolutional layers:** 2 
- **Fully connected layers:** 2 
- **Total parameters:** 405,000

## Training Comparison

### Version 1
- **Learning rate:** 0.001
- **Batch size:** 64
- **Optimizer:** Adam
- **Test accuracy:** 92.02% 

### Version 2
- **Learning rate:** 0.0001
- **Batch size:** 64
- **Optimizer:** Adam
- **Test accuracy:** 89.90% 

### Best Result
- **Best version:** Version 1
- **Final test accuracy:** 92.02% 
- **Target accuracy:** 88.00%
- **Status:** ✓ Achieved

## Analysis
- **Best performing class:** Trouser 
- **Worst performing class:** Shirt 
- **Key observations:** 
  1. learning rate 0.001 allowed the model to improve much faster than 0.0001 within the 10-epoch limit.
  2. The model easily surpassed the target accuracy of 88% using the specified CNN architecture.

## Files
- `notebook.ipynb`: Complete implementation with both training runs
- `results/training_comparison.png`: Comparison of Version 1 vs Version 2
- `results/confusion_matrix.png`: Confusion matrix from best model
- `results/predictions.png`: Sample predictions

