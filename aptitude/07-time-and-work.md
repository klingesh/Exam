# 7️⃣ TIME & WORK (+ PIPES AND CISTERNS) ⭐⭐

⏱️ **Study time: 45 minutes** | 🎯 **Typical questions: 3–4**

> 🔥 **This is one of the highest-scoring topics** in placement papers, and the **LCM method** below turns it from "fractions everywhere" into simple whole-number arithmetic. Learn that one trick and this topic becomes free marks.

---

## 📖 PART 1 — THE CORE IDEA

```
If a person completes a job in n days,  then in 1 day he does  1/n  of the job.

That "1/n" is called his RATE or ONE DAY'S WORK.
```

**Everything in this topic is: add the rates, then flip.**

```
                                   1       1
Together, A and B do per day:     ─── +  ───
                                   a       b

                                        1              a × b
Time taken together  =  ────────────────────────  =  ─────────
                          (1/a) + (1/b)               a + b
```

### 🔍 Example 1 — The basic case
*A can do a piece of work in 10 days and B can do it in 15 days. How long will they take working together?*

**Method 1 — fractions (the textbook way):**
```
Step 1: A's 1 day work = 1/10
Step 2: B's 1 day work = 1/15
Step 3: Together = 1/10 + 1/15
        LCM of 10 and 15 is 30 → 3/30 + 2/30 = 5/30 = 1/6
Step 4: If they do 1/6 per day, they finish in 6 days.
✅ 6 days
```

**Method 2 — the shortcut formula:**
```
ab/(a+b) = (10 × 15)/(10 + 15) = 150/25 = 6 days
```
> ⚠️ The `ab/(a+b)` shortcut works for **exactly two** people. For three or more, use the LCM method below.

---

## 📖 PART 2 — THE LCM METHOD ⭐⭐⭐ (learn this — it's the best trick in the topic)

Instead of fractions, **assume the total work = LCM of the given days.** Then everyone's rate becomes a whole number.

### 🔍 Example 2 — Three people, no fractions
*A can do a job in 20 days, B in 30 days, and C in 60 days. How long together?*

```
Step 1: Total work = LCM(20, 30, 60) = 60 units
        (Just pretend the job is "60 bricks".)

Step 2: Convert each person's speed into units per day.
        A: 60 units ÷ 20 days = 3 units/day
        B: 60 units ÷ 30 days = 2 units/day
        C: 60 units ÷ 60 days = 1 unit/day

Step 3: Together per day = 3 + 2 + 1 = 6 units/day

Step 4: Time = Total work / Combined rate = 60 / 6 = 10 days

✅ 10 days
```
> 🎯 **Notice: not a single fraction appeared.** This is why the LCM method is worth memorising. Set it up as a small table on your rough sheet:
> ```
> Total work = 60 units
> A → 3/day      B → 2/day      C → 1/day
> ```

### 🔍 Example 3 — Finding one person's time from the total
*A and B together can complete a work in 8 days. A alone can do it in 12 days. In how many days can B alone do it?*

```
Step 1: Total work = LCM(8, 12) = 24 units

Step 2: (A + B) together = 24/8 = 3 units/day
        A alone          = 24/12 = 2 units/day

Step 3: B alone = (A+B) – A = 3 – 2 = 1 unit/day

Step 4: B's time = 24 units / 1 unit per day = 24 days

✅ 24 days
```
> 🧠 **The pattern:** to find B, **subtract A's rate from the combined rate.** Never subtract the *days* — `8 – 12` is meaningless. Rates subtract; days don't.

---

## 📖 PART 3 — EFFICIENCY ⭐

**Efficiency and time are inversely proportional.** More efficient → fewer days.

```
If A is twice as efficient as B, then A takes HALF the time B takes.

Efficiency ratio  a : b   →   Time ratio  b : a      (just flip it)
```

### 🔍 Example 4
*A is twice as efficient as B. Together they finish a work in 12 days. How long would each take alone?*

```
Step 1: Let B's rate = 1 unit/day. Then A's rate = 2 units/day (twice as efficient).

Step 2: Together = 1 + 2 = 3 units/day

Step 3: They take 12 days together, so the total work is:
        Total = rate × time = 3 × 12 = 36 units

Step 4: A alone = 36 / 2 = 18 days
        B alone = 36 / 1 = 36 days

✅ A = 18 days, B = 36 days

VERIFY: 1/18 + 1/36 = 2/36 + 1/36 = 3/36 = 1/12 ✔
```

---

## 📖 PART 4 — MEN, DAYS, HOURS (the work-equivalence formula)

```
M₁ × D₁ × H₁       M₂ × D₂ × H₂
─────────────  =  ─────────────
      W₁                W₂

M = men,  D = days,  H = hours per day,  W = amount of work
```
Drop whichever letters aren't in the question.

### 🔍 Example 5
*If 12 men can complete a work in 18 days, how many days will 27 men take?*
```
Step 1: Same work, no hours mentioned → use M₁D₁ = M₂D₂
Step 2: 12 × 18 = 27 × D₂
Step 3: 216 = 27 × D₂
Step 4: D₂ = 216 / 27 = 8

✅ 8 days
```
> 💡 **Sanity check with logic:** more men → fewer days. We went from 12 to 27 men (more), and 18 to 8 days (fewer). ✔ If your answer moves the wrong way, you've flipped the equation.

### 🔍 Example 6 — Men and women together
*6 men or 10 women can complete a work in 20 days. How long will 4 men and 5 women take?*
```
Step 1: Establish the exchange rate between men and women.
        6 men = 10 women     →     1 man = 10/6 = 5/3 women

Step 2: Convert the new group entirely into women.
        4 men = 4 × 5/3 = 20/3 women
        Plus 5 women
        Total = 20/3 + 5 = 20/3 + 15/3 = 35/3 women

Step 3: Find the total work in "woman-days".
        10 women × 20 days = 200 woman-days

Step 4: Time = 200 / (35/3) = 200 × 3/35 = 600/35 = 17.14 days

✅ About 17.14 days (120/7 days)
```

---

## 📖 PART 5 — SOMEONE LEAVES PARTWAY ⭐⭐ (very common)

**Method: figure out how much work got done, then how much is left.**

### 🔍 Example 7
*A can do a work in 20 days and B in 30 days. They start together, but A leaves after 5 days. How long will B take to finish the remaining work?*

```
Step 1: Total work = LCM(20, 30) = 60 units
        A = 60/20 = 3 units/day
        B = 60/30 = 2 units/day

Step 2: For the first 5 days, BOTH work.
        Combined rate = 3 + 2 = 5 units/day
        Work done = 5 units/day × 5 days = 25 units

Step 3: Remaining work = 60 – 25 = 35 units

Step 4: Only B works now, at 2 units/day.
        Time = 35 / 2 = 17.5 days

✅ B needs 17.5 more days   (total project time = 5 + 17.5 = 22.5 days)
```

### 🔍 Example 8 — Reverse version
*A can do a work in 15 days. He works for 5 days and then B finishes the remaining work in 8 days. How long would B alone take for the whole work?*

```
Step 1: Work A completed = 5 days out of his 15-day job = 5/15 = 1/3 of the work

Step 2: Remaining work = 1 – 1/3 = 2/3

Step 3: B did 2/3 of the work in 8 days.
        So for the FULL work (3/3), B needs:
        8 × (3/2) = 12 days

✅ B alone would take 12 days
```

---

## 📖 PART 6 — PIPES AND CISTERNS ⭐

**Exactly the same topic with new words.** One rule only:

```
Inlet pipe (fills)  →  rate is POSITIVE  (+)
Outlet pipe / leak (empties)  →  rate is NEGATIVE  (–)
```

### 🔍 Example 9 — Two fill, one empties
*Pipe A can fill a tank in 12 hours, pipe B in 15 hours, and pipe C can empty it in 20 hours. If all three are opened together, how long to fill the tank?*

```
Step 1: Total capacity = LCM(12, 15, 20) = 60 units

Step 2: A = 60/12 = +5 units/hour       (fills)
        B = 60/15 = +4 units/hour       (fills)
        C = 60/20 = –3 units/hour       (EMPTIES → negative)

Step 3: Net rate = 5 + 4 – 3 = +6 units/hour

Step 4: Time = 60 / 6 = 10 hours

✅ 10 hours

(Net rate is positive, so the tank does fill. If it had been negative,
 the tank would never fill — a classic trick question.)
```

### 🔍 Example 10 — The leak problem
*A tank can be filled in 10 hours, but due to a leak it takes longer. The leak alone can empty the full tank in 15 hours. How long does it take to fill with the leak present?*
```
Step 1: Total = LCM(10, 15) = 30 units
Step 2: Fill pipe = 30/10 = +3 units/hour
        Leak      = 30/15 = –2 units/hour
Step 3: Net = 3 – 2 = +1 unit/hour
Step 4: Time = 30/1 = 30 hours
✅ 30 hours
```

### 🔍 Example 11 — Pipe closed partway
*Pipe A fills a tank in 6 hours and pipe B in 8 hours. Both are opened, but A is closed after 2 hours. Find the total time to fill the tank.*
```
Step 1: Total = LCM(6, 8) = 24 units
        A = 24/6 = 4 units/hour
        B = 24/8 = 3 units/hour

Step 2: First 2 hours, both open → (4 + 3) × 2 = 14 units filled

Step 3: Remaining = 24 – 14 = 10 units

Step 4: Only B now, at 3 units/hour → 10/3 = 3.33 hours

Step 5: Total time = 2 + 3.33 = 5.33 hours (5 hours 20 minutes)

✅ 5 hours 20 minutes
```

---

## 📖 PART 7 — THE "PAIRS" PATTERN ⭐

*A and B together can do a work in 12 days, B and C in 15 days, and A and C in 20 days. How long will all three take together?*

```
Step 1: Write the three rates.
        A + B = 1/12
        B + C = 1/15
        A + C = 1/20

Step 2: ADD all three equations.
        (A+B) + (B+C) + (A+C) = 1/12 + 1/15 + 1/20
        2A + 2B + 2C = ...

        Notice the left side is 2(A + B + C).

Step 3: Compute the right side. LCM of 12, 15, 20 is 60.
        1/12 = 5/60,  1/15 = 4/60,  1/20 = 3/60
        Sum = 12/60 = 1/5

Step 4: So 2(A + B + C) = 1/5
        A + B + C = 1/10

Step 5: All three together take 10 days.

✅ 10 days
```
> 🔑 **The trick:** when you're given all three PAIRS, **add them and divide by 2.** Recognise this instantly — it's a guaranteed mark.

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **ALWAYS use the LCM method.** Total work = LCM of all given days. It eliminates every fraction. This is the single most valuable habit in this topic.

2. **Two people only:** `Time = ab/(a+b)`. Memorize it.

3. **Rates add and subtract. Days never do.** If you find yourself computing `20 – 30 = –10 days`, stop — you needed to work with rates.

4. **All three pairs given → add and halve.**

5. **Efficiency ratio flips to become the time ratio.** 3:2 efficiency → 2:3 time.

6. **Percentage efficiency version:** "A is 25% more efficient than B" → A's rate : B's rate = 125 : 100 = 5 : 4 → so A's time : B's time = **4 : 5**.

7. **Sanity check:** the combined time must always be **LESS than the fastest individual time.** If A alone takes 10 days and you calculate "together = 12 days", you've made an error.

8. **Work done in fraction form:** if someone works d days out of a job that takes n days, they've done **d/n** of the work.

---

## ✍️ PRACTICE (do these — 15 min)

1. A can do a work in 12 days and B in 18 days. How long together?
2. A and B together take 10 days. A alone takes 15 days. How long does B alone take?
3. A, B and C can do a work in 20, 30 and 60 days respectively. How long together?
4. If 15 men complete a work in 20 days, how many days will 20 men take?
5. A is twice as efficient as B. Together they take 14 days. How long does B alone take?
6. Pipe A fills a tank in 6 hours, pipe B in 8 hours. Both are opened but A is closed after 2 hours. Find the total time to fill the tank.
7. A tank fills in 10 hours. A leak can empty the full tank in 15 hours. How long to fill with the leak open?
8. A can do a work in 15 days. He works 5 days, then B finishes the rest in 8 days. How long would B alone take?
9. 6 men or 10 women can do a work in 20 days. How long will 4 men and 5 women take?
10. A and B together can do a work in 12 days, B and C in 15 days, A and C in 20 days. How long will all three take?
11. A can do a work in 20 days, B in 30 days. They start together and A leaves after 5 days. How many more days does B need?
12. A is 25% more efficient than B. If B takes 25 days, how long does A take?

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **7.2 days (36/5)** — LCM = 36; A = 3, B = 2, total 5/day → 36/5 = 7.2
2. **30 days** — LCM = 30; (A+B) = 3, A = 2, so B = 1 → 30/1 = 30
3. **10 days** — LCM = 60; 3 + 2 + 1 = 6/day → 60/6 = 10
4. **15 days** — 15 × 20 = 20 × D → D = 300/20 = 15
5. **42 days** — B = 1, A = 2, total 3/day; work = 3 × 14 = 42 units → B = 42/1 = 42 days
6. **5 hours 20 minutes** — LCM = 24; 2 hrs × 7 = 14 units; remaining 10 at 3/hr = 3.33 hrs; total 5.33 hrs
7. **30 hours** — LCM = 30; +3 – 2 = +1/hr → 30 hours
8. **12 days** — A did 5/15 = 1/3; B did 2/3 in 8 days → full work = 8 × 3/2 = 12 days
9. **17.14 days (120/7)** — 1 man = 5/3 women; group = 35/3 women; work = 200 woman-days → 200 ÷ (35/3) = 600/35 = 17.14
10. **10 days** — sum of pairs = 1/5 = 2(A+B+C) → A+B+C = 1/10 → 10 days
11. **17.5 days** — LCM = 60; 5 days × 5 units = 25 done; 35 left at 2/day = 17.5 days
12. **20 days** — efficiency 125:100 = 5:4, so time ratio = 4:5. If B = 25, A = 25 × 4/5 = 20 days

</details>

---

## 🎯 QUICK RECAP — say these out loud

- 1 day's work = **1/n**. Add the rates, then flip to get the time.
- **LCM METHOD:** total work = LCM of the days → all rates become whole numbers. **Use it always.**
- Two people: **Time = ab/(a+b)**
- To find one person: **subtract rates**, never days
- Efficiency ratio a:b → **time ratio b:a** (flip it)
- **M₁D₁H₁/W₁ = M₂D₂H₂/W₂**
- Pipes: fill = **+**, empty = **–**. Net rate positive → it fills.
- All three pairs given → **add them and divide by 2**
- Combined time is **always less than the fastest person's time**

➡️ **Next:** [08-speed-time-distance.md](08-speed-time-distance.md)
