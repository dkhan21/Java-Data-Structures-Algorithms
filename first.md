output: pdf_document
# HW3-Numbers by Daniyal Khan

---

### Student Details
- **Name:** Daniyal Khan
- **Email:** dak@njit.edu

### Course Details
- **Course Name:** CS435
- **Instructor:** Prof Nassimi


---


1. **Question 1**


   a.

        Question:

        List all prime numbers between 2 and 100. Use the fact that a composite integer 𝑛 must have a prime factor ≤ √𝑛 to limit the search. Thus, a number < 100 is prime if and only if it is not a factor of {2, 3, 5, 7}.

        Answer:

        The number that are prime fromt he range of 2 and 100 are:
        {2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 61, 67, 71, 73, 79, 83, 89, 97}


    
   b.

        Question:

        How many prime numbers are there in your list in the range 2 to 100?

        Answer: 25
<br style="page-break-before: always;">


2. **Question 2**

   a. 

        Question:

        Find the Greatest-Common-Divisor (GCD) of the following pair of numbers by finding their prime factorizations: 𝑎 = 7623, 𝑏 = 425.

        Answer: 

            7623 / 3 = 2541
            2541 / 3 = 847
            847 / 7 = 121
            121 / 11 = 11
            11 / 11 = 1

            3 * 3 * 7 * 11 * 11

            7425 / 3 = 2475 
            2475 / 3 = 825
            825 / 3 = 275
            275 / 5 = 55
            55 / 5 = 11
            11 / 11 = 1 

            3 * 3 * 3 * 5 * 5 * 11

            Both:
            3 * 3 * 7 * 11 * 11
            3 * 3 * 3 * 5 * 5 * 11

            Similarities change it to: 3^2 * 11 = 99

            GCD(7623, 7425) = 3^2 * 11 = 99
    
    b. 

        Question:

        Use Euclid’s algorithm to find GCD of the above integers 𝑎, 𝑏. Use the iterative algorithm. Also show the computation of integers (𝑠, 𝑡) so that gcd(𝑎, 𝑏) = 𝑠𝑎 + 𝑡𝑏.
        
        Answer: 

         | (s, t) a | (s, t) b |     a    |    b     | quotient |Remainder |
         |----------|----------|----------|----------|----------|----------|
         | (1, 0)   | (0, 1)   |   7623   |   7425   |     1    | Cell 6   |
         | (0, 1)   | (-1, 1)  |   7425   |   198    |    37    | Cell 12  |
         | (1, -1)  |(-37, 38) |   198    |    99    |     2    |     0    |
         |(-37, 38) |  (0, 0)  |    99    |     0    |          |          |

         (s, t) = (-37, 38)
         GCD(7623, 7425) = -37 * 7623  + 38 * 7425 = 99

3. **Question 3**

   a.
         Question:
         Find inverse of integers 1 to 10 mod 11. Tabulate the results. You may find the values by inspection.

         Answer: 

          1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 
         |--|---|---|---|---|---|---|---|---|----
          1   6   4   3   9   2   8   7   5   10   

         

4. **Question 4**

   [Your question goes here]

5. **Question 5**

   [Your question goes here]

6. **Question 6**

   [Your question goes here]

7. **Question 7**

   [Your question goes here]

8. **Question 8**

   [Your question goes here]

9. **Question 9**

   [Your question goes here]

10. **Question 10**

    [Your question goes here]
