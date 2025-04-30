# Named Entity Recognition


## AIM
To develop an LSTM-based model for recognizing the named entities in the text.

## Problem Statement and Dataset
Build a Named Entity Recognition (NER) model that can automatically identify and classify entities like names of people, locations, organizations, and other important terms from text. The goal is to tag each word in a sentence with its corresponding entity label.


### Dataset Name: ner_dataset.csv

Size: Contains thousands of words grouped into sentences with entity annotations.

#### Columns:

Sentence # – Sentence ID

Word – Individual word/token in the sentence

POS – Part-of-speech tag

Tag – Named entity tag (e.g., O, B-PER, I-LOC, etc.)


## DESIGN STEPS:
### STEP 1
Import necessary libraries and set up the device (CPU or GPU).
### STEP 2
Load the NER dataset and fill missing values.
### STEP 3
Create word and tag dictionaries for encoding.
### STEP 4
Group words into sentences and encode them into numbers.
### STEP 5
Build a BiLSTM model for sequence tagging.
### STEP 6
Train the model using the training data.
### STEP 7
Evaluate the model performance on test data.

## PROGRAM
### Name: K SANTHAN KUMAR
### Register Number: 212223240065

```python
class BiLSTMTagger(nn.Module):
    # Include your code here







    def forward(self, input_ids):
        # Include your code here
        


model = 
loss_fn = 
optimizer = 


# Training and Evaluation Functions
def train_model(model, train_loader, test_loader, loss_fn, optimizer, epochs=3):
    # Include the training and evaluation functions






    return train_losses, val_losses

```
## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

Include your plot here

### Sample Text Prediction
Include your sample text prediction here.

## RESULT
