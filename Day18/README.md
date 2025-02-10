# Day 18: Transfer Learning

## What I Learned
- **Transfer Learning**: Using pretrained models to improve performance on new tasks.
- **Pretrained Models**: Understanding architectures like VGG, ResNet, and Inception.
- **Fine-tuning**: Adapting pretrained models for specific tasks by modifying layers.
- **Image Classification**: Applying ResNet for binary classification (dog vs. cat).

## Tasks Completed
1. **Loaded and Preprocessed Dataset**:
   - Used a dataset of dog and cat images.
   - Applied data augmentation and normalization.
2. **Fine-tuned ResNet Model**:
   - Loaded pretrained ResNet with ImageNet weights.
   - Modified the final layers for binary classification.
   - Used Adam optimizer and binary crossentropy loss.
3. **Trained and Evaluated Model**:
   - Fine-tuned on the dataset and monitored validation accuracy.
   - Plotted training curves and evaluated performance.

## Resources Used
- [Transfer Learning with ResNet](https://keras.io/api/applications/resnet/)
- [Dog vs. Cat Dataset](https://www.kaggle.com/c/dogs-vs-cats)
- [Fine-tuning in Keras](https://www.tensorflow.org/tutorials/images/transfer_learning)
