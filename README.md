# jsChallenge

## Column Check
  - Take the indices of the `column` (left most arrays)
    - push the first index of each of those arrays into an array if the number doesnt already exist within the array we have pushed too.
    - check that the length of that array is 9 if so return true
       - repeat for indecies 1, 2 of inner arrays,
  - Repeat the above process for middle column indices
  - Repeat the abobve process for right column indices


## Row Check
  - Push the contents of ```sudoku[0,1,2]``` into an array and on every push run a check to see if the integer already exists in the destination array.  If so dont push, and once you have gone through all 9 iterration check the length of the pushed array if 9 then return true. 
    - repeat for the ```sudoku[3, 4, 5], sudoku[6, 7, 8]``` etc.
