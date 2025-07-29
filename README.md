# Cat vs Dog Image Classifier

This notebook implements a binary image classifier to distinguish between cats and dogs using TensorFlow and Keras. The model uses a simple but effective CNN architecture optimized for this specific dataset.

## Motivation

- Learn to create deep learning models and train them to accurately recognize specific photos.

## Project Structure

```
cat_dog/
├── cat_dog_classifier_v2.ipynb    # Main notebook with complete implementation
├── requirements.txt               # Python dependencies
├── README.md                      # This file
└── best_cat_dog_model.h5          # Saved model (created after training)
```

## Performance

- **Training Accuracy**: ~95%
- **Validation Accuracy**: ~90%
- **Dataset**: 800 training images, 200 validation images
- **Training Time**: ~5-10 minutes on CPU, ~2-3 minutes on GPU

## Results

The notebook displays:
- Training and validation accuracy/loss curves
- 12 example predictions with confidence scores
- Model evaluation metrics
- Correctly colored predictions (green=correct, red=incorrect)

## Acknowledgments

- Dataset: [Kaggle Dog vs Cat](https://www.kaggle.com/anthonytherrien/dog-vs-cat)
- Built with TensorFlow/Keras
- Inspired by CNN architectures for image classification