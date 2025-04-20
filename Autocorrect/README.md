# Autocorrect Project

## Project Overview
This project implements a simple autocorrect system using Python. It processes a dataset of words, calculates their probabilities, and suggests corrections for misspelled words based on common spelling errors (e.g., deleting, swapping, replacing, or inserting letters).

## Features
- **Text Processing**: Reads a CSV file containing words and processes them into a vocabulary set.
- **Word Probability Calculation**: Calculates the probability of each word based on its frequency in the dataset.
- **Autocorrection**: Suggests corrections for misspelled words by generating candidate words and ranking them by probability.

## Dataset
The dataset used in this project is `dict.csv`, which contains the following column:
- **word**: A list of words used to build the vocabulary and calculate word probabilities.

### Dataset Preview
The dataset contains a collection of words that are used to train the autocorrect system. Each word is processed to create a vocabulary set and calculate its probability.

## Requirements
The following Python libraries are required to run the project:
```bash
pip install pandas nltk
```
- **pandas**: For reading and processing the CSV file.
- **nltk**: For natural language processing tasks like lemmatization.

## Project Structure
1. **Importing Dependencies**: Required Python libraries are imported.
2. **Data Processing**:
   - Load the dataset from `dict.csv`.
   - Combine all words into a single string and convert to lowercase.
   - Extract individual words using a regular expression.
   - Create a vocabulary set of unique words.
3. **Word Probability Calculation**:
   - Count the frequency of each word.
   - Calculate the probability of each word based on its frequency.
4. **Autocorrection**:
   - Generate candidate corrections for a given word by:
     - Deleting a letter
     - Swapping adjacent letters
     - Replacing a letter
     - Inserting a letter
   - Rank the candidates by their probabilities and suggest the top corrections.

## Running the Project
1. Clone the repository or download the project files.
2. Ensure all required libraries are installed.
3. Place your `dict.csv` file in the project directory.
4. Run the `autocorrect.py` script:
   ```bash
   python autocorrect.py
   ```
5. Enter a word when prompted, and the system will display the top suggestions.

## Example
`Enter a word for autocorrection: helo`
`You entered: helo`

`Top suggestions:`
1. hello
2. help
3. hell

## Key Findings
- The system effectively identifies and corrects common spelling errors.
- The use of word probabilities ensures that the most likely corrections are suggested first.
- The project demonstrates how simple NLP techniques can be used to build practical tools like autocorrect.

## Conclusion
This project showcases the implementation of a basic autocorrect system using Python. It highlights the importance of text processing, probability calculation, and candidate generation in building such systems. The project can be extended with more advanced techniques like context-aware corrections or integration with larger datasets.

## Author
[Atharva Baikar](https://github.com/DarkGuardian641)