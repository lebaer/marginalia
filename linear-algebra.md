# Linear Algebra
## What is Linear Algebra?
### Overview
* “translating something residing in an m-dimensional space into a corresponding shape in an n-dimensional space” … like an object to a picture of an object, or vice versa; m and n can be equal here
* “will learn to work with matrices and vectors to understand the central concepts of ‘linear transformations,’ ‘eigenvalues,’ and ‘eigenvectors.’”

## Fundamentals
### Number Systems
* Complex numbers: a + b * I, where a and b are real numbers and I is “the imaginary unit” (sqrt(-1))
* real numbers: integers, rational numbers, irrational numbers
* imaginary numbers: complex numbers without a real component, like 0 + b*I
* so, take x^2 + 5 = 0. This also equals x^2 - (-5), which breaks out into (x + sqrt(5)I)(x - sqrt(5)I) - but wait, why is sqrt(-5) = sqrt(5) * I here? Is I constant? (Is there such a thing as a constant for an imaginary number?)
* I **is** a constant imaginary number 😂. Consider it a “placeholder” and that it’s accepted we can say sqrt(-x) = sqrt(x) * I.

### Implication and Equivalence
* Propositions are “declarative sentences that are either true or false.” Must be true or false, cannot be both or ambiguous. (“Reiji Yurino is handsome.”)
* Implication: “If this dish is a schnitzel, then it contains pork” is always true. But its converse: “If this dish contains pork, then it is a schnitzel” is not always true!
* “If P then Q” is true, “If Q then P” not necessarily true: “P entails Q” and “Q could entail P”
* “If P then Q” is true, can write as P => Q; this is the “implication” symbol.
* Equivalence: If both “If P then Q” and “If Q then P” are true, P => Q, Q => P, P and Q are “equivalent” and can write as P <=> Q. This is the “equivalence” symbol. P: Reiji is shorter than Tetsuo. Q: Tetsuo is taller than Reiji.

### Set Theory
* a “set” is a collection of things; these things are called its “elements” or “objects”
* example: the set of all even numbers from 1-10 contains these five elements: 2, 4, 6, 8, 10
* write it as {2, 4, 6, 8, 10}
* also write it as {2n|n = 1, 2, 3, 4, 5 }
* So give the set a name: X = {2, 4, 6, 8, 10}
* element x belongs to set X; no idea how to type it, will use an E. x E X.
* Subsets: all elements of set X also belong to set Y, X is a subset. X C Y.

### Functions
* Images: if x1 is an element of set X, y1 is “x1’s image under f in Y” - the element in Y that corresponds to x1 when put through function f. “x1’s image under f in Y” is also written as f(x1).
* Domain and Range: Range is a (sub)set of Y; it’s the image of the set X under function f. Can also sometimes be called the image of f, but usually called the range of f. X is the domain of f. Y is the co-domain; it includes any values in Y that aren’t included in the range; a function’s range is a subset of its co-domain. CY vs =Y.
* Onto and 1:1 Functions: a function is “onto” if its image (range?) is equal to its co-domain; all elements in the co-domain of an onto function are being mapped “onto.” If no element in the co-domain can be mapped onto more than once, it’s 1:1. A function can be both onto and 1:1; in this case, each element has one and only one partner.
* Onto but not 1:1: X has 4 elements, Y has 3; one element in Y has two partners in X.
* 1:1 but not onto: X has 4 elements, Y has 5; even if each x maps onto a different y, there’s still a y left over that is not being mapped onto.
* Inverse Functions: f is an inverse of function g if: 1. g(f(xi)) = xi; 2. f(g(yj)) = yj. The two functions undo each other. f^-1: X -> Y. Also, if f has an inverse, f is both 1:1 and onto. And vice versa.
* Linear Transformations: if xi and xj are arbitrary elements of X, c is a real number, and f is a function from X to Y; f is a linear transformation from X to Y if 1. f(xi) + f(xj) = f(xi + xj); 2. cf(xi) = f(cxi).
* Example: 2x would make a linear transformation; test it against the two formulae. 2x - 1 would **not** make a linear transformation; test.

### Combinations and Permutations
* remember that (n over r) = (n! OVER (r!(n-r)!). This is the binomial coefficient. 

### Not All “Rules for Ordering” Are Functions
* if there are multiple different ways to obey a command, it’s not a function.

## Matrices
### What is a Matrix
### Matrix Calculations
* Addition
* Subtraction
* Scalar Multiplication
* Matrix Multiplication

### Special Matrixes
* Zero Matrices: all elements are 0.
* Transpose Matrices: 
* Symmetric Matrices:
* Upper Triangular and Lower Triangular Matrices
* Diagonal Matrices
* Identity Matrices

## More Matrices
## Vectors
## More Vectors
## Linear Transformations
## Eigenvalues and Eigenvectors