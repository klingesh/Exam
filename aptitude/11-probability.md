# 1️⃣1️⃣ PROBABILITY

⏱️ **Study time: 45 minutes** | 🎯 **Typical questions: 2–3**

> ✅ Placement-level probability is **not** hard. It's coins, dice, cards and balls — four scenarios, and once you know the sample space of each, the questions answer themselves.

---

## 📖 PART 1 — THE CORE FORMULA

```
                        Number of FAVOURABLE outcomes
Probability P(E)  =  ─────────────────────────────────
                        Total number of POSSIBLE outcomes
```

### Three facts that are always true
```
0 ≤ P(E) ≤ 1            Probability can never be negative or above 1.
P(impossible) = 0       P(certain) = 1
P(E) + P(not E) = 1     →   P(not E) = 1 – P(E)
```

> 🔑 **The complement rule `P(not E) = 1 – P(E)` is your best friend.**
> Whenever a question says **"at least one"**, do NOT count all the cases. Instead compute **"none"** and subtract from 1. This one trick saves you enormous time.

---

## 📖 PART 2 — THE FOUR SAMPLE SPACES (learn these cold)

### 🪙 COINS
```
1 coin  → 2 outcomes:  H, T
2 coins → 4 outcomes:  HH, HT, TH, TT
3 coins → 8 outcomes:  HHH, HHT, HTH, THH, HTT, THT, TTH, TTT

n coins → 2ⁿ outcomes
```
⚠️ **HT and TH are DIFFERENT outcomes.** Forgetting this is the classic coin mistake.

### 🎲 DICE
```
1 die   → 6 outcomes
2 dice  → 36 outcomes  (6 × 6)
n dice  → 6ⁿ outcomes
```

**The two-dice sum table — memorize the counts:**

| Sum | 2 | 3 | 4 | 5 | 6 | **7** | 8 | 9 | 10 | 11 | 12 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **Ways** | 1 | 2 | 3 | 4 | 5 | **6** | 5 | 4 | 3 | 2 | 1 |

> 💡 **Pattern:** it climbs 1,2,3,4,5 up to **7 (the peak, with 6 ways)**, then falls back down symmetrically. Total = 36 ✔
> Sum of 7 is the most likely sum: **6/36 = 1/6**.

Also: **doublets** (1-1, 2-2, … 6-6) = **6 outcomes → 6/36 = 1/6**

### 🃏 PLAYING CARDS (a standard 52-card deck)
```
52 cards total

4 SUITS × 13 cards each:
   ♠ Spades (black)     ♣ Clubs (black)
   ♥ Hearts (red)       ♦ Diamonds (red)

26 RED  (hearts + diamonds)      26 BLACK (spades + clubs)

Each suit has: A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K

FACE CARDS (J, Q, K)  = 3 per suit × 4 = 12 cards
ACES = 4      KINGS = 4      QUEENS = 4      JACKS = 4
```
| Common event | Count | Probability |
|---|---|---|
| A specific card value (e.g. a king) | 4 | 4/52 = **1/13** |
| A specific suit (e.g. a spade) | 13 | 13/52 = **1/4** |
| A red card | 26 | **1/2** |
| A face card | 12 | 12/52 = **3/13** |
| A red king | 2 | 2/52 = **1/26** |
| An ace **or** a king | 8 | 8/52 = **2/13** |

### ⚪ BALLS IN A BAG
Total = sum of all the balls. Then it's simple counting (see Part 5 for drawing two at once).

---

## 📖 PART 3 — WORKED EXAMPLES: COINS & DICE

### 🔍 Example 1 — Two coins
*Two coins are tossed. Find the probability of getting (a) exactly one head, (b) at least one head.*
```
Step 1: Sample space = {HH, HT, TH, TT}, total 4 outcomes.

(a) EXACTLY one head → favourable = HT, TH → 2 outcomes
    P = 2/4 = 1/2

(b) AT LEAST one head → use the complement!
    "At least one head" is the opposite of "no heads at all".
    No heads = TT = 1 outcome → P(no head) = 1/4
    P(at least one head) = 1 – 1/4 = 3/4

✅ (a) 1/2   (b) 3/4
```

### 🔍 Example 2 — Three coins
*Three coins are tossed. Find P(exactly 2 heads).*
```
Step 1: Total = 2³ = 8 outcomes.
Step 2: Which have exactly 2 heads?
        HHT, HTH, THH → 3 outcomes
Step 3: P = 3/8
✅ 3/8
```

### 🔍 Example 3 — Two dice, sum condition ⭐
*Two dice are thrown. Find the probability that the sum is 9.*
```
Step 1: Total outcomes = 6 × 6 = 36

Step 2: List the pairs that add to 9. Be systematic — go up the first die.
        (3,6), (4,5), (5,4), (6,3)  →  4 outcomes
        (Note: (3,6) and (6,3) are DIFFERENT outcomes. Count both.)

Step 3: P = 4/36 = 1/9

✅ 1/9
   (Cross-check with the sum table: sum 9 → 4 ways ✔)
```

### 🔍 Example 4 — Sum greater than 10
*Two dice are thrown. Find P(sum > 10).*
```
Step 1: "Sum > 10" means sum = 11 or 12.
Step 2: From the table: sum 11 → 2 ways, sum 12 → 1 way. Total 3.
        (Namely (5,6), (6,5), (6,6).)
Step 3: P = 3/36 = 1/12
✅ 1/12
```

---

## 📖 PART 4 — THE ADDITION & MULTIPLICATION RULES

### ➕ ADDITION RULE — for "OR"
```
P(A or B) = P(A) + P(B) – P(A and B)

If A and B are MUTUALLY EXCLUSIVE (can't both happen), P(A and B) = 0, so:
P(A or B) = P(A) + P(B)
```

### 🔍 Example 5 — Overlapping events ⭐
*One card is drawn from a pack. Find the probability that it is a red card OR a king.*
```
Step 1: P(red)  = 26/52
        P(king) =  4/52

Step 2: ⚠️ Careful — these OVERLAP. There are 2 red kings, and they'd be
        counted twice if we just added.
        P(red AND king) = 2/52

Step 3: P(red or king) = 26/52 + 4/52 – 2/52 = 28/52

Step 4: Simplify → 7/13

✅ 7/13

(The naive answer 30/52 is wrong — it double-counts the two red kings.)
```

### ✖️ MULTIPLICATION RULE — for "AND"
```
P(A and B) = P(A) × P(B)          (for independent events)
```

### 🔍 Example 6 — With and without replacement ⭐⭐
*A bag has 5 red and 4 blue balls. Two balls are drawn. Find P(both red) if the draw is (a) with replacement, (b) without replacement.*
```
Total balls = 5 + 4 = 9

(a) WITH replacement (the first ball goes back in):
    First draw:  P(red) = 5/9
    Second draw: still 5 red out of 9 → 5/9
    P(both red) = 5/9 × 5/9 = 25/81

(b) WITHOUT replacement (the first ball is kept out):
    First draw:  P(red) = 5/9
    Second draw: only 4 reds left out of 8 balls → 4/8 = 1/2
    P(both red) = 5/9 × 4/8 = 20/72 = 5/18

✅ (a) 25/81   (b) 5/18
```
> 🚨 **Always check: with or without replacement?** If the question says "two balls are drawn **together**" or "**at random**" without mentioning replacement, assume **without** replacement.

---

## 📖 PART 5 — THE COMBINATION METHOD (for drawing several at once)

When you draw multiple items simultaneously, use combinations. Order doesn't matter.

```
             n!                    n × (n–1) × (n–2) × …  (r terms)
C(n, r) = ──────────    =    ──────────────────────────────────────
          r! (n–r)!                    r × (r–1) × … × 1
```

**The values you'll actually need:**
| C(n,2) | Value | | C(n,3) | Value |
|---|---|---|---|---|
| C(4,2) | 6 | | C(4,3) | 4 |
| C(5,2) | 10 | | C(5,3) | 10 |
| C(6,2) | 15 | | C(6,3) | 20 |
| C(8,2) | 28 | | C(7,3) | 35 |
| C(9,2) | 36 | | | |
| C(10,2) | 45 | | | |

> 💡 **Quick way for C(n,2):** it's just `n(n–1)/2`. So C(9,2) = 9×8/2 = 36.

### 🔍 Example 7 — One of each colour
*A bag contains 3 red and 5 blue balls. Two balls are drawn at random. Find the probability that one is red and one is blue.*
```
Step 1: Total balls = 8. Total ways to pick any 2 = C(8,2) = 8×7/2 = 28

Step 2: Favourable = (ways to pick 1 red) × (ways to pick 1 blue)
        = C(3,1) × C(5,1)
        = 3 × 5 = 15

Step 3: P = 15/28

✅ 15/28
```

### 🔍 Example 8 — Using the complement with balls ⭐
*A bag has 4 white, 5 black and 6 red balls. One ball is drawn. Find P(not red).*
```
Step 1: Total = 4 + 5 + 6 = 15

Step 2: Two ways to do this —
        Direct:     not red = 4 white + 5 black = 9 → P = 9/15 = 3/5
        Complement: P(red) = 6/15 = 2/5, so P(not red) = 1 – 2/5 = 3/5

✅ 3/5   (Both routes agree ✔)
```

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **"At least one" → ALWAYS use 1 – P(none).** This is the biggest time-saver in probability. Never enumerate.

2. **Memorize the two-dice sum table.** It appears in most dice questions and saves you from listing pairs.

3. **Memorize the card deck facts.** 4 of each value, 13 of each suit, 12 face cards, 26 red.

4. **For "OR" with overlapping events, subtract the overlap.** Red or king → subtract the red kings.

5. **C(n,2) = n(n–1)/2.** Fast and error-free.

6. **Sanity check every answer:** it must be between 0 and 1. If you get 5/4 or a negative number, you've made an error — usually you added when you should have multiplied.

7. **If the answer must be a "nice" fraction, simplify fully.** Exam options are usually in lowest terms: 4/36 will be listed as 1/9.

8. **"Together" or "simultaneously" = without replacement.**

---

## ✍️ PRACTICE (do these — 15 min)

1. A coin is tossed. Find P(head).
2. Two coins are tossed. Find P(at least one head).
3. A die is thrown. Find P(an even number).
4. A die is thrown. Find P(a prime number).
5. Two dice are thrown. Find P(sum = 8).
6. Two dice are thrown. Find P(a doublet).
7. A card is drawn from a pack of 52. Find P(a queen).
8. A card is drawn. Find P(a spade).
9. A card is drawn. Find P(a red king).
10. A bag has 5 red and 3 green balls. One is drawn. Find P(red).
11. A bag has 4 red and 6 black balls. Two are drawn together. Find P(both red).
12. Three coins are tossed. Find P(exactly 2 heads).
13. A bag has 3 red and 5 blue balls. Two are drawn. Find P(one red and one blue).
14. A card is drawn. Find P(a red card or a king).
15. A bag has 4 white, 5 black and 6 red balls. One is drawn. Find P(not red).

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **1/2**
2. **3/4** — 1 – P(no head) = 1 – 1/4
3. **1/2** — {2, 4, 6} → 3/6
4. **1/2** — primes on a die are 2, 3, 5 → 3/6. (⚠️ 1 is NOT prime.)
5. **5/36** — (2,6),(3,5),(4,4),(5,3),(6,2) → 5 ways
6. **1/6** — 6 doublets out of 36
7. **1/13** — 4/52
8. **1/4** — 13/52
9. **1/26** — 2/52
10. **5/8** — total 8 balls
11. **2/15** — C(4,2)/C(10,2) = 6/45 = 2/15
12. **3/8** — HHT, HTH, THH out of 8
13. **15/28** — (3 × 5)/C(8,2) = 15/28
14. **7/13** — 26/52 + 4/52 – 2/52 = 28/52
15. **3/5** — 9/15

</details>

---

## 🎯 QUICK RECAP — say these out loud

- **P = favourable / total**, and it always sits between 0 and 1
- **"At least one" → 1 – P(none)**. Always.
- Coins: **2ⁿ** outcomes. HT ≠ TH.
- Two dice: **36** outcomes. Sum 7 is most likely (6 ways). Doublets = 6.
- Cards: 52 total, **13 per suit**, **4 per value**, **12 face cards**, **26 red**
- "OR" → **add, then subtract the overlap**
- "AND" → **multiply**
- Without replacement → the **second denominator shrinks by 1**
- **C(n,2) = n(n–1)/2**

➡️ **Next:** [12-data-interpretation.md](12-data-interpretation.md)
