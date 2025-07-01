# PRODIGY_GA_03 — Markov Chain Text Generator

This project implements a simple Markov Chain-based text generation algorithm in Python. It generates text by predicting the next word in a sequence using a statistical model based on previous word(s), also known as n-grams.

---

## Objective

Implement a simple text generation algorithm using Markov chains. This task involves creating a statistical model that predicts the probability of a character or word based on the previous one(s).

---

## Features

- Word-level Markov Chain text generator
- Adjustable `n` for n-gram size (unigram, bigram, trigram, etc.)
- Configurable output length
- Optional seed for reproducibility
- Easy to modify and experiment with
- No external dependencies (standard Python libraries only)

---

## How It Works

1. **Text Preprocessing**  
   The input text is converted to lowercase, unnecessary punctuation is removed, and the text is split into individual words.

2. **Build Markov Chain**  
   A dictionary is constructed where each key is an n-gram (e.g., 2 words for a bigram), and the values are possible next words based on the input data.

3. **Generate Text**  
   A starting n-gram is randomly selected, and the algorithm generates new words by following the transitions defined in the Markov chain, continuing until the desired length is reached.

---

## Steps to Use

1. Clone or download this repository to your local system.

2. Open the file `markov_generator.py` in any code editor.

3. Inside the script, locate the following variables and update them as needed:
   - `sample_text`: Replace this with your own input text.
   - `n`: Set the n-gram size (e.g., 1 for unigram, 2 for bigram).
   - `length`: Set the number of words you want to generate.
   - `seed`: Optionally set a number for reproducible results.

4. Save the file and run the script using a Python interpreter (Python 3+).

5. The generated text will be printed in the terminal or console.

---

## Files Included

- `markov_generator.py` – Main Python script containing the Markov Chain algorithm
- `output.txt` – A sample generated text output (optional)
- `README.md` – Project documentation



