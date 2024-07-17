## TourGPT: A Fine-Tuned Large Language Model for Tourism and Hospitality

### Overview
This project demonstrates the fine-tuning of a GPT-2 language model for applications in the tourism and hospitality industry. The notebook covers the necessary steps to:

1. Set up the environment with essential Python libraries and verify GPU availability.
2. Mount Google Drive to access datasets and save trained models.
3. Load and preprocess a dataset containing 500 samples related to tourism and hospitality.
4. Tokenize the text data using the GPT-2 tokenizer and create a custom PyTorch dataset class (GPT2Dataset) for efficient data handling.
5. Set up data loaders for training and validation.
6. Fine-tune the GPT-2 model (gpt2-medium) on the tourism dataset, including model configuration, training setup, optimizer initialization (AdamW), and learning rate scheduling with warm-up.
7. Train the model over multiple epochs, evaluate performance on a validation set, and log training statistics such as loss and time.
8. Save the fine-tuned model to Google Drive.
9. Showcase text generation using the trained model and set up an interactive chatbot interface using Gradio for tourism-related queries.

### Key Features
- Comprehensive approach to understanding and implementing GPT-2 fine-tuning for specific applications.
- Leverages pre-trained models and state-of-the-art NLP techniques to create a domain-specific language model.
- Provides a structured and efficient way to handle text data using PyTorch datasets and data loaders.
- Demonstrates fine-tuning process, including model configuration, training setup, and performance evaluation.
- Enables generation of tourism-related text and sets up an interactive chatbot interface.

### Usage
1. Install the necessary libraries, including the Transformer library by Hugging Face:

```python
!pip install transformers
```

2. Mount Google Drive and copy the dataset file to the current Colab working directory.
3. Run the notebook to fine-tune the GPT-2 model and generate tourism-related text.
4. Explore the interactive chatbot interface to test the fine-tuned model's capabilities.

