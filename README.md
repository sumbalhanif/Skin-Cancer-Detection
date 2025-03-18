# Skin-Cancer-Detection
Dataset Preparation → Loaded image paths, assigned labels (Benign = 0, Malignant = 1).
 Train-Test Split → 80% training, 20% validation (stratified split).
 Preprocessing → Resized images (224x224), normalized (0-1), converted to TensorFlow dataset.
 Model Selection → I have Used transfer learning( EfficientNetB7 pretrained), added custom classification layers.
 Training → Used Adam optimizer , binary cross-entropy loss, trained for a few epochs.
 Evaluation → Predicted on the validation set, checked the accuracy, confusion matrix, and classification report.
