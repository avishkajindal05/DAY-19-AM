Q1 — What is the difference between loops, list comprehension, and higher-order functions in Python? When would you use each?
Q2 (Coding) — Implement a function using list comprehension to:
● Flatten a nested list
● Remove all even numbers
Q3 — What is hypothesis testing? Explain null hypothesis, p-value, and significance level with an example

ans1:
Loops → flexible, readable for complex logic
List comprehension → concise, faster for simple transforms
Higher-order functions → functional style, useful in pipelines

ans2:
nested = [[1,2,3],[4,5,6],[7,8]]
flatten = [x for sub in nested for x in sub]
odd_only = [x for x in flatten if x % 2 != 0]
print(odd_only)

ans3:
Null Hypothesis (H₀): no effect
p-value: probability of observing result if H₀ true
Significance level (α): threshold (0.05)
Example:
Testing if new teaching method improves marks.