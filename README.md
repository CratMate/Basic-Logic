## LOGICS TO REMEMBER 
# Finding number of digits:
    Using while loop = time complexity - O(count)
    Using floor(log(N)+1) = time complexity - O(1)
# Arithmetic Progression
    nth term of an AP = a + (n-1)*d.
    Sum of ‘n’ terms of an AP = 0.5 n (first term + last term) = 0.5 n [ 2a + (n-1) d ].
# Geometric Progression
    nth term of a GP = a*(r^n-1).
    Geometric Mean = nth root of product of n terms in the GP.
    Sum of ‘n’ terms of a GP (r < 1) = [a (1 – r^n)] / [1 – r].
    Sum of ‘n’ terms of a GP (r > 1) = [a (r^n – 1)] / [r – 1].
    Sum of infinite terms of a GP (r < 1) = (a) / (1 – r).
# Quadratic Equation
    a X^2 + b X + c = 0  [To derive root formula solve for X]
    roots = (-b ± √(b2 - 4ac))/2a 
    b2 = 4ac => roots are real and equal
    b2 > 4ac => roots are real and different
    b2 < 4ac => roots are complex
# Mean
    Average of sequence => Mean = [x1+x2+...+xn]/n
# Median
    Middle value of sequence after sorting
    if sequence id ODD => Median =  Middle value
    if sequence id EVEN => Median = [Average of two middle values]/2
# Prime Numbers 
    Iteration using for loop => time complexity - O(N)
    Efficient method = Seive of Eratosthenes
# LCM HCF/GCD
    gcd(a, b) {  //to find hcf/gcd using Euclidean algorithm
    if (a == 0) return b;
    return gcd(b % a, a); }
    time complexity = O(log(min(a,b)))
    -----------------
    For two numbers say, 'a' and 'b', LCM x HCF = a x b.
    HCF of co-primes = 1.
    For two fractions,
    HCF = HCF (Numerators) / LCM (Denominators)
    LCM = LCM (Numerators) / HCF (Denominators)
# Permutation
    n Pr = n! / (n - r)!
    n P n = n*(n-1)*(n-2)*......*1 = n!
    n P 0 = n! / n! = 1
    n P 1 = n
    n P n-1 = n!
    n P r/n P r-1 = n - r + 1
# Combination
    n C r = n! / [ (r !) * (n - r)! ]
    n C 0 = n C n = 1.
    n C r = n C n-r.
    n C r + n C r-1 = n+1 C r.
    n * n-1 C r-1 = (n - r + 1)* n C r-1
