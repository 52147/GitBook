---
description: Thursday, November 11th 6:00 pm-8:45 pm
---

# 🐶 Boolean Algebra

{% hint style="info" %}
**George Boole:**&#x20;

We may map the logical dichotomy "true or false" to mathematical bits or binary digits "0 or 1" and then to electric switches "open or closed".

Boole's symbolic logic proved suitable for the design of modern computers.
{% endhint %}

## Boolean variable

## Boolean function

### How many boolean function of variable are there?

f(x) = 0, f(x) = x\*x'

f: B -> B

|B| = 2

2^2 = 4

### How many boolean function of variable are there?

f: B\*B -> B

&#x20;f(x,y) = x+y'

B = {00,01,10,11}

B\*B-> {0,1}

2^4 =16

### How many boolean function of 3 variables are there?

|B\*B\*B| =8 -> |B| =2 ->2^8 =256

### How many boolean function of n variables are there?

Domain : B\*B\*......\*B (n times)

Co-domain : B

total number of function = 2^2^n

### It is possible to have 2 Boolean function that look different, but in fact they yield the same result.



&#x20;

Properties of Boolean Algebra:

1. x+y =y+x
2. x\*y = y\*x
3. x'' =x
4. (x+y) +z  = x +(y+z)
5. (x\*y)\*z = x\*(y\*z)
6. x\*x' =0
7. x+x' =1
8. x+0 =x
9. x+1 =1
10. x\*1 =x
11. x\*x =x
12. x+x =x
13. (x\*y)' =x'+y'  <mark style="background-color:orange;">(De Morgan's Laws)</mark>
14. (x+y)' = x'+y'  <mark style="background-color:orange;">(De Morgan's Laws)</mark>
15. x\*(y+z) = x\*y +y\*z
16. x + (y\*z) =(x+y)\*(x+z)

Prove the following statement:

"If x\*y is 0 and x+y is 1 then x is the negation of y"

(x\*y = 0 & x+y =1) -> x =y'

Proof:

x = x\*1(probability#10)

&#x20;  \= x\*(y+y') (ppty #7)

&#x20; \=x\*y + x\*y' (ppty #15)

&#x20; \=0 + x\*y' (hypothesis)

&#x20;\=y\*y' +x\*y (ppty # 6)

&#x20;\=(y+x)\*y'(ppty #)

&#x20;\= (x+y)\* y' (ppty #1)

&#x20;\= 1\*y' (hypothese)

\= y'(ppty #10)



