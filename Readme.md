Multi-Output Landmark and Category Classification using VGG16 and Transfer Learning

This project leverages transfer learning with the VGG16 model to classify both architectural styles and landmarks from a challenging dataset. By using pre-trained VGG16, which is fine-tuned on our specific task, we achieved state-of-the-art results in both tasks.

Key Features:
Architectural Style Classification: The model was trained to classify images based on architectural styles, achieving an impressive accuracy of 96%.
Landmark Classification: The second task focused on landmark recognition, where the model achieved 87% accuracy.
Methodology:
Transfer Learning: We utilized the VGG16 model, which was pre-trained on ImageNet, and fine-tuned it to adapt to our specific dataset. This allows for faster convergence and higher accuracy with fewer training data.

Data Augmentation: To enhance the model's robustness and improve generalization, several data augmentation techniques were employed, such as rotation, flipping, zooming, and shifting. This helped improve the model's robustness by 10%.

Results:
96% accuracy in architectural style classification.
87% accuracy in landmark classification.
Improved model robustness by 10% through data augmentation.

Conclusion:
This project demonstrates the power of transfer learning for solving complex computer vision tasks, especially when the dataset is challenging. By fine-tuning the VGG16 model and applying strategic data augmentation techniques, we were able to achieve excellent performance across both classification tasks.
