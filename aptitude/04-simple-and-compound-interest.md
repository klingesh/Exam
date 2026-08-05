# 4️⃣ SIMPLE & COMPOUND INTEREST

⏱️ **Study time: 45 minutes** | 🎯 **Typical questions: 2–4**

> ✅ **Good news:** this is the most formula-driven topic in the paper. There is almost no "thinking" required — recognise the type, plug in, compute. Easy marks if you know 5 formulas.

---

## 📖 PART 1 — THE VOCABULARY

| Term | Symbol | Meaning |
|---|---|---|
| **Principal** | P | The money originally borrowed/invested |
| **Rate** | R or r | Interest rate **per year** (%) |
| **Time** | T or n | Duration **in years** |
| **Interest** | SI / CI | The extra money earned |
| **Amount** | A | Principal + Interest (the total) |

### The one-line difference between SI and CI

| | Simple Interest | Compound Interest |
|---|---|---|
| Interest is calculated on… | the **original** principal, every year | the **new balance** (principal + interest so far) |
| Yearly interest amount | **same** every year | **grows** every year |
| Real-world example | some fixed loans | bank savings, FDs, mutual funds, population growth |

### 🔍 See the difference — ₹1,000 at 10% for 3 years

**Simple Interest** (interest always on the original ₹1,000):
| Year | Interest | Balance |
|---|---|---|
| 1 | 10% of 1000 = 100 | 1,100 |
| 2 | 10% of 1000 = 100 | 1,200 |
| 3 | 10% of 1000 = 100 | 1,300 |
| | **SI = ₹300** | |

**Compound Interest** (interest on the growing balance):
| Year | Interest | Balance |
|---|---|---|
| 1 | 10% of 1000 = 100 | 1,100 |
| 2 | 10% of 1100 = 110 | 1,210 |
| 3 | 10% of 1210 = 121 | 1,331 |
| | **CI = ₹331** | |

**CI – SI = ₹31.** That gap is what most exam questions are secretly about.

> 💡 **CI is ALWAYS ≥ SI** (they're equal only for the first year at yearly compounding). If you ever compute CI less than SI, you've made an arithmetic error.

---

## 📖 PART 2 — SIMPLE INTEREST FORMULAS

```
        P × R × T
SI  =  ───────────
           100

Amount = P + SI

Rearranged (know all four — questions ask for each):

P =  SI × 100 / (R × T)
R =  SI × 100 / (P × T)
T =  SI × 100 / (P × R)
```

### 🔍 Example 1 — Straightforward SI
*Find the simple interest on ₹5,000 at 8% per annum for 3 years.*
```
Step 1: Write the formula.  SI = P × R × T / 100
Step 2: Substitute.         SI = 5000 × 8 × 3 / 100
Step 3: Numerator.          5000 × 8 = 40,000;  40,000 × 3 = 1,20,000
Step 4: Divide by 100.      1,20,000 / 100 = 1,200
✅ SI = ₹1,200   (Amount = 5000 + 1200 = ₹6,200)
```

### 🔍 Example 2 — Find the time
*In what time will ₹8,000 amount to ₹9,200 at 5% per annum simple interest?*
```
Step 1: The question gives the AMOUNT, not the interest. Extract SI first.
        SI = Amount – P = 9200 – 8000 = ₹1,200

Step 2: Use T = SI × 100 / (P × R)
        T = 1200 × 100 / (8000 × 5)

Step 3: T = 1,20,000 / 40,000 = 3

✅ T = 3 years
```
> 🚨 **The trap:** if the question says "amounts to", you must subtract P to get the interest. Plugging ₹9,200 in as SI is a very common error.

### 🔍 Example 3 — The "doubles / triples" pattern ⭐
```
For SI, if a sum becomes k times itself in T years:

Rate =  (k – 1) × 100 / T
```
*A sum of money doubles itself in 8 years at simple interest. Find the rate.*
```
Step 1: Doubles → k = 2, so the INTEREST earned = 1 × P (it grew by P).
Step 2: Rate = (2 – 1) × 100 / 8 = 100/8 = 12.5%
✅ Rate = 12.5% per annum

Sanity check: 12.5% × 8 years = 100% of P as interest → yes, it doubled ✔
```
*Triples in 12 years?* → `(3–1) × 100 / 12 = 200/12 = 16.67%`

---

## 📖 PART 3 — COMPOUND INTEREST FORMULAS ⭐

```
                    R  ⁿ
Amount  =  P ( 1 + ─── )
                   100

CI = Amount – P
```

⚠️ **CI is the amount MINUS the principal.** Forgetting to subtract P is the single most common CI mistake. Read the question: does it want the *interest* or the *amount*?

### 🔍 Example 4 — Basic CI
*Find the compound interest on ₹10,000 at 10% per annum for 2 years.*
```
Step 1: Amount = P (1 + R/100)ⁿ
Step 2: Amount = 10000 (1 + 10/100)²
Step 3:        = 10000 (1.10)²
Step 4:        = 10000 × 1.21 = ₹12,100
Step 5: CI = Amount – P = 12100 – 10000 = ₹2,100

✅ CI = ₹2,100
```

### 🔍 Example 5 — Different rates for different years
*Find the amount on ₹8,000 for 2 years if the rate is 10% in year 1 and 12% in year 2.*
```
Step 1: When rates differ, just chain the multipliers.
        Amount = P × (1 + r₁/100) × (1 + r₂/100)

Step 2: Amount = 8000 × 1.10 × 1.12

Step 3: 8000 × 1.10 = 8,800
        8,800 × 1.12 = 9,856

✅ Amount = ₹9,856   (CI = ₹1,856)
```

---

## 📖 PART 4 — HALF-YEARLY & QUARTERLY COMPOUNDING ⭐

When compounding happens more often than once a year, **adjust both the rate and the time**:

| Compounded | Rate becomes | Time becomes |
|---|---|---|
| Annually | R | n |
| **Half-yearly** | **R/2** | **2n** |
| **Quarterly** | **R/4** | **4n** |
| Monthly | R/12 | 12n |

### 🔍 Example 6 — Half-yearly
*Find the CI on ₹8,000 at 10% per annum for 1 year, compounded half-yearly.*
```
Step 1: Adjust. Rate = 10/2 = 5% per half-year.
                 Time = 1 × 2 = 2 half-years.

Step 2: Amount = 8000 (1 + 5/100)²
Step 3:        = 8000 (1.05)²
Step 4:        = 8000 × 1.1025 = ₹8,820
Step 5: CI = 8820 – 8000 = ₹820

✅ CI = ₹820

Compare: yearly compounding would have given only ₹800.
More frequent compounding → more interest. Always.
```

---

## 📖 PART 5 — THE DIFFERENCE BETWEEN CI AND SI ⭐⭐

This is the **most asked** question type in this topic. Memorize these two.

```
                          R   2
For 2 years:   CI – SI = P(───)
                         100

                          R   2      R
For 3 years:   CI – SI = P(───) × (3 + ───)
                         100         100
```

### 🔍 Example 7 — Two-year difference
*Find the difference between CI and SI on ₹8,000 at 5% per annum for 2 years.*
```
Step 1: Use CI – SI = P (R/100)²
Step 2: = 8000 × (5/100)²
Step 3: = 8000 × (0.05)²
Step 4: = 8000 × 0.0025
Step 5: = ₹20

✅ Difference = ₹20

Verify the long way:
   SI = 8000 × 5 × 2 / 100 = ₹800
   CI: Amount = 8000 × (1.05)² = 8000 × 1.1025 = 8,820 → CI = ₹820
   820 – 800 = ₹20  ✔
```

### 🔍 Example 8 — Working backwards from the difference
*The difference between CI and SI on a sum at 10% per annum for 2 years is ₹65. Find the sum.*
```
Step 1: CI – SI = P (R/100)²
Step 2: 65 = P × (0.10)²
Step 3: 65 = P × 0.01
Step 4: P = 65 / 0.01 = 6,500

✅ Principal = ₹6,500
```

### 🔍 Example 9 — Three-year difference
*Difference between CI and SI on ₹15,000 at 10% for 3 years?*
```
Step 1: CI – SI = P (R/100)² × (3 + R/100)
Step 2: = 15000 × (0.10)² × (3 + 0.10)
Step 3: = 15000 × 0.01 × 3.10
Step 4: = 150 × 3.10 = ₹465

✅ Difference = ₹465

Verify: SI = 15000×10×3/100 = 4,500
        Amount = 15000 × 1.331 = 19,965 → CI = 4,965
        4965 – 4500 = 465 ✔
```

---

## 📖 PART 6 — THE "TWO TIME PERIODS" CI PATTERN ⭐

*A sum amounts to ₹6,690 in 3 years and to ₹10,035 in 6 years at compound interest. Find the sum.*

```
Step 1: Write both statements.
        P(1+r)³ = 6,690        … (i)
        P(1+r)⁶ = 10,035       … (ii)

Step 2: DIVIDE (ii) by (i). This kills P and gives you the growth factor.
        (1+r)³ = 10,035 / 6,690 = 1.5

Step 3: Substitute back into (i).
        P × 1.5 = 6,690
        P = 6,690 / 1.5 = 4,460

✅ Principal = ₹4,460
```
> 🧠 **The trick:** when two amounts are given at two times, **divide the equations**. Never try to find r first.

---

## 📖 PART 7 — INSTALMENTS (quick version)

If a sum P is repaid in equal annual instalments of X at r% compound interest for 2 years:
```
        X            X
P =  ────────  +  ────────
     (1+r/100)   (1+r/100)²
```
*(Low priority — skip if short on time. It appears rarely.)*

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **SI is linear — so scale it freely.** If SI for 3 years is ₹600, then for 5 years it's `600 × 5/3 = ₹1,000`. No formula needed.

2. **Learn these CI multipliers by heart:**
   | Rate | 2 years | 3 years |
   |---|---|---|
   | 5% | 1.1025 | 1.157625 |
   | 10% | 1.21 | 1.331 |
   | 20% | 1.44 | 1.728 |

3. **The 2-year CI shortcut:** CI for 2 years = `2R + R²/100` percent of P.
   At 10%: `20 + 1 = 21%` of P. At 5%: `10 + 0.25 = 10.25%` of P. Instant.

4. **Rule of 72 (for CI doubling):** time to double ≈ **72 / R**.
   At 8% → about 9 years. At 12% → about 6 years. Great for eliminating MCQ options.

5. **SI doubling/tripling:** doubles → `100/R` years. Triples → `200/R` years.

6. **If CI doubles a sum in n years, it becomes 4× in 2n years and 8× in 3n years.** (It squares/cubes, it doesn't multiply.) A classic trap: "doubles in 5 years, so 4× in 10 years" — correct. "8× in 15 years" — correct. But **not** "3× in 15 years."

7. **Half-yearly beats yearly, quarterly beats half-yearly.** If an MCQ asks which gives more, the more frequent one always wins.

---

## ✍️ PRACTICE (do these — 15 min)

1. Find the SI on ₹6,000 at 5% per annum for 4 years.
2. The SI on ₹2,500 for 3 years is ₹750. Find the rate.
3. Find the CI on ₹8,000 at 10% per annum for 2 years.
4. Find the difference between CI and SI on ₹10,000 at 5% per annum for 2 years.
5. In what time will ₹8,000 amount to ₹9,200 at 5% per annum SI?
6. A sum triples itself in 12 years at simple interest. Find the rate.
7. Find the CI on ₹12,500 at 8% per annum for 2 years.
8. Find the CI on ₹5,000 at 20% per annum for 1 year, compounded half-yearly.
9. What sum will earn a simple interest of ₹900 at 6% per annum in 5 years?
10. Find the difference between CI and SI on ₹15,000 at 10% per annum for 3 years.
11. The difference between CI and SI on a certain sum at 10% for 2 years is ₹40. Find the sum.
12. A sum of money doubles itself in 6 years at compound interest. In how many years will it become 8 times?

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **₹1,200** — 6000 × 5 × 4 / 100 = 1200
2. **10%** — R = 750 × 100 / (2500 × 3) = 75000/7500 = 10%
3. **₹1,680** — Amount = 8000 × 1.21 = 9,680; CI = 1,680
4. **₹25** — 10000 × (0.05)² = 10000 × 0.0025 = 25
5. **3 years** — SI = 1,200; T = 1200 × 100 / (8000 × 5) = 3
6. **16.67%** — (3–1) × 100 / 12 = 200/12 = 16.67%
7. **₹2,080** — Amount = 12500 × (1.08)² = 12500 × 1.1664 = 14,580; CI = 2,080
8. **₹1,050** — Half-yearly: R = 10%, n = 2. Amount = 5000 × 1.21 = 6,050; CI = 1,050
9. **₹3,000** — P = 900 × 100 / (6 × 5) = 90000/30 = 3000
10. **₹465** — 15000 × 0.01 × 3.10 = 465
11. **₹4,000** — 40 = P × 0.01 → P = 4,000
12. **18 years** — Doubles in 6 → 4× in 12 → 8× in 18. (2³ = 8, so 3 × 6 years.)

</details>

---

## 🎯 QUICK RECAP — say these out loud

- **SI = PRT/100** — interest on the original principal, same every year
- **Amount = P(1 + R/100)ⁿ**, and **CI = Amount – P** (don't forget to subtract!)
- "Amounts to" means the **total** — subtract P to get the interest
- Half-yearly → **rate ÷ 2, time × 2**. Quarterly → **rate ÷ 4, time × 4**
- **CI – SI (2 yrs) = P(R/100)²** ← memorize, most-asked formula here
- **CI – SI (3 yrs) = P(R/100)²(3 + R/100)**
- SI doubles in **100/R** years, triples in **200/R** years
- CI doubling in n years → 4× in 2n, 8× in 3n
- Two amounts at two times → **divide the equations**
- **CI ≥ SI, always**

➡️ **Next:** [05-average.md](05-average.md)
