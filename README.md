# Task-03: Text Generation with Markov Chains

## About
This project is a simple text generator built using **Markov Chains**.
It learns from a piece of training text and then generates new text by
predicting the next word based on the current word.

This was completed as part of my internship task at ProDigy InfoTech.

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

## How to Run
1. Make sure you have Python installed (no extra libraries needed).
2. Run the script:
   ```
   python markov_chain_text_generator.py
   ```
3. Follow the prompts:
   - Choose whether to use your own text or the sample text
   - Enter how many words you want generated
   - Optionally enter a starting word

## Example Output
```
Enter a starting word (or press Enter for random): the

--- Generated Text ---
the sun rose slowly over the calm blue ocean.
```

## Files
- `markov_chain_text_generator.py` — main Python script

## Possible Improvements
- Use a character-level Markov chain instead of word-level
- Use bigrams/trigrams (last 2-3 words) instead of just 1 word for better accuracy
- Train on a larger dataset for more natural-sounding output

## Author
Dev — B.Tech Student, ProDigy InfoTech Internship
