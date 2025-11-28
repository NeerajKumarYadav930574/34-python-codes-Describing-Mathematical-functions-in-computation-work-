# 34-python-codes-Describing-Mathematical-functions-in-computation-work-
These 34 python programmes describes how we can use mathematical function in computional work which builds the foundation of highend tasks of cybersecurity, data predection and data analytics.  

📌 Repository Includes

🧮 Basic Arithmetic & Digit Operations

1. Factorial calculation -: Computes n! using a loop; includes time and memory estimation.
Efficient for moderate values; complexity O(n).
2. Palindrome number checker -: Checks if a number reads the same backwards, reports steps, time, memory.
3. Mean of digits -: Returns the average of digits in an integer; complexity O(d).
4. Digital root -: Repeatedly sums digits until a single digit remains; shows iteration count.
5. Abundant number check -: Returns True if sum of proper divisors > n.
6. Deficient number check-: Returns True if sum of proper divisors < n and reports iterations.
7. Harshad (Niven) number check-: Checks if number divisible by sum of its digits.
8. Automorphic number check-: Checks if n² ends with n (e.g., 25 → 625).
9. Pronic number check-: Checks if n = k(k+1).


🔢 Prime, Divisors & Special Numbers

10. Prime factorization-: Extracts all prime factors and prints memory/time stats.
11. Count distinct prime factors-: Uses prime factorization and counts unique primes.
12. Prime power check-: Checks if n = pᵏ for some prime p and k ≥ 1.
13. Mersenne prime check-: Checks if (2ᵖ – 1) is prime using Lucas–Lehmer test.
14. Twin primes up to a limit-: Generates all twin prime pairs up to the specified limit.
15. Total number of divisors (d(n))-: Counts all divisors using sqrt method.
16. Aliquot sum-: Sum of all proper divisors (used in abundance, deficiency, amicable checks).
17. Amicable number check-: Checks if two numbers form an amicable pair.
18. Multiplicative persistence-: Counts steps to reduce number by multiplying digits repeatedl
19. Highly composite number check-: Checks if n has more divisors than any number < n.


⚙ Modular Arithmetic & Cryptography

20. Modular exponentiation-:Fast power with modulus using binary exponentiation.
21. Modular multiplicative inverse-:Uses Extended Euclidean Algorithm to find inverse modulo m.
22. Chinese Remainder Theorem solver-:Solves simultaneous congruences for coprime moduli.
23. Quadratic residue checker (Euler criterion)-:Uses Euler’s criterion to determine if x² ≡ a (mod p) has a solution.
24. Order of a modulo n-:Smallest k for which aᵏ ≡ 1 (mod n).
25. Fibonacci prime check-:Checks if number is both Fibonacci and prime.



🌿 Sequences & Mathematical Series

26. Lucas sequence generator-:Generates first n Lucas numbers.
27. Polygonal numbers-:General formula for s-gonal number.
28. Collatz sequence length-:Counts steps in Collatz conjecture (3n+1 rule).
29. Polygonal number summary with performance metrics-:Shows triangular, square, pentagonal examples with performance metrics.


🔐 Advanced Mathematical Algorithms

30. Carmichael number check-:Checks if composite number satisfies Fermat’s condition for all coprime a.
31. Miller–Rabin probabilistic primality test-:Probabilistic primality test suitable for very large numbers.
32. Pollard’s Rho integer factorization-:Fast integer factorization using Floyd’s cycle-finding.
33. Riemann zeta approximation (s)-:Approximates (s) via partial series.
34. Partition function p(n) using Euler’s pentagonal theorem-:Number of integer partitions using Euler’s pentagonal number theorem.


TECHNOLOGIES USED
1. PYTHON 3
2. time module
3. math module
4. tracemalloc for memory profilling
5. random for probabilistic algorithms
6. sys for size and systrm metrics

SKILLS ACHIEVED
While building the project , I developed a strong understanding of python programming and mathematical computaation . Working through 34 differnt algorithms improved my ability to write clean, efficient and well structured codes . I become confident in handling loops , conditions logic , modular arithematic and recursion-based ideas .The project also strengthened my knowledge of number theory, including prime numbers, divisors, modular exponentiation, factorization techniques, and various mathematical sequences like Fibonacci, Lucas, and polygonal numbers.
In addition to mathematical insight, this project helped me understand performance analysis—measuring execution time, estimating memory usage, and evaluating the computational complexity of each algorithm. I also learned how to convert mathematical formulas into optimized code and how to structure a large multi-function program in a readable and maintainable manner. Overall, this project significantly improved my problem-solving skills, analytical thinking, and programming discipline.



DIFFICULTIES FACED
One of the main challenges I faced during this project was handling large numbers and ensuring every program executed efficiently. Algorithms like factorial computation, partition function, Pollard’s Rho, and Mersenne prime checks involved massive values and required careful handling to avoid slowdowns or memory issues. Implementing advanced number-theoretic algorithms such as the Miller–Rabin primality test and the Lucas–Lehmer test was also challenging because they required a mix of mathematical understanding and
precise coding logic.
Another difficulty was managing all 34 programs inside a single script while keeping the structure clean and readable. Ensuring that each function handled edge cases correctly—like non-coprime numbers in modular inverses, invalid primes for quadratic residue checks, or large sequences in the Collatz process—also required extra care. Despite these challenges, each difficulty helped me learn something new and improved the overall quality of the project.

FUTURE IMPROVEMENT 
In the future, I plan to expand this project by making the programs more interactive and user-friendly. One of the first improvements will be creating a menu-driven interface so that users can select which algorithm they want to run without scrolling through the entire script. I also aim to build a graphical interface (using Tkinter or PyQt) and possibly a web-based version using Flask or FastAPI so that these algorithms can be used easily without running Python code manually.
Another planned improvement is to break the large script into 34 separate modules for better organization and readability. I also want to include visualizations—for example, plots of Collatz sequences, prime distributions, or Lucas/Fibonacci growth patterns. Over time, I hope to optimize more of the algorithms, add new mathematical functions, and turn this into a full mathematics toolkit.






