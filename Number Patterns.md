## Types of number patterns:

Title | Type | Description | Constants
--- | --- | --- | ---
1 | Linear | Arithmetic Sequence | First difference remains constant
2 | Quadratic | Quadratic Sequence | Second difference remains constant
3 | Exponential | Geometric Sequence | The change in the difference is constant

## 1. Arithmetic Sequence (Linear)

An arithmetic (linear) sequence is one where the difference between two neighbouring values is the same for all the values in the sequence.

For example:
$$\text{1 ; 2 ; 3 ; 4 ; 5 ; ...}$$
Every new number in the sequence is just the previous one plus 1

These sequences are often the easier of the sequences that you can come across. 

### Find the Difference

The difference between two neighbouring terms have a constant difference between them. This difference can be used to calculate the formula for the row.

Take this row as an example:

$$ \text{ T₁ ; T₂ ; T₃ ; ...}$$
T stands for term, and the numbers next to it are the positions in the sequence. You should be able to read this sequence as "Term 1, Term 2, Term 3, etc."

Since this is an arithmetic sequence, the difference between neighbouring terms will always be the same. So, to calculate that difference (d), you would do the following:

$$ \text{T₂} - \text{T₁} = d$$
$$ \text{T₃} - \text{T₂} = d$$
This is how you will be able to find out both the formula of the sequence and the next term in the sequence.

Here is the general formula for determining the difference
$$d=\text{T(n)} - \text{T(n-1)}$$
Here, "n" stands for number, or, in this case, position.

**Note:** The second difference (the difference between two neighbouring differences) will always be 0, in other words, d₂ - d₁ = 0

### General Formula

Now that you have the first difference, you can begin to use it to figure out the formula of the sequence! You will be using the general formula below to do this:

$$ \text{Tn} = a + d(n-1) $$

Symbols | Meaning
--- | ---
Tn | Term in the position "n"
n | Position of term
a | First term (T₁)
d | Difference

### Find the Next Term in the Sequence

Generally, the sequence will follow a pattern along the lines of something like this:

$$ \text{a + (n-1)d ; }\text{a + (n-1)d ; } \text{a + (n-1)d ; } ...$$$$ \text{↓}$$$$ \text{a + 0d ; }\text{a + 1d ; } \text{a + 2d ; } ...$$
You can use this to calculate the next term in the sequence, or to find values that weren't given to you. Keep this in mind for more complex problems later on. 

### Example Problems

##### 1) **Determine the nth term:**
1. Find the value of term 64
	Given:
$$ \text{11 ; 8 ; 5 ; ...} $$
2. Find the value of term 36
	Given:
$$ \text{2 ; 9 ; 16 ; 23 ; ...} $$
3. Find the value of term 8
	Given:
$$\frac{2}{3} ;\frac{11}{3}; \frac{20}{3}; \text{...} $$

##### 2) Solve the given problem if a sequence or set of terms are given**
1. Find the position of the value -22
	Given:
$$ \text{11 ; 8 ; 5 ; ...} $$
2. Find the position of the value 65
	Given:
$$ \text{2 ; 9 ; 16 ; 23 ; ...} $$
3. Find the position of the value 78
	Given:
$$ \text{-2 ; 2 ; 3 ; 2 ; 8 ; 2 ; ... ; 78} $$
4. Find the position of the value 72
	Given:
$$ \text{ T₁ = 2 ; T₇ = 16} $$
5. Find the value of term 15
	Given: 
$$ \text{T₄ = 14 };\text{ T₁₆ = 50} $$
6. Find the value of term 27
	Given:
$$ \text{T₅ = 23 };\text{ T₁₂ = 72} $$

##### 4) **Find the asked if the sequence contains variables**
1. Solve the given sequence
	Given:
$$ \text{x+2 ; 3x-1 ; 4x-3} $$
2. Solve the given sequence
	Given:
$$ \text{4-2x ; x-1 ; 3x-2} $$
2. Find the value of x
	Given:
$$ \text{x=2 ; x-3 ; x-7} $$
3. Solve the given sequence
	Given: 
$$ \text{ 4 ; x ; y ; -8 } $$

##### 5) Solve the problem with the given word problem
1. Solve the given word problem and sequence
	Given: Term 17 is nine times the value of term 1, and the value of term 9 is six less than three times the value of the 3rd term.

2. Solve the given word problem and sequence
	Given: Term 1 is equal to two and term 7 is equal to 16. Which term's value is equal to 72?

## 2. Quadratic Sequence

A quadratic sequence is a sequence of numbers in which each term can be represented by a quadratic expression of the form
$$ \text{Tn = } a n^2 + b n + c $$
where a, b, and c are constants and n is the position of the term in the sequence.

Quadratic sequences always include an n² term and can also be called quadratic algebraic sequences.

The terms in a quadratic sequence typically follow a pattern in which the second difference between terms is constant. 

The variable "a" can be calculated by using the formula

$$a=\frac{d₂}{2}$$

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

### Find the Next Term in the Sequence

Generally, the sequence will follow the pattern:

$$ \text{ x ; }\text{x+d ; } \text{x+(d+c) ; } \text{x+(d+2c) ; } ...$$
Where x is the first term, d is the difference between the first two terms, and c is the constant second difference.

You can use this to calculate the next term in the sequence

### 