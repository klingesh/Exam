# 1️⃣ NUMBER SYSTEM

⏱️ **Study time: 45 minutes** | 🎯 **Typical questions: 3–5**

---

## 📖 PART 1 — CONCEPT: Types of Numbers

| Type | Meaning | Examples |
|---|---|---|
| **Natural (N)** | Counting numbers | 1, 2, 3, 4… |
| **Whole (W)** | Naturals + zero | 0, 1, 2, 3… |
| **Integers (Z)** | Negatives + zero + positives | …–2, –1, 0, 1, 2… |
| **Rational (Q)** | Can be written as p/q (q ≠ 0) | 3/4, 0.5, –7, 0.333… |
| **Irrational** | Cannot be written as p/q | √2, √3, π |
| **Prime** | Exactly 2 factors (1 and itself) | 2, 3, 5, 7, 11, 13… |
| **Composite** | More than 2 factors | 4, 6, 8, 9, 10… |
| **Co-prime** | Two numbers whose HCF = 1 | (8, 15), (9, 10) |

### ⚠️ Three facts examiners love
1. **1 is neither prime nor composite.**
2. **2 is the only even prime number.**
3. **0 is neither positive nor negative.**

### Primes from 1–50 (memorize these 15)
```
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47
```
There are **25 primes below 100.**

---

## 📖 PART 2 — DIVISIBILITY RULES ⭐ (most tested)

| Divisible by | Rule | Quick example |
|---|---|---|
| **2** | Last digit is even (0,2,4,6,8) | 3 4**6** ✔ |
| **3** | **Sum of digits** divisible by 3 | 4 5 1 → 4+5+1=10 ✘ |
| **4** | **Last 2 digits** divisible by 4 | 73**16** → 16÷4 ✔ |
| **5** | Last digit is 0 or 5 | 12**5** ✔ |
| **6** | Divisible by **2 AND 3** both | 1 3 2 → even ✔, sum 6 ✔ → ✔ |
| **7** | Double the last digit, subtract from rest. Repeat. | see below |
| **8** | **Last 3 digits** divisible by 8 | 45**120** → 120÷8 ✔ |
| **9** | **Sum of digits** divisible by 9 | 7 2 9 → 18 ✔ |
| **10** | Last digit is 0 | 45**0** ✔ |
| **11** | (Sum of odd-position digits) – (sum of even-position digits) = 0 or multiple of 11 | see below |
| **12** | Divisible by **3 AND 4** both | |

### 🔍 Rule of 7, step by step — Is **672** divisible by 7?
```
Step 1: Last digit = 2. Remaining number = 67.
Step 2: Double the last digit → 2 × 2 = 4
Step 3: Subtract from the rest → 67 – 4 = 63
Step 4: Is 63 divisible by 7? YES (7 × 9)
✅ So 672 IS divisible by 7.
```

### 🔍 Rule of 11, step by step — Is **4 8 1 5 2** divisible by 11?
```
Step 1: Number the positions from the LEFT.
        Position:  1   2   3   4   5
        Digit:     4   8   1   5   2

Step 2: Add the ODD positions  (1st, 3rd, 5th) → 4 + 1 + 2 = 7
Step 3: Add the EVEN positions (2nd, 4th)      → 8 + 5     = 13

Step 4: Difference → 13 – 7 = 6
Step 5: Is 6 zero or a multiple of 11? NO.
❌ So 48152 is NOT divisible by 11.
```

---

## 📖 PART 3 — HCF & LCM ⭐

| | HCF (Highest Common Factor) | LCM (Lowest Common Multiple) |
|---|---|---|
| **What it is** | Biggest number that divides all of them | Smallest number divisible by all of them |
| **In prime factors** | Take **common** primes, **lowest** power | Take **all** primes, **highest** power |
| **Think of it as** | "Greatest **shared** piece" | "First time they **meet** again" |

### 🔑 The golden formula
```
HCF × LCM = Product of the two numbers
```

### 🔍 Worked example — Find HCF and LCM of 24 and 36

```
Step 1: Prime factorise both.
        24 = 2 × 2 × 2 × 3 = 2³ × 3¹
        36 = 2 × 2 × 3 × 3 = 2² × 3²

Step 2: HCF → common primes, LOWEST power.
        Common primes: 2 and 3
        Lowest power of 2 → 2²
        Lowest power of 3 → 3¹
        HCF = 2² × 3 = 4 × 3 = 12

Step 3: LCM → all primes, HIGHEST power.
        Highest power of 2 → 2³
        Highest power of 3 → 3²
        LCM = 8 × 9 = 72

Step 4: VERIFY with the golden formula.
        HCF × LCM = 12 × 72 = 864
        24 × 36            = 864   ✅ Matches.
```

### 🎯 The 4 classic HCF/LCM question patterns

**Pattern A — "Smallest number divisible by all"** → just take the LCM.

**Pattern B — "Smallest number leaving the SAME remainder r"**
```
Answer = LCM + r
```
*Q: Smallest number which when divided by 5, 6 and 7 leaves remainder 3?*
```
LCM(5,6,7) = 210  →  Answer = 210 + 3 = 213
```

**Pattern C — "Remainders are each 1 LESS than the divisor"**
```
Answer = LCM – 1
```
*Q: Least number which leaves remainder 5 when divided by 6, remainder 4 by 5, remainder 3 by 4?*
```
Notice: 6–5=1, 5–4=1, 4–3=1  → all short by 1
LCM(6,5,4) = 60  →  Answer = 60 – 1 = 59
```

**Pattern D — "Largest number dividing x, y, z leaving the same remainder"**
```
Answer = HCF of the DIFFERENCES
```
*Q: Largest number that divides 43, 91 and 183 leaving the same remainder?*
```
Differences: 91–43 = 48,  183–91 = 92,  183–43 = 140
HCF(48, 92, 140) = 4   →  Answer = 4
```

---

## 📖 PART 4 — UNIT DIGIT (CYCLICITY) ⭐⭐

**Question type:** "What is the last digit of 7¹⁰⁵?"
You will never calculate this. You use the **cycle**.

### The cyclicity table (memorize)

| Base ends in | Cycle of last digits | Cycle length |
|---|---|---|
| **0** | 0 | 1 |
| **1** | 1 | 1 |
| **5** | 5 | 1 |
| **6** | 6 | 1 |
| **4** | 4, 6 | 2 |
| **9** | 9, 1 | 2 |
| **2** | 2, 4, 8, 6 | 4 |
| **3** | 3, 9, 7, 1 | 4 |
| **7** | 7, 9, 3, 1 | 4 |
| **8** | 8, 4, 2, 6 | 4 |

> 💡 **Memory hook:** 0,1,5,6 never change. 4 and 9 flip between two. 2,3,7,8 have a 4-cycle.

### 🔍 Worked example — Find the unit digit of **7¹⁰⁵**

```
Step 1: Base ends in 7 → cycle length is 4, cycle = (7, 9, 3, 1)

Step 2: Divide the POWER by the cycle length.
        105 ÷ 4 = 26 remainder 1

Step 3: Use the remainder to pick from the cycle.
        Remainder 1 → 1st item in cycle → 7
        (Remainder 2 → 9,  Remainder 3 → 3,  Remainder 0 → 1, the LAST item)

✅ Unit digit of 7¹⁰⁵ = 7
```

### 🔍 Worked example — Unit digit of **2⁵⁹**
```
Step 1: Cycle of 2 = (2, 4, 8, 6), length 4
Step 2: 59 ÷ 4 = 14 remainder 3
Step 3: Remainder 3 → 3rd item → 8
✅ Answer = 8
```

> ⚠️ **The trap:** when the remainder is **0**, take the **LAST** item of the cycle, not the first.
> Unit digit of 3¹² → 12 ÷ 4 = rem 0 → last item of (3,9,7,1) → **1**

---

## 📖 PART 5 — NUMBER OF FACTORS

```
If N = a^p × b^q × c^r   (a, b, c are primes)

Number of factors = (p+1)(q+1)(r+1)
```

### 🔍 Worked example — How many factors does 720 have?
```
Step 1: Prime factorise.
        720 = 72 × 10 = (8 × 9) × (2 × 5) = 2³ × 3² × 2 × 5 = 2⁴ × 3² × 5¹

Step 2: Take each power, add 1, multiply.
        Powers are 4, 2, 1
        (4+1) × (2+1) × (1+1) = 5 × 3 × 2 = 30

✅ 720 has 30 factors.
```

---

## 📖 PART 6 — TRAILING ZEROS IN A FACTORIAL

A trailing zero needs a 2 and a 5 paired. Factorials always have more 2s than 5s, so:
**count the 5s.**

```
Zeros in n! = [n/5] + [n/25] + [n/125] + …        ([ ] = ignore the decimal)
```

### 🔍 Worked example — Number of trailing zeros in **100!**
```
Step 1: 100 ÷ 5   = 20
Step 2: 100 ÷ 25  = 4
Step 3: 100 ÷ 125 = 0  → stop

Step 4: Add → 20 + 4 = 24
✅ 100! ends with 24 zeros.
```

---

## 📖 PART 7 — REMAINDERS (the easy trick)

**Key idea:** you can replace a number by its remainder before doing the power.

### 🔍 Worked example — Remainder when **17²³** is divided by 16
```
Step 1: What is 17 itself leaving as remainder with 16?
        17 = 16 × 1 + 1   → remainder 1

Step 2: So 17²³ behaves like 1²³ = 1

✅ Remainder = 1
```

### 🔍 Worked example — Remainder when **2³¹** is divided by 5
```
Step 1: Find the pattern of 2's powers with 5.
        2¹ = 2  → rem 2
        2² = 4  → rem 4
        2³ = 8  → rem 3
        2⁴ = 16 → rem 1   ← pattern restarts here, so cycle length = 4

Step 2: 31 ÷ 4 = 7 remainder 3

Step 3: Remainder 3 → 3rd value in the pattern → 3

✅ Remainder = 3
```

---

## 📖 PART 8 — SUM FORMULAS (memorize)

| Sum of… | Formula | Check with n = 5 |
|---|---|---|
| First n natural numbers | **n(n+1)/2** | 5·6/2 = 15 = 1+2+3+4+5 ✔ |
| First n **odd** numbers | **n²** | 25 = 1+3+5+7+9 ✔ |
| First n **even** numbers | **n(n+1)** | 30 = 2+4+6+8+10 ✔ |
| Squares of first n | **n(n+1)(2n+1)/6** | 5·6·11/6 = 55 ✔ |
| Cubes of first n | **[n(n+1)/2]²** | 15² = 225 ✔ |

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **Squaring a number ending in 5:** 35² → take 3, do 3×(3+1) = 12, stick 25 on → **1225**. 65² → 6×7=42 → **4225**.

2. **Multiply by 11 (2-digit):** 43 × 11 → split 4_3, put 4+3=7 in the middle → **473**.

3. **a² – b² = (a+b)(a–b).** So 51² – 49² = (100)(2) = **200**. Instantly.

4. **Largest n-digit number divisible by k:** divide, drop the decimals, multiply back.
   *Largest 4-digit number divisible by 88?* 9999 ÷ 88 = 113.6 → 113 × 88 = **9944**

5. **Two numbers in ratio a:b with HCF h** → the numbers are **ah** and **bh**, and **LCM = abh**.
   *Ratio 3:4, HCF 4 → numbers 12 and 16, LCM = 3×4×4 = 48*

6. **To test if a number is prime,** you only need to check division by primes up to its square root. For 97: √97 ≈ 9.8, so test 2, 3, 5, 7 only. None divide → prime.

---

## ✍️ PRACTICE (do these — 15 min)

1. Find the unit digit of 3⁴⁷.
2. Find the HCF and LCM of 108 and 144.
3. How many factors does 360 have?
4. How many trailing zeros does 50! have?
5. Find the smallest number which, when divided by 12, 15 and 20, leaves remainder 5 in each case.
6. Find the remainder when 2³¹ is divided by 5.
7. Is 5,72,168 divisible by 8?
8. Find the sum of the first 30 natural numbers.
9. Find the largest 4-digit number exactly divisible by 88.
10. Two numbers are in the ratio 3 : 4 and their HCF is 4. Find their LCM.
11. Compute 4001² – 3999² without long multiplication.
12. Find the unit digit of 8²².

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **7** — cycle of 3 is (3,9,7,1); 47 ÷ 4 = rem 3 → 3rd item → 7
2. **HCF = 36, LCM = 432** — 108 = 2²·3³, 144 = 2⁴·3². HCF = 2²·3² = 36; LCM = 2⁴·3³ = 432. Check: 36 × 432 = 15552 = 108 × 144 ✔
3. **24** — 360 = 2³·3²·5¹ → (3+1)(2+1)(1+1) = 4·3·2 = 24
4. **12** — 50÷5 = 10, 50÷25 = 2, total 12
5. **65** — LCM(12,15,20) = 60, then 60 + 5 = 65
6. **3** — pattern of 2 mod 5 is (2,4,3,1); 31 ÷ 4 = rem 3 → 3
7. **Yes** — last 3 digits are 168, and 168 ÷ 8 = 21 exactly
8. **465** — 30 × 31 / 2 = 465
9. **9944** — 9999 ÷ 88 = 113.6…; 113 × 88 = 9944
10. **48** — numbers are 12 and 16; LCM = 3 × 4 × 4 = 48
11. **16000** — (4001+3999)(4001–3999) = 8000 × 2 = 16000
12. **4** — cycle of 8 is (8,4,2,6); 22 ÷ 4 = rem 2 → 2nd item → 4

</details>

---

## 🎯 QUICK RECAP — say these out loud

- Divisibility: **3 & 9 → digit sum**, **4 → last 2 digits**, **8 → last 3 digits**, **11 → odd minus even positions**
- **HCF × LCM = product of the numbers**
- Same remainder r → **LCM + r**. All short by 1 → **LCM – 1**. Same remainder, unknown → **HCF of differences**
- Unit digit → divide power by 4, use remainder. **Remainder 0 = last item of the cycle**
- Factors of a^p·b^q → **(p+1)(q+1)**
- Trailing zeros → **count the 5s**
- 1 is not prime. 2 is the only even prime. 25 primes below 100.

➡️ **Next:** [02-percentage.md](02-percentage.md) — the most important topic in the whole paper.
