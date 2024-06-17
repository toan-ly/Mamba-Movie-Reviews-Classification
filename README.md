# Mamba Movie Reviews Classification with IMDB Dataset

This repository demonstrates how to perform text classification using the Mamba model on the IMDB dataset. The IMDB dataset contains movie reviews labeled as positive or negative, and this project aims to build a custom Mamba model to classify these reviews.

## Model Architechture
The model architechture is based on the Mamba model. The custom Mamba model includes:
1. `MambaConfig`: Configuration class for the Mamba model.
2. `MambaClassificationHead`: A classification head tailored for Mamba models.
3. `MambaLMHeadModel`: The base Mamba model.
4. `MambaTextClassification`: Custom model for text classification.
