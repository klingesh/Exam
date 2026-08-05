# 9️⃣ PROBLEMS ON TRAINS

⏱️ **Study time: 30 minutes** | 🎯 **Typical questions: 2–3**

> 📌 **Prerequisite:** read [08-speed-time-distance.md](08-speed-time-distance.md) first. Trains is that topic plus **one new idea**.

---

## 📖 PART 1 — THE ONE NEW IDEA

A train is not a dot — **it has length**. So "crossing" something means the **whole train** must clear it, from the engine's nose to the guard's van.

```
Distance covered when crossing = Length of TRAIN + Length of the OBJECT
```

### The decision table — this is the whole topic

| Train crosses… | Distance covered | Why |
|---|---|---|
| a **pole / post / man / tree / signal** | **train length only** | the object has no length |
| a **platform / bridge / tunnel / station** | **train + platform** | the object has length |
| **another train** | **train 1 + train 2** | both have length |

> 🔑 **Ask yourself one question: "does the thing being crossed have a length?"**
> A pole, a man, a tree, a signal post → **no length**, use the train's length alone.
> A platform, bridge, tunnel, another train → **has length**, add it.

### And for two trains, add relative speed:

| Two trains moving… | Relative speed |
|---|---|
| **opposite** directions (crossing each other) | **s₁ + s₂** |
| **same** direction (one overtaking) | **s₁ – s₂** |

```
                      L₁ + L₂
Time to cross  =  ─────────────
                  relative speed
```

---

## 📖 PART 2 — WORKED EXAMPLES, STEP BY STEP

### 🔍 Example 1 — Crossing a pole (the simplest case)
*A train 150 m long is running at 54 km/h. How long does it take to cross a pole?*

```
Step 1: A pole has NO length. So distance = train length = 150 m.

Step 2: Convert the speed to m/s (because the distance is in metres).
        54 × 5/18 = 15 m/s

Step 3: Time = Distance / Speed = 150 / 15 = 10 seconds

✅ 10 seconds
```

### 🔍 Example 2 — Crossing a platform
*A train 200 m long, running at 72 km/h, crosses a platform 300 m long. Find the time taken.*

```
Step 1: A platform HAS length. So add both.
        Distance = 200 + 300 = 500 m

Step 2: Convert the speed.
        72 × 5/18 = 20 m/s

Step 3: Time = 500 / 20 = 25 seconds

✅ 25 seconds
```

### 🔍 Example 3 — Find the train's length
*A train running at 36 km/h crosses a pole in 9 seconds. Find its length.*
```
Step 1: Speed = 36 × 5/18 = 10 m/s
Step 2: Pole → distance = train length
Step 3: Length = Speed × Time = 10 × 9 = 90 m
✅ 90 m
```

### 🔍 Example 4 — Find the speed
*A train 150 m long crosses a platform 250 m long in 20 seconds. Find its speed in km/h.*
```
Step 1: Distance = 150 + 250 = 400 m
Step 2: Speed = 400 / 20 = 20 m/s
Step 3: Convert to km/h → 20 × 18/5 = 72 km/h
✅ 72 km/h
```

### 🔍 Example 5 — Two trains, OPPOSITE directions ⭐
*Two trains, 120 m and 180 m long, are running in opposite directions at 42 km/h and 30 km/h. How long do they take to cross each other?*

```
Step 1: Both trains have length → distance = 120 + 180 = 300 m

Step 2: Opposite directions → ADD the speeds.
        Relative speed = 42 + 30 = 72 km/h

Step 3: Convert. 72 × 5/18 = 20 m/s

Step 4: Time = 300 / 20 = 15 seconds

✅ 15 seconds
```

### 🔍 Example 6 — Two trains, SAME direction ⭐
*Same two trains (120 m and 180 m, at 42 km/h and 30 km/h) now running in the SAME direction. How long to cross each other?*

```
Step 1: Distance is unchanged = 300 m

Step 2: Same direction → SUBTRACT the speeds.
        Relative speed = 42 – 30 = 12 km/h

Step 3: Convert. 12 × 5/18 = 60/18 = 10/3 m/s

Step 4: Time = 300 ÷ (10/3) = 300 × 3/10 = 90 seconds

✅ 90 seconds
```
> 🚨 **Look at the difference: 15 seconds vs 90 seconds** with identical trains and speeds. Same direction takes **six times** as long, because the gap closes so slowly. This contrast is a favourite exam trap — always check the direction.

### 🔍 Example 7 — Train crossing a moving man ⭐
*A train 150 m long, running at 63 km/h, overtakes a man walking at 3 km/h in the same direction. How long does it take to pass him?*

```
Step 1: A man has NO length → distance = 150 m only.

Step 2: Same direction → subtract.
        Relative speed = 63 – 3 = 60 km/h

Step 3: Convert. 60 × 5/18 = 300/18 = 50/3 m/s

Step 4: Time = 150 ÷ (50/3) = 150 × 3/50 = 9 seconds

✅ 9 seconds
```

### 🔍 Example 8 — The "pole AND platform" pattern ⭐⭐
*A train crosses a platform 200 m long in 24 seconds and crosses a pole in 12 seconds. Find the length of the train and its speed.*

```
Step 1: Let the train's length = L metres. The speed is the same in both cases,
        so write the speed twice and equate.

Step 2: Crossing the pole:      speed = L / 12
        Crossing the platform:  speed = (L + 200) / 24

Step 3: Equate them.
              L         L + 200
             ────  =  ───────────
              12          24

Step 4: Cross-multiply.
        24L = 12(L + 200)
        24L = 12L + 2400
        12L = 2400
        L = 200 m

Step 5: Speed = L/12 = 200/12 = 16.67 m/s
        In km/h: 16.67 × 18/5 = 60 km/h

✅ Length = 200 m, Speed = 60 km/h

VERIFY: Pole → 200/16.67 = 12 s ✔   Platform → 400/16.67 = 24 s ✔
```
> 🔑 **The trick:** the platform took 12 extra seconds (24 – 12), and in those 12 seconds the train covered exactly the platform's 200 m.
> So **speed = 200/12 = 16.67 m/s** immediately, and then length = 16.67 × 12 = 200 m. One line.

---

## 📖 PART 3 — TWO USEFUL RATIO RESULTS

### ① Two trains cross a pole in t₁ and t₂ seconds, and cross each other (opposite direction) in t seconds
```
        2 t₁ t₂
t  =  ───────────      (only when both trains are the same length)
       t₁ + t₂
```

### ② Two trains start towards each other from A and B at the same time, cross, then take a and b hours to reach their destinations
```
Speed of A       √b
──────────  =  ─────
Speed of B       √a
```
*(Low priority — know it exists, skip if short on time.)*

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **Write down these two lines before solving anything:**
   ```
   Distance = train + (object's length, if it has one)
   Speed    = add if opposite, subtract if same direction
   ```
   Get those two right and the arithmetic is trivial.

2. **Convert km/h → m/s immediately** (× 5/18). Metres and seconds are the natural units here.

3. **Memorize:** 36 km/h = 10 m/s, 54 = 15, 72 = 20, 90 = 25. These appear constantly.

4. **"Platform time – pole time" gives you the platform crossing directly.**
   `Speed = platform length / (t_platform – t_pole)`. This solves Example 8 in one step.

5. **Pole, man, tree, signal, post = zero length.** Platform, bridge, tunnel, train = has length. Circle the object in the question.

6. **Sanity check:** same-direction crossings always take **much longer** than opposite-direction ones. If you get the same-direction answer smaller, you added instead of subtracting.

7. **If a train "just misses"/"overtakes" someone walking, the man's length is still zero** — only the relative speed changes.

---

## ✍️ PRACTICE (do these — 12 min)

1. A train 180 m long runs at 54 km/h. How long to cross a pole?
2. A train 240 m long runs at 72 km/h and crosses a platform 360 m long. Find the time.
3. A train crosses a pole in 9 seconds at 36 km/h. Find its length.
4. A train 150 m long crosses a 250 m platform in 20 seconds. Find its speed in km/h.
5. Two trains, 100 m and 150 m long, run in opposite directions at 45 km/h and 36 km/h. Find the time to cross each other.
6. The same two trains now run in the same direction. Find the time to cross each other.
7. A train 120 m long, running at 45 km/h, passes a man running at 9 km/h in the opposite direction. Find the time taken.
8. A train crosses a platform 200 m long in 24 seconds and a pole in 12 seconds. Find the train's length.
9. A train 200 m long, running at 63 km/h, overtakes a man walking at 3 km/h in the same direction. Find the time taken.
10. A train 300 m long crosses a bridge in 30 seconds at a speed of 54 km/h. Find the length of the bridge.

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

1. **12 seconds** — 54 km/h = 15 m/s; 180/15 = 12
2. **30 seconds** — Distance = 600 m; 72 km/h = 20 m/s; 600/20 = 30
3. **90 m** — 36 km/h = 10 m/s; 10 × 9 = 90
4. **72 km/h** — 400 m / 20 s = 20 m/s → 20 × 18/5 = 72
5. **11.11 seconds** — Distance 250 m; relative 81 km/h = 22.5 m/s; 250/22.5 = 11.11 s
6. **100 seconds** — relative 9 km/h = 2.5 m/s; 250/2.5 = 100 s
7. **8 seconds** — man has no length → 120 m; opposite → 45 + 9 = 54 km/h = 15 m/s; 120/15 = 8
8. **200 m** — Speed = 200/(24–12) = 16.67 m/s; length = 16.67 × 12 = 200 m
9. **12 seconds** — relative 60 km/h = 50/3 m/s; 200 ÷ (50/3) = 12 s
10. **150 m** — 54 km/h = 15 m/s; total distance = 15 × 30 = 450 m; bridge = 450 – 300 = 150 m

</details>

---

## 🎯 QUICK RECAP — say these out loud

- Crossing a **pole / man / tree / post** → distance = **train length only**
- Crossing a **platform / bridge / tunnel / train** → **add both lengths**
- **Opposite** direction → **add** speeds. **Same** direction → **subtract** speeds.
- Always convert km/h → m/s using **× 5/18**
- Speed = **platform length ÷ (platform time – pole time)**
- Same-direction crossings take **far longer** than opposite-direction ones

➡️ **Next:** [10-boats-and-streams.md](10-boats-and-streams.md) — the easiest topic in the syllabus.
