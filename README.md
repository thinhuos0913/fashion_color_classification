# Purpose
In the field of fashion we need to distinguish at the same time the type of fashion product along with the characteristics of the product such as color (blue, red, purple, yellow, ...) , gender (male, female), age (old people, youth, children), season (winter, summer, ....), so in this project we'll build a model that classifies product fashion but also predicts product color at the same time.

We'll use Multitask learning algorithm that trains two tasks simultaneously: fashion product classification and product color, the data includes 3 fashion labels: {dress, jean, shirt} and 3 color labels: {black, blue, red}.

The multitask learning model will simultaneously learn 6 binary classification tasks on an input image, which are problems:

- Is the photo a dress or not?

- Is the picture jeans or not?

- Is the photo skirt or not?

- Is the picture blue or not?

- Is the image black or not?

- Is the image red or not?
