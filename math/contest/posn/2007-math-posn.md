# 2007 Math POSN: mistertfy64's "Answers"
These are my answers for practicing the math POSN.

This exam was given out to 7th to 11th grade students.

The exam has 30 questions, a 3-hour time limit, and is used as a selection test for olympiad camps.

Although this exam is in Thai, I've translated the questions to English.

This exam was found in a book that had the solutions to the past paper exams.

No calculators are allowed in the exam, however, since this is not a real exam setting, I used a calculator anyway.

Disclaimer: I did use online resources, such as formulas (in case I forget), etc.
# Questions
## Question 1

**Question:** *(abridged)* How many Friday the 13ths are there in 2007? (Assume that January 1, 2007 is a Monday.)


**My Answer:** (to be filled in)


## Question 2

**Question:** Find the lowest positive integer $n > 2$ where $\frac{n^2}{n2+13}$ is not a simplified fraction.

**My Answer:** $9$ (2023-04-15)

My approach is to find a integer $n$ where ${n^2+13}$ is not a prime number.

I would guess-and-check (because I'm stupid) the numbers from $4$, while also calculating for the numerator of the fraction (skipping $3$ because $3-2=1$, and that makes it a simplified fraction) and so on...
$4^2+13=29$, $5^2+13=38$, $6^2+13=49$, $7^2+13=62$, $8^2+13=77$, $9^2+13=94$

**Correct Answer:** $19$

Apparently the book also used guess-and-check. I guess that's what happens when you use guess-and-check: you accidentally make mistakes.

## Question 3

**Question:** (abridged) $f(n) = n^3$, $g(n) = f(n+1) - f(n)$, What is $\frac{1}{10}(g(0)+g(1)+g(2)+\cdots+g(9))$?

**My Answer:** $100$

My approach is to use the formula for the difference of cubes, $a^3-b^3=(a-b)(a^2+ab+b^2)$.

However, since $g(n) = f(n+1)-f(n)$, the first part of the difference of cubes formula would always be $1$ (because $n+1-n=1$), so I only need to calculate $a^2+ab+b^2$. Additionally, since $a^2+ab+b^2 = (a+b)^2-ab$, I can further "rewrite" the equation as 

$g(n) = (2n-1)^2-(n+1)(n)$

$\Rightarrow g(n) = 4n^2+4n+1-(n^2+n)$.

$\Rightarrow g(n) = 3n^2+3n+1$.

Therefore I would get 

$\text{Answer} = \frac{1}{10}(10+135+855)$

$\Rightarrow \text{Answer} = \frac{1}{10}(1000)$

$\Rightarrow \text{Answer} = 100$

**Correct Answer:** $100$

The book used a much simpler method. According to it, substituting $g$ with $f$ gives:

$\{f(1)-f(0))+(f(2)-f(1))+\cdots+(f(10)-f(9)\}$

$= f(10)-f(9)+f(9)-f(8)+\cdots+f(1)-f(0)$

$= f(10)-f(0)$

$= 10^3-0^3$

$=100$

