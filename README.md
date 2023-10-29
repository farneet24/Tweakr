# Tweakr

Tweakr is a web-based application that suggests closely related English words based on the user's input. It is designed to find the minimal number of deletions or insertions needed to transform the input string into real English words. 

## Features

- **Minimal Edits**: Instantly provides English words that require a minimal number of deletions or insertions to match the user's input string.
- **Dynamic UI**: Features a beautiful animative background to enrich user experience.
- **Real-Time Results**: Automatically updates the suggestions as the user types in each character.

## Under the Hood: Data Structures and Algorithms

- **Array-based Dictionary**: Utilized for storing the list of possible words.
- **Edit Distance Algorithm**: Employs dynamic programming to calculate the minimal number of edits required to transform the input string.

### Core Functions

#### `findSimilarWords`

This function takes a `searchTerm` and a `dictionary` and returns an array of words that are within a maximum edit distance of 2 from the `searchTerm`.

- **Algorithm Complexity**: O(n * m) where n is the number of words in the dictionary and m is the average length of the words.

#### `calculateEditDistance`

This function calculates the edit distance between two strings using dynamic programming.

- **Algorithm Complexity**: O(m * n) where m and n are the lengths of the two input strings.


  
## Live Demo

The website is live. Just visit [Tweakr](https://ada-assignment-farneet.vercel.app/) to get started. 

## Usage

1. Navigate to the Tweakr website.
2. Start typing into the search box.
3. Watch as a list of closely related words appears below the search box.

## Technologies Used

- HTML5, CSS3 for frontend
- JavaScript for dynamic behavior

## Contributing
Individuals interested in contributing to the project are encouraged to connect through [LinkedIn](https://www.linkedin.com/in/farneet-singh-6b155b208/).
