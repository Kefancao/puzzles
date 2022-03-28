# Puzzles
## Introduction
Hey! Thanks for visiting my puzzles page! This is where I'll be publishing some of the puzzles I find interesting! Hope you'll enjoy them as well!

## Algorithms
### Banana Bundles
Suppose you're a grocery clerk filling banana 🍌 orders. The customer may order any number of banana they desire. Now, bananas come in bundles ranging from a single banana upwards to hundreds of bananas. Your job as a grocery clerk is to fill these banana orders to the best of your ability without breaking any bananas. If there are multiple solutions that allow you to fill these bananas without breaking a bundle, your job is to minimize the number of bundles you take! If there are multiple combination of bundles that minimize the number of bundles, any one of them will work!

Example: 
  Desired -> 10
  Bundles -> [4, 3, 5, 5, 6, 3, 2]
  Expected -> (4, 6) or (5, 5) since 4 + 6 = 10 and 5 + 5 = 10, and 2 is the minimum number of bundles to take since there are no single bundles of 10. 
  
Function: 
  bestBananaBundle :: Int -> List -> List
