![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) 29: Whiteboard Challenge
===

## Requirements
Write a method to sort an array of strings so that all the anagrams are next to each other

Note - we can use a hash table to map the sorted version of a word to a list of its anagrams

example:
```javascript
sortAnagrams('acre race care act cat tac') =>

{
  acre : {acre, race, care},
  act: {act, cat, tac},
}
```

Once all the words have been grouped into lists by anagram we can put them back into the array.

Write at least four tests for this function
* your tests should cover basic (*expected*) functionality
* your tests should consider edge cases for your function (ex: will your function still operate on an array of floating point integers?)

## Submission Instructions

1. With your assigned partner, pseudocode your solution on the whiteboard. Take a picture of your proposed solution for your repo.
1. Make a new branch and folder in your whiteboard challenge repository on GitHub. The name of the folder should be the same as the name of the challenge.
1. This folder should contain:
	- A file named `solution.js` which contains the JavaScript solution
	- A picture of your pseudocoded solution from the whiteboarding exercise
	- A `README.md` which includes the problem domain
1. Complete the whiteboard challenge in your text editor, and verify that it's functional.
1. Make a pull request from your working branch to your master branch.
1. Submit a link to your PR, or a link to your repo/submission, in Canvas.
