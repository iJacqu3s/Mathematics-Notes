## Types of number patterns:

Title | Type | Description | Constants
--- | --- | --- | ---
1 | Linear | Arithmetic Sequence | First difference remains constant
2 | Quadratic | Quadratic Sequence | Second difference remains constant
3 | Exponential | Geometric Sequence | The change in the difference is constant
4 | "Special" | "Special" Sequence | Dependant on the type of sequence


---
## 1. Arithmetic Sequence (Linear)

An arithmetic (linear) sequence is one where the difference between two neighbouring values is the same for all the values in the sequence.

For example:

$$1 ; 2 ; 3 ; 4 ; 5 ; ...$$

Every new number in the sequence is just the previous one plus 1

These sequences are often the easier of the sequences that you can come across. 

---
### Find the Difference

The difference between two neighbouring terms have a constant difference between them. This difference can be used to calculate the formula for the row.

Take this row as an example:

$$  T₁ ; T₂ ; T₃ ; ...$$

T stands for term, and the numbers next to it are the positions in the sequence. You should be able to read this sequence as "Term 1, Term 2, Term 3, etc."

Since this is an arithmetic sequence, the difference between neighbouring terms will always be the same. So, to calculate that difference (d), you would do the following:

$$ \text{T₂} - \text{T₁} = d$$

$$ \text{T₃} - \text{T₂} = d$$

This is how you will be able to find out both the formula of the sequence and the next term in the sequence.

Here is the general formula for determining the difference

$$d=\text{T(n)} - \text{T(n-1)}$$

Here, "n" stands for number, or, in this case, position.

**Note:** The second difference (the difference between two neighbouring differences) will always be 0, in other words, d₂ - d₁ = 0

---
### General Formula

Now that you have the first difference, you can begin to use it to figure out the formula of the sequence! You will be using the general formula below to do this:

$$ \text{Tn} = a + d(n-1) $$

where "Tn" is the term in the position "n", "n" is the position of a term in the sequence, "a" is the first term (T₁), and "d" is the difference between two neighbouring terms

---
### Find the Next Term in the Sequence

Generally, the sequence will follow a pattern along the lines of something like this:

$$ a + (n-1)d ; a + (n-1)d ;  a + (n-1)d ;  ...$$

$$↓$$

$$ a + 0d ; a + 1d ;  a + 2d ;  ...$$

You can use this to calculate the next term in the sequence, or to find values that weren't given to you. Keep this in mind for more complex problems later on. 

---
## 2. Quadratic Sequence

A quadratic sequence is a sequence of numbers in which each term can be represented by a quadratic expression of the form

$$ \text{Tn = } a n^2 + b n + c $$

where "a", "b", and "c" are constants and "n" is the position of the term in the sequence.

Quadratic sequences always include an n² term and can also be called quadratic algebraic sequences.

The terms in a quadratic sequence typically follow a pattern in which the second difference between terms is constant. 

The variable "a" can be calculated by using the formula

$$a=\frac{d₂}{2}$$

where "d₂" is the constant second difference.

---
### Find the Difference

For quadratic sequences, the difference between each pair of adjacent terms is constant, and the difference between each pair of adjacent terms in the sequence of differences is also constant.

![What are quadratic sequences?](https://thirdspacelearning.com/wp-content/uploads/2021/07/Quadratic-Sequences-What-is-Card.png)

For example, the quadratic sequence

$$3, 7, 11, 15, 19, 23, 27, 31, 35, 39, 43, 47, ...$$

has a second difference of 4, and each pair of adjacent terms has a difference of 4 as well.

To find the second difference of a quadratic sequence, you can follow these steps:

1.  Write down the first few terms of the sequence. For example, if the sequence is 3, 7, 11, 15, 19, 23, 27, 31, 35, 39, 43, 47..., you would write down the first six terms like this: 3, 7, 11, 15, 19, 23.

2.  Find the difference between each pair of adjacent terms. In this example, the differences would be 4, 4, 4, 4, 4.

3.  Find the difference between each pair of adjacent terms in the sequence of differences you found in the previous step. In this example, the second differences would all be 0.

4.  The second difference of a quadratic sequence is the constant number that you find in the third step. In this example, the second difference is 0.

Note that the second difference of a quadratic sequence is not always 0, as in this example. In general, the second difference can be any constant number.

---
### Find the Next Term in the Sequence

Generally, the sequence will follow the pattern:

$$ \text{ x ; }\text{x+d ; } \text{x+(d+c) ; } \text{x+(d+2c) ; } ...$$

Where x is the first term, d is the difference between the first two terms, and c is the constant second difference.

You can use this to calculate the next term in the sequence

---

## 3. Geometric Sequence (Exponential)

An exponential sequence is a sequence of numbers in which each term is obtained by multiplying the previous term by a constant value called the common ratio.

For example, the sequence

$$2, 4, 8, 16, 32, 64, 128, ... $$

is an exponential sequence because each term is obtained by multiplying the previous term by 2 (the common ratio). 


![This image has an empty alt attribute; its file name is Sequences-Hub-3.svg|300](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-3.svg)

![Sequences Hub 4|300](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-4.svg)

The general formula for an exponential sequence is 

$$Tn = a  r^{(n-1)}$$

where "a" is the first term in the sequence, "r" is the common ratio, and "n" is the position of the term in the sequence.

---
## "Special" Sequences

### Square numbers

A square number is the result when a number is multiplied by itself.

![Sequences Hub 6](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-6.svg)

This sequence has a general term of 

$$ Tn=n^2 $$

---
### Cube Sequences

Similarly to square sequences, a square number is the result of multiplying a number by itself 3 times.

![Sequences Hub 7](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-7.svg)

This sequence has a general term of 

$$ Tn=n^3 $$

A sequence like this would therefore looks something like this:

$$3 ; 27; 19683 ; ...$$

---
### Triangular Sequences

A triangular sequence can form a triangular dot pattern when drawn.

![Sequences Hub 8](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-8.svg)

This sort of pattern can be made by adding one more to the difference 

![This image has an empty alt attribute; its file name is Sequences-Hub-9.svg|300](https://thirdspacelearning.com/wp-content/uploads/2021/05/Sequences-Hub-9.svg)

---

### Fibonacci Sequence

This sequence can be made by adding the previous two terms in a sequence together to find the next term in said sequence.

For example:

$$0, 1, 1, 2, 3, 5, 8, 13, 21, …$$

Term 3 is found by adding term 1 and term 2 together, the result of which, is 1. 