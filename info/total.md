Accuracy is not the only important skill a sniper requires.
Snipers should have a quick mind and must make quick calculations to ensure they hit their mark.

For this mission, you are given the number **N** (which will be comprised of at least two digits). You must work to find the smallest positive number of **X** such that the product of its digits is equal to N.
If X does not exist, then you should return 0.

Let's look at an example. N = 20. We can factorize this number as 2\*10, but 10 is not a digit.
Also we can factorize it as 4\*5 or 2\*2\*5. The smallest number for 2\*2\*5 is 225, for 4\*5 -- 45. So we select 45.

**Input:** The number N as an integer. 

**Output:** The number X as an integer.

**Example:**

```python
reconstruct(20) == 45
reconstruct(21) == 37
reconstruct(17) == 0
reconstruct(33) == 0
```

**How it is used:**

This task will teach you how to work with numbers and simple math in code, teaching you to factorize numbers and reconstruct them into new numbers.
Of course you could try to solve this problem with brute force, but is that the best way?
Numbers are the foundation of mathematics and programming and you would do well to remember this.

**Precondition:**
```python
9 < number < 10 ** 5
```
