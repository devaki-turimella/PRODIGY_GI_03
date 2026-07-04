# Task-03: Text Generation with Markov Chains

## About
This project is a simple text generator built using **Markov Chains**.
It learns from a piece of training text and then generates new text by
predicting the next word based on the current word.

## What is a Markov Chain?
A Markov Chain is a simple statistical model where the next output
depends only on the current state — not the entire history before it.

In this project:
- The "state" is the current word.
- The model looks at what words followed that word in the training text.
- It randomly picks one of those "next words" to continue the sentence.

## How the Program Works
1. Takes some training text (either a built-in sample or text entered by the user).
2. Builds a dictionary where each word is linked to a list of words that came after it.
3. Starts with a word (chosen by the user, or random) and keeps picking
   the next word randomly from the dictionary to generate new text.


## Example Output
```
Enter a starting word (or press Enter for random): the

--- Generated Text ---
the sun rose slowly over the calm blue ocean.
```


## Author - by Devaki
