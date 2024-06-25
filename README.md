# Custom Named Entity Recognition (NER) Model

This project demonstrates how to create and train a custom Named Entity Recognition (NER) model using spaCy.

## Prerequisites


- spaCy library

## Installation

1. Install spaCy:
   `pip install spacy`

## Usage

- Prepare your training data in the format shown in the notebook.

- Run the Jupyter notebook or Python script to train the model:

### The script will:
- Create a blank English language model
- Add NER pipeline to the model
- Train the model on the provided data
- Test the model on sample sentences

## Code Structure

- Import required libraries (spaCy, random)
- Define training data
- Create a blank model and add NER pipeline
- Extract and add entity labels
- Set up training configuration
- Train the model using batches
- Test the model on sample sentences

## Customization

You can customize the model by:
- Modifying the `train_data` list with your own examples
- Adjusting the number of training iterations
- Fine-tuning hyperparameters like dropout rate

## Notes

- The current implementation uses a small dataset for demonstration purposes. For production use, a larger and more diverse dataset is recommended.
- The model's performance may vary depending on the quality and quantity of training data.
