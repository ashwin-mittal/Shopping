# Shopping 
AI to predict whether online shopping customers will complete a purchase.
## Background
When users are shopping online, not all will end up purchasing something. Most visitors to an online shopping website, in fact, likely don’t end up going through with a purchase during that web browsing session. It might be useful, though, for a shopping website to be able to predict whether a user intends to make a purchase or not: perhaps displaying different content to the user, like showing the user a discount offer if the website believes the user isn’t planning to complete the purchase. How could a website determine a user’s purchasing intent? That’s where machine learning will come in.
## Output
```bash
$ python shopping.py shopping.csv
Correct: 4094
Incorrect: 838
True Positive Rate: 41.22%
True Negative Rate: 90.53%
```
## Running
* Run ```pip3 install scikit-learn``` to install the ```scikit-learn``` package if it isn’t already installed then you should be able to run ```python3 shopping.py shopping.csv``` to print the results on  the terminal.
* The order of columns in ```shopping.csv``` will always be presented in the same order.
* It will compute what proportion of the time we correctly classify the user’s intent. Along with this, it will also measure two values: sensitivity (also known as the “true positive rate”) and specificity (also known as the “true negative rate”). Sensitivity refers to the proportion of positive examples that were correctly identified: in other words, the proportion of users who did go through with a purchase who were correctly identified. Specificity refers to the proportion of negative examples that were correctly identified: in this case, the proportion of users who did not go through with a purchase who were correctly identified.
