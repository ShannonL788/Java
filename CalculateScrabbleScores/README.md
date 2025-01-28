# Calculate Scrabble Scores

Given an array of Strings, the goal is to sort the words based on their Scrabble scores. Scrabble scores are calculated by summing up the points for each letter in the word based on the standard Scrabble letter values.
The program sorts the words such that words with the lowest Scrabble score come first. If two words have the same score, they are sorted alphabetically.

## Features
  
- Takes in size of array, and an array of Strings
- Sorts words by their Scrabble score in ascending order, using bubbleSort.
- If two words have the same Scrabble score, they are sorted alphabetically.
- The program supports case-insensitive sorting.

### Example Input
  
4<br>
pear<br>
apple<br>
banana<br>
grape<br>

### Example Output

pear: 6 points<br>
banana: 8 points<br>
grape: 8 points<br>
apple: 9 points<br>
