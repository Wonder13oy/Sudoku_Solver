# Backtracking Psuedocode

1. Pick empty square
2. Try all numbers
3. Find number that fits
4. Continue to next square.
5. Repeat
6. Backtrack - if number does not fit
  1. Remove the number from the square
  2. Go to previous square.
  3. Try numbers above that current number.
  4. Find the number that fits.
  5. If number does not fit, repeat Backtrack.
