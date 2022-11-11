# Airbnb-price-category-prediction

Input (two modalities):

- summary (text data)

- image (image data)

Output (two predictions): 

- To predict the listing price based on the listing characteristics Price, Type.

Data mining function:

- Classification and prediction because we need to predict the listing price based on the listing characteristics.

The challenges:

- Cleaning data and removing all tags, special characters, ASCII, and white spaces from the text, remove all nan values and convert all images into the same size.

Impact:

We will know the range of the price.

Steps:

1- Reading data and display data.

2- Cleaning data and preprocessing data.
   - Remove all tags, special characters, ASCII, and white spaces from the text.
   - Convert all images into the same size.
   - Remove all nan values.

4- Trials

Protocol:

- I intend to use hold out method.

Search space:

- I used random's range in the code according to try and error.

Determine good/bad hyper-parameters:

- According to the accuracy graph if there is overfitting or underfitting and then I decided to change hyperparameters of add layers.
