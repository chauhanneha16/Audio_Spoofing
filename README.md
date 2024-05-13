# Audio_Spoofing
Dataset https://www.kaggle.com/datasets/awsaf49/asvpoof-2019-dataset.

Spoof detection involves several key steps:

Feature Extraction: Extracting specific features related to vocal tract arrangement from audio signals. In this process, features such as the positions and movements of articulators are identified. Common techniques include using Mel spectrogram features along with centroid analysis.

Model Training: Training machine learning models, including classifiers or neural networks, on a dataset containing both real and deepfake audio samples. These models learn to distinguish between features associated with genuine speech production and those indicative of deepfake generation. Various deep learning approaches like CNN, Transformer, and combinations such as CNN+Transformer are employed in this work.

Detection: During the detection phase, the trained models analyze the features extracted from new audio samples to determine whether they are more likely to be genuine or deepfake. If the features resemble those associated with deepfake generation, the sample is flagged as a potential deepfake. The model is evaluated on unseen audio data to ensure its capability to identify whether the input audio is genuine or spoofed.
