Objective: Using computer vision to annotate images based on the context, with the help of various datasets.

Key Tasks:
- Understanding computer vision technologies.
- Using VGG16 model( CNN model) to extract photo features and convert into necessary dimensions.
- Performing data cleaning on the training and test dataset captions using Natural Language Processing.
- Using LSTM (Long Short Term Memory) model to combine text and photo feature vector to generate captions.
- Evaluating the generated captions using BLUE score.

Outcome:
- The model generated annotations for images based on the context of the images and learning uses memory to generate captions based on previous generated words. However, a larger feature extractor model could be used rather than the basic VGG16 model for better results.
