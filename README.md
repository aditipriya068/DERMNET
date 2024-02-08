# DERMNET
Developed an skin disease detector using DERMNET and HAM10000 dataset, trained many models with various loss functions and hyperparameters.

Methodology:

Data Preprocessing:

Images from both datasets were preprocessed to ensure uniformity and enhance model performance. Preprocessing steps include resizing, normalization, and augmentation techniques such as rotation, flipping, and zooming.

Model Training:
Multiple deep learning models, including convolutional neural networks (CNNs), were trained on the preprocessed dataset.
Various loss functions such as categorical cross-entropy, binary cross-entropy, and focal loss were employed to optimize model training.
Hyperparameters including learning rate, batch size, and number of epochs were tuned to enhance model convergence and generalization.

Evaluation Metrics:
The performance of each model was evaluated using standard evaluation metrics such as accuracy, precision, recall, and F1-score.
Confusion matrices were generated to analyze the model's classification performance across different skin diseases.

Model Selection:
The model demonstrating the highest performance metrics on the validation set was selected as the final skin disease detector.

Deployment:
The selected model was deployed using a user-friendly interface, allowing users to upload skin lesion images and receive predictions regarding potential skin diseases.
