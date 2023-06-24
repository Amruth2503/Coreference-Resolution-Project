# Coreference Resolution Project

## Overview
This project focuses on implementing coreference resolution, a natural language processing task aimed at identifying expressions that refer to the same entity within a text. Two different implementations were explored using different models and datasets, resulting in varying levels of accuracy.

## Implementations
### AllenNLP Implementation
The first implementation utilized the AllenNLP library and the VisDial dataset. The AllenNLP implementation achieved a modest accuracy of 60%. While this result indicates room for improvement, it serves as a starting point for further exploration.

### BERT Implementation
The second implementation leveraged the BERT (Bidirectional Encoder Representations from Transformers) model and the Hindi coreference annotated data. This implementation demonstrated a significant accuracy boost, achieving an accuracy of 88.06%. The improved performance can be attributed to factors such as a larger annotated dataset for Hindi, BERT's strong contextual understanding, and specific optimizations applied during training.

## Limitations and Future Enhancements
It is important to note that direct comparison between the two implementations is limited due to differences in evaluation metrics and datasets. However, both implementations highlight the potential of deep learning models for coreference resolution.

To further enhance the accuracy of coreference resolution on real-world datasets, several avenues for future refinement can be explored. These include:
- Increasing the size of the training data to capture a wider range of linguistic variations and contexts.
- Exploring optimized model architectures or variations of BERT to tailor them specifically for coreference resolution.
- Utilizing advanced language embeddings, such as contextual embeddings or domain-specific embeddings, to capture more nuanced semantic information.
- Employing ensemble methods that combine multiple models or techniques to leverage their individual strengths.

By pursuing these avenues, the accuracy of coreference resolution can be improved, leading to more effective natural language understanding and downstream applications in fields like information retrieval, question answering, and text summarization.
