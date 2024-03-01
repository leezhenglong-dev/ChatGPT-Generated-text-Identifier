# ChatGPT Generated-text Identifier
A tiny language model (fine-tuned from bert-base-chinese) designed to distinguish between ChatGPT generated text and human written text

## Requirements

- Python 3.11
- Cuda (if you wish to retrain the model)
- PyTorch 1.12
- transformer
- Pandas
- Numpy

## Train

Fully run `src.ipynb` 

## Test

Run `src.ipynb` from the `Evaluation` section. You can test your own test dataset by replace the value of `df_test`.

Besides, you can simply test single sentence/paragraph in `Exploratory Testing` section.

## Model

We have trained the model for 11 epoch. You can used the latest model stored in directory `saved_model`