# Puzzles

## Introduction

Hey! Thanks for visiting my puzzles page! This is where I'll be publishing some of the puzzles I find interesting! Hope you'll enjoy them as well!

## Algorithms

### Banana Bundles

Suppose you're a grocery clerk filling banana 🍌 orders. The customer may order any number of banana they desire. Now, bananas come in bundles ranging from a single banana upwards to hundreds of bananas. Your job as a grocery clerk is to fill these banana orders to the best of your ability without breaking any bananas. If there are multiple solutions that allow you to fill these bananas without breaking a bundle, your job is to minimize the number of bundles you take! If there are multiple combination of bundles that minimize the number of bundles, any one of them will work!

**Example:** 
- Desired -> 10
- Bundles -> [4, 3, 5, 5, 6, 3, 2]
- Expected -> (4, 6) or (5, 5) since 4 + 6 = 10 and 5 + 5 = 10, and 2 is the minimum number of bundles to take since there are no single bundles of 10. 
  
**Function:**

```hs 
minBananaBundle :: Int -> List -> List
```

## Mathematics

### Pair to Destination Pair with 2 Operations
Let a, b, c, d be integers and (a, b) and (c, d) be two pairs of integers. We then define two operations, 
- (a, b) -> (a + b, b)
- (a, b) -> (a, a + b)

Given two pairs of such integers, determine if it's possible for (a, b) to become (c, d) via these two operations.

**Example:**
- (a, b) = (2, 4)
- (c, d) = (6, 10)
- Expected: Yes, by performing (2, 4) -> (2 + 4, 4) = (6, 4) -> (6, 4 + 6) = (6, 10)

**Function**
```hs
isReachable :: (Int, Int) (Int, Int) -> Bool
```

## Probability
### Painted Die
Suppose you have a 3x3x3 cube, made of 27 tiny cubes. And suppose you painted the exteriors of the cube. Now, you break up the cube into it's 27 parts and take one die out and roll it. It turns out all five visible sides of the die are unpainted, what is the probability that the hiddne face is also unpainted?

### First Primes
What is the probability that four randomly chosen primes from the first 20 primes is odd?
