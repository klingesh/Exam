# 5️⃣ AVERAGE

⏱️ **Study time: 45 minutes** | 🎯 **Typical questions: 2–4**

> ✅ One formula runs this entire topic. The skill isn't the formula — it's **converting the average back into a SUM**. Do that and every question becomes easy.

---

## 📖 PART 1 — THE CORE IDEA

```
              Sum of all values
Average  =  ────────────────────
             Number of values


Rearranged — and this is the version you'll actually use:

Sum  =  Average × Number of values
```

> 🔑 **THE MASTER SKILL OF THIS TOPIC:** the moment you see an average, convert it to a total.
> "Average of 5 numbers is 20" → immediately write **"Sum = 100."**
> Nearly every average question is solved by comparing two sums.

### 🔍 Example 1 — Warm-up
*Find the average of 12, 18, 24, 30, 36.*
```
Step 1: Sum = 12 + 18 + 24 + 30 + 36 = 120
Step 2: Count = 5
Step 3: Average = 120 / 5 = 24
✅ 24
```

---

## 📖 PART 2 — AVERAGE OF CONSECUTIVE / EVENLY SPACED NUMBERS ⭐

For any set of numbers with an equal gap (consecutive, or all even, or all odd, or an AP):

```
                First value + Last value
Average  =  ────────────────────────────
                        2

… which is also just the MIDDLE value.
```

### 🔍 Example 2
*Find the average of the first 20 natural numbers.*
```
Step 1: They run from 1 to 20, evenly spaced.
Step 2: Average = (1 + 20)/2 = 21/2 = 10.5
✅ 10.5

(The long way — sum = 20×21/2 = 210, then 210/20 = 10.5 — gives the same answer
 but takes three times as long.)
```

### 🔍 Example 3 — Working backwards
*The average of 5 consecutive even numbers is 30. Find the largest one.*
```
Step 1: For evenly spaced numbers, the average IS the middle value.
        With 5 numbers, the average is the 3rd one → 3rd number = 30

Step 2: They're consecutive EVEN numbers, so the gap is 2.
        1st   2nd   3rd   4th   5th
         26    28    30    32    34

✅ The largest is 34
```

---

## 📖 PART 3 — WEIGHTED AVERAGE ⭐

Use this when groups have **different sizes**. You cannot just average the averages.

```
                     n₁a₁ + n₂a₂
Combined average = ───────────────
                       n₁ + n₂
```

### 🔍 Example 4
*In a class, 20 boys have an average weight of 50 kg and 30 girls have an average weight of 45 kg. Find the average weight of the whole class.*
```
Step 1: Convert each average to a SUM.
        Boys:  20 × 50 = 1,000 kg
        Girls: 30 × 45 = 1,350 kg

Step 2: Total sum = 1,000 + 1,350 = 2,350 kg
Step 3: Total people = 20 + 30 = 50
Step 4: Average = 2,350 / 50 = 47 kg

✅ 47 kg
```
> 🚨 **The trap:** the naive answer is (50 + 45)/2 = 47.5. That's wrong because there are more girls, so the average is pulled **towards 45**. Note our answer 47 is indeed below 47.5. **Sanity check every weighted average this way** — it should lean toward the bigger group.

---

## 📖 PART 4 — AVERAGE SPEED ⭐⭐ (very commonly asked)

```
                    Total distance
Average speed  =  ──────────────────
                     Total time
```

⚠️ **Average speed is NEVER the average of the two speeds** (unless the *times* are equal).

### The shortcut for EQUAL DISTANCES
```
When the same distance is covered at speed x and then at speed y:

                    2xy
Average speed  =  ───────
                   x + y
```

### 🔍 Example 5
*A man goes from A to B at 60 km/h and returns at 40 km/h. Find his average speed.*
```
Step 1: The distance each way is the same → use the 2xy/(x+y) shortcut.
Step 2: = 2 × 60 × 40 / (60 + 40)
Step 3: = 4,800 / 100
Step 4: = 48 km/h

✅ 48 km/h  — NOT 50 km/h

Why it's less than 50: he spends MORE TIME at the slower speed,
so the slow speed carries more weight.
```

### 🔍 Example 6 — Proving it the long way (do this once so you trust the formula)
*A car travels 100 km at 50 km/h and another 100 km at 25 km/h.*
```
Step 1: Time for first leg  = 100 / 50 = 2 hours
Step 2: Time for second leg = 100 / 25 = 4 hours
Step 3: Total distance = 200 km. Total time = 6 hours.
Step 4: Average speed = 200 / 6 = 33.33 km/h

Check with the shortcut: 2(50)(25)/(50+25) = 2500/75 = 33.33 ✔
```

### For THREE equal distances
```
                     3xyz
Average speed = ─────────────────
                xy + yz + zx
```

### If the TIMES are equal (not the distances)
Then it **is** the simple average: `(x + y)/2`.
> 🧠 Read the question carefully: *"travelled for 2 hours at 40 and 2 hours at 60"* → equal **times** → answer is 50. *"travelled 100 km at 40 and 100 km at 60"* → equal **distances** → use 2xy/(x+y) = 48.

---

## 📖 PART 5 — REPLACEMENT PROBLEMS ⭐⭐

*"The average changes when a person/item is replaced."* Very common. Use this:

```
Change in total  =  Number of items  ×  Change in average
```

### 🔍 Example 7
*The average weight of 8 people increases by 2.5 kg when a new person replaces one who weighed 65 kg. Find the new person's weight.*
```
Step 1: How much did the TOTAL weight go up?
        Change in total = 8 people × 2.5 kg = 20 kg

Step 2: The total went up by 20 kg purely because of the swap.
        So the new person is 20 kg heavier than the one who left.

Step 3: New person = 65 + 20 = 85 kg

✅ 85 kg
```

### 🔍 Example 8 — Adding a person (not replacing)
*The average age of 30 students is 12 years. When the teacher's age is included, the average becomes 13. Find the teacher's age.*
```
Step 1: Convert both to sums.
        Students only:      30 × 12 = 360
        Students + teacher: 31 × 13 = 403      ← note: 31 people now

Step 2: The teacher's age is the difference.
        403 – 360 = 43

✅ Teacher is 43 years old
```
> 💡 **Fast way to see it:** the teacher must (a) match the new average of 13, and (b) supply 1 extra year to each of the 30 students to lift them from 12 to 13. So `13 + 30 = 43`.

### 🔍 Example 9 — Removing a value
*The average of 5 numbers is 20. One number is removed and the average of the remaining becomes 18. Find the removed number.*
```
Step 1: Original sum   = 5 × 20 = 100
Step 2: Remaining sum  = 4 × 18 = 72
Step 3: Removed number = 100 – 72 = 28
✅ 28
```

---

## 📖 PART 6 — CORRECTION PROBLEMS

*"A number was misread."* Find the error in the **total**, then spread it over the count.

### 🔍 Example 10
*The average of 40 numbers is 18. Later it was found that one number, 25, had been wrongly read as 52. Find the correct average.*
```
Step 1: Wrong total = 40 × 18 = 720

Step 2: How wrong is it? They used 52 instead of 25.
        The total was too BIG by 52 – 25 = 27

Step 3: Correct total = 720 – 27 = 693

Step 4: Correct average = 693 / 40 = 17.325

✅ 17.325
```
> 🧠 **Direction rule:** if the value used was **too big**, subtract the difference. If **too small**, add it.

---

## 📖 PART 7 — CRICKET / INNINGS PROBLEMS ⭐

The classic "average runs" question. Use sums.

### 🔍 Example 11
*A batsman has an average of 32 runs in 10 innings. How many runs must he score in the 11th innings to raise his average to 34?*
```
Step 1: Runs so far = 10 × 32 = 320
Step 2: Runs needed after 11 innings = 11 × 34 = 374
Step 3: Required score = 374 – 320 = 54

✅ 54 runs
```
> 💡 **Shortcut:** `new average + (old innings × increase in average)` = `34 + (10 × 2)` = **54**. Same answer, one line.

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **Always convert averages into SUMS immediately.** Write `Sum = Avg × n` on your rough sheet before doing anything else.

2. **The deviation method** — great for big, ugly numbers. Pick a convenient base, average the deviations, add back.
   ```
   Average of 102, 106, 109, 113, 115?
   Take base = 110. Deviations: –8, –4, –1, +3, +5
   Sum of deviations = –5 → average deviation = –1
   Average = 110 – 1 = 109
   ```

3. **Average of first n natural numbers = (n+1)/2.** So first 50 → 25.5.

4. **Average of the first n odd numbers = n.** Average of the first n even numbers = **n + 1**.

5. **Adding a value equal to the current average doesn't change the average.**

6. **Sanity check with the range:** the average must always lie **between the smallest and largest** values. If you compute an "average age" of 71 for a group of teenagers, you've made an error.

7. **For average speed, remember it always leans toward the SLOWER speed.** So the answer must be less than the simple average. Use this to eliminate MCQ options instantly.

---

## ✍️ PRACTICE (do these — 15 min)

1. Find the average of 12, 18, 24, 30, 36.
2. Find the average of the first 20 natural numbers.
3. The average of 6 numbers is 30. Find their sum.
4. The average of 10 numbers is 15. If each number is multiplied by 2, find the new average.
5. A car travels 100 km at 50 km/h and another 100 km at 25 km/h. Find the average speed.
6. The average age of 30 students is 12 years. Including the teacher, the average becomes 13. Find the teacher's age.
7. The average of 5 consecutive even numbers is 30. Find the largest number.
8. The average weight of 8 men increases by 2.5 kg when a man weighing 65 kg is replaced by a new man. Find the new man's weight.
9. A batsman's average is 32 after 10 innings. What must he score in the 11th innings to make his average 34?
10. The average of 40 numbers is 18. One number, 25, was misread as 52. Find the correct average.
11. In a class, 20 boys average 50 kg and 30 girls average 45 kg. Find the class average.
12. The average of 5 numbers is 20. One number is removed and the average of the rest is 18. Find the removed number.
13. A man walks to his office at 5 km/h and cycles back at 20 km/h. Find his average speed.

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **24** — Sum = 120; 120/5 = 24
2. **10.5** — (1 + 20)/2 = 10.5
3. **180** — 6 × 30 = 180
4. **30** — multiplying every value by 2 doubles the average
5. **33.33 km/h** — 2(50)(25)/75 = 2500/75 = 33.33
6. **43 years** — (31 × 13) – (30 × 12) = 403 – 360 = 43
7. **34** — middle number = 30 → 26, 28, 30, 32, 34
8. **85 kg** — 65 + (8 × 2.5) = 65 + 20 = 85
9. **54 runs** — (11 × 34) – (10 × 32) = 374 – 320 = 54
10. **17.325** — 720 – 27 = 693; 693/40 = 17.325
11. **47 kg** — (1000 + 1350)/50 = 2350/50 = 47
12. **28** — 100 – 72 = 28
13. **8 km/h** — 2(5)(20)/(5+20) = 200/25 = 8

</details>

---

## 🎯 QUICK RECAP — say these out loud

- **Sum = Average × Count.** Convert to sums first, always.
- Evenly spaced numbers → average = **(first + last)/2** = the middle value
- Weighted average → **(n₁a₁ + n₂a₂)/(n₁ + n₂)**, and it leans toward the bigger group
- Average speed = **Total distance / Total time**, never the average of the speeds
- Equal distances → **2xy/(x+y)**. Equal times → **(x+y)/2**
- Replacement: **change in total = count × change in average**
- Adding one person: **new average + (old count × change in average)**
- Misread value: too big → **subtract** the error; too small → **add** it
- The average always sits **between the smallest and largest** value

➡️ **Next:** [06-problems-on-ages.md](06-problems-on-ages.md)
