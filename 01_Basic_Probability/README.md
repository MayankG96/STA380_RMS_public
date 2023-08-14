Answer 1
Let the total be x
Random =0.3x
Yes_confirmed =0.5*0.3x
No confirmed = 0.5*0.3x
Total yes = 0.65x
Remaining Yes = 0.65x-0.15x == 0.5x
Total No =0.35x
Remaining No =0.2x
Total truthful = 0.7x
Fraction = 0.5*100/0.7
Ans: 71.43%

Answer 2
A: Someone Tests Positive
B: Someone has the disease

P(B) = 0.000025 (prob of having the disease).
P(A|B) = 0.993 (prob of testing positive if they have the disease).
P(~A|~B) = 0.9999 (prob of testing negative if they dont have the disease).
To Find - Prob of having the disease if they are positive. Therefore P(B|A).

Bayes' theorem:
P(B|A) = P(A|B)*P(B)/P(A)


Given P(A|B) and P(B)
P(A) - Prob of testing positive, irrespective of having a disease or no. Therefore True Positive and False Positive.

P(A) = P(A|B) * P(B) + P(A|~B) * P(~B)
P(A) = 0.993 * 0.000025 + (1 - 0.9999) * (1 - 0.000025)
P(A) = 0.000024825 + 0.999975
P(A) = 0.0001248225

Now, we can calculate P(B|A):
P(B|A) = P(A|B) * P(B) / P(A)
P(B|A) = 0.993 * 0.000025/0.0001248225
P(B|A) = 0.1989

Therefore answer is 19.89%
