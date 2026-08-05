# 1️⃣7️⃣ SEATING ARRANGEMENT

⏱️ **Study time: 30 minutes** | 🎯 **Typical questions: 3–5 (usually one puzzle with 3–5 questions attached)**

> ⚖️ **The honest assessment:** seating puzzles take **4–6 minutes** to crack, but one puzzle usually carries **3–5 marks**. That's good value — but only if you solve it. So: **do the rest of the paper first, then come back to this.** Never start the exam with a seating puzzle.
>
> 🖊️ **You cannot do these in your head. You must draw.**

---

## 📖 PART 1 — THE DIRECTION RULES ⭐⭐ (get these wrong and everything collapses)

### 🔵 LINEAR ARRANGEMENT (a row)

```
Draw the row left-to-right, always. Then:

FACING NORTH  →  the person's LEFT is your LEFT,  RIGHT is your RIGHT   (matches you)
FACING SOUTH  →  the person's LEFT is your RIGHT, RIGHT is your LEFT    (REVERSED)
```

```
FACING NORTH (towards you, out of the page):
   ┌─────┬─────┬─────┬─────┐
   │  A  │  B  │  C  │  D  │      B's left  = A     B's right = C
   └─────┴─────┴─────┴─────┘      (same as how you read it)
      ↑     ↑     ↑     ↑
     all facing North


FACING SOUTH (away from you, into the page):
   ┌─────┬─────┬─────┬─────┐
   │  A  │  B  │  C  │  D  │      B's left  = C     B's right = A
   └─────┴─────┴─────┴─────┘      (EVERYTHING FLIPS)
      ↓     ↓     ↓     ↓
     all facing South
```

> 🚨 **Test it on yourself:** stand facing a wall (North). Your right hand is on the right side of your view. Now turn around (South). Your right hand is now on what *was* the left side. **That's the whole rule.**

### 🔴 CIRCULAR ARRANGEMENT

```
FACING THE CENTRE (inward):
      clockwise      =  towards their LEFT
      anticlockwise  =  towards their RIGHT

FACING OUTSIDE (outward):
      clockwise      =  towards their RIGHT
      anticlockwise  =  towards their LEFT
```

> 💡 **How to remember without memorizing:** picture yourself sitting at the **top** of the circle facing the centre — you're facing *downwards*, i.e. South. Facing South, your right hand points **West**, which from the top of a circle is the **anticlockwise** direction. Done. Re-derive it in 5 seconds any time you need it.

### 📐 "Opposite" in a circle
```
In a circle of n people (facing centre), the person opposite position p is at:

    p + n/2      (wrapping around)

So with 8 people: 1↔5, 2↔6, 3↔7, 4↔8
   With 6 people: 1↔4, 2↔5, 3↔6
```

---

## 📖 PART 2 — THE VOCABULARY

| Phrase | What it means |
|---|---|
| **immediate left / right** | directly next to, adjacent |
| **"third to the left of X"** | count 3 positions in X's left direction |
| **"between A and B"** | strictly in between, in any order |
| **"exactly between A and B"** | at the midpoint, equal gaps on both sides |
| **"extreme ends"** | the 1st and last positions of a row |
| **"A and B are neighbours"** | they're adjacent (either side) |
| **"second from the end"** | position 2, or position n–1 |

### 🔑 The 3-part strategy for any puzzle
```
STEP 1: Draw the empty frame — boxes for a row, a circle with n slots.
        Number the positions.

STEP 2: Find the "ANCHOR" clue — the ONE clue that fixes a definite position.
        Best anchors:  "X sits at an extreme end"
                       "X sits third from the left"
                       "X sits opposite Y"
        Place that first. NEVER start with a vague clue.

STEP 3: Add clues in order of how much they RESTRICT things.
        Use pencil. If a clue creates two possibilities, draw BOTH cases
        and eliminate one later.
```

---

## 📖 PART 3 — WORKED LINEAR PUZZLE ⭐⭐ (follow every step)

**Puzzle:** Six friends **A, B, C, D, E, F** sit in a row facing **North**.
1. C sits third to the left of E.
2. B sits at one of the extreme ends.
3. D sits second to the right of B.
4. A is an immediate neighbour of E.
5. F is not at an extreme end.

```
Step 1: Draw the frame. Facing North, so left/right match our reading direction.

        ┌───┬───┬───┬───┬───┬───┐
        │ 1 │ 2 │ 3 │ 4 │ 5 │ 6 │
        └───┴───┴───┴───┴───┴───┘
        (position 1 = leftmost)

Step 2: Find the anchor. Clue 2 says B is at an extreme end → B is at 1 or 6.
        Combine with clue 3: D is second to the RIGHT of B, so D = B + 2.

        If B = 6, then D = 8 → doesn't exist. IMPOSSIBLE.
        Therefore B = 1 and D = 3.       ← anchor locked in ✔

        ┌───┬───┬───┬───┬───┬───┐
        │ B │   │ D │   │   │   │
        └───┴───┴───┴───┴───┴───┘

Step 3: Apply clue 1. C is third to the LEFT of E, so C = E – 3.
        Possible (E, C) pairs: (4,1), (5,2), (6,3)

        (4,1) → C would be at 1, but B is there. ✘
        (6,3) → C would be at 3, but D is there. ✘
        (5,2) → E = 5, C = 2. Both free. ✔

        ┌───┬───┬───┬───┬───┬───┐
        │ B │ C │ D │   │ E │   │
        └───┴───┴───┴───┴───┴───┘

Step 4: Positions 4 and 6 are left, for A and F.

        Clue 4: A is an immediate neighbour of E (position 5).
                Neighbours of 5 are 4 and 6. Both are available, so no help yet.

        Clue 5: F is NOT at an extreme end. Position 6 IS an extreme end.
                So F ≠ 6  →  F = 4, and therefore A = 6.

        Check clue 4: is A (6) a neighbour of E (5)? YES ✔

Step 5: FINAL ARRANGEMENT

        ┌───┬───┬───┬───┬───┬───┐
        │ B │ C │ D │ F │ E │ A │
        └───┴───┴───┴───┴───┴───┘
          1   2   3   4   5   6
                (all facing North)

Step 6: VERIFY every clue against the final layout.
        1. C(2) third to the left of E(5)?  5 – 3 = 2 ✔
        2. B at an extreme end? Position 1 ✔
        3. D(3) second to the right of B(1)? 1 + 2 = 3 ✔
        4. A(6) immediate neighbour of E(5)? ✔
        5. F(4) not at an extreme end? ✔
        ALL CLUES SATISFIED ✔
```

### Now answer the attached questions (this is the payoff — 5 marks in 60 seconds)
| Question | Answer |
|---|---|
| Who sits at the extreme right end? | **A** |
| Who sits between D and E? | **F** |
| How many people sit between C and E? | **2** (D and F) |
| Who is second to the left of E? | **D** |
| Who is immediately to the right of C? | **D** |

---

## 📖 PART 4 — WORKED CIRCULAR PUZZLE ⭐⭐

**Puzzle:** Six friends **A, B, C, D, E, F** sit around a circular table **facing the centre**.
1. A sits third to the left of B.
2. C sits second to the right of A.
3. D is an immediate neighbour of B.
4. E sits immediately to the right of A.

```
Step 1: Draw a circle with 6 numbered slots. I'll number them CLOCKWISE.

                    1
              6           2
              5           3
                    4
        (everyone faces the centre)

        REMEMBER: facing centre →  LEFT = clockwise,  RIGHT = anticlockwise

Step 2: Anchor. Place B at position 1 (in a circle you can always fix
        one person arbitrarily — only the relative order matters).

Step 3: Clue 1 — A is third to the LEFT of B.
        Left = clockwise. From B(1), count 3 clockwise: 2, 3, 4.
        → A = 4

                    B(1)
              6            2
              5            3
                    A(4)

Step 4: Clue 2 — C is second to the RIGHT of A.
        Right = anticlockwise. From A(4), count 2 anticlockwise: 3, 2.
        → C = 2

Step 5: Clue 3 — D is an immediate neighbour of B(1).
        Neighbours of 1 are 2 and 6. Position 2 is taken by C.
        → D = 6

Step 6: Clue 4 — E is immediately to the RIGHT of A(4).
        Right = anticlockwise. One step anticlockwise from 4 is 3.
        → E = 3

Step 7: Only position 5 is left → F = 5

Step 8: FINAL ARRANGEMENT (clockwise from position 1)

                    B(1)
             D(6)          C(2)
             F(5)          E(3)
                    A(4)

        Clockwise order:  B → C → E → A → F → D → (back to B)

Step 9: VERIFY.
        1. A(4) third to the left of B(1)? Clockwise 1→2→3→4 = 3 steps ✔
        2. C(2) second to the right of A(4)? Anticlockwise 4→3→2 = 2 steps ✔
        3. D(6) an immediate neighbour of B(1)? Yes, adjacent ✔
        4. E(3) immediately right of A(4)? Anticlockwise one step ✔
        ALL CLUES SATISFIED ✔
```

### Attached questions
| Question | Answer | Why |
|---|---|---|
| Who sits opposite A? | **B** | 6 people, so 4 ↔ 1 |
| Who is immediately to the left of C? | **E** | left = clockwise; from 2 → 3 = E |
| Who is third to the right of D? | **E** | right = anticlockwise from 6 → 5, 4, 3 = E |
| How many people sit between C and A going clockwise? | **1** (E) | from 2 clockwise: 3, then 4 |

---

## ⚡ SHORTCUTS & SPEED TRICKS

1. **DRAW THE FRAME FIRST**, with numbered positions. Every time.

2. **Start with the most RESTRICTIVE clue**, not clue #1. Look for "extreme end", "third from the left", "opposite". Vague clues like "X is a neighbour of Y" go last.

3. **Write the direction rule at the top of your working** before you place anyone:
   ```
   Facing centre: LEFT = clockwise, RIGHT = anticlockwise
   Facing North:  left/right = as I read it
   Facing South:  left/right = REVERSED
   ```

4. **In a circle, fix one person at a chosen position.** Circular arrangements have no absolute positions, only relative ones — so anchoring is free.

5. **When a clue gives two possibilities, draw BOTH cases side by side.** Don't guess. A later clue will kill one of them. This is the standard technique for harder puzzles.

6. **VERIFY every clue at the end.** It takes 30 seconds and protects all 4–5 marks. If you got one placement wrong, every attached question is wrong too — so verification here is the highest-value 30 seconds in the whole paper.

7. **Answer ALL the attached questions once you've solved it.** The hard work is the arrangement; the questions are then nearly free. This is why the topic is worth doing.

8. **Time-box it.** If you're 5 minutes in with no progress, abandon it and come back only if there's time left. Don't let one puzzle eat 15 minutes.

9. **Count carefully for "third to the left".** "Third to the left of B" means you land on the 3rd seat, counting B's immediate left as the 1st. Do not count B itself.

---

## ✍️ PRACTICE

**Puzzle:** Five friends **P, Q, R, S, T** sit in a row facing **North**.
1. P sits at the extreme left end.
2. T sits at the extreme right end.
3. R sits second to the right of P.
4. S is an immediate neighbour of R.

**Questions:**
1. Draw and complete the arrangement.
2. Who sits in the middle?
3. Who sits between Q and S?
4. Who is immediately to the left of T?
5. Who is second to the left of T?

---

### ✅ ANSWERS

<details>
<summary>Click to reveal</summary>

**Solving it:**
```
Positions 1–5, facing North.

Clue 1: P = 1
Clue 2: T = 5
Clue 3: R is second to the right of P(1) → R = 3
Clue 4: S is an immediate neighbour of R(3) → S = 2 or S = 4
        Positions still free: 2 and 4 (for Q and S).
        Either works for clue 4, so we need to look again...

        Both 2 and 4 are neighbours of 3, so S could be either.
        BUT there are only two people left (Q and S) and two seats (2 and 4),
        and no clue restricts Q. So we check: does the puzzle have a unique answer?

        Clue 4 is satisfied whether S = 2 or S = 4. The puzzle as stated
        has TWO valid arrangements:
            P Q R S T    or    P S R Q T

        ⚠️ This is deliberate — it teaches you to CHECK FOR UNIQUENESS.
        In a real exam, there would be a fifth clue (e.g. "Q is not adjacent to T")
        which would force S = 4 and give:  P Q R S T
```

**Taking the intended arrangement `P Q R S T`:**

1. **P Q R S T** (positions 1–5)
2. **R** — position 3 is the middle
3. **R** — Q is at 2, S is at 4, so R (3) is between them
4. **S** — position 4 is immediately left of T(5)
5. **R** — two positions left of T(5) is position 3

> 🧠 **The real lesson here:** if you finish a puzzle and find **more than one** valid arrangement, you've either misread a clue or skipped one. Go back and re-read. A well-set puzzle always has exactly one solution.

</details>

---

## 🎯 QUICK RECAP — say these out loud

- **DRAW the frame with numbered positions.** Never work in your head.
- Linear, facing **North** → left/right match how you read. Facing **South** → **reversed**.
- Circular, facing **centre** → **left = clockwise, right = anticlockwise**. Facing outward → flipped.
- Circle of n: opposite of p is **p + n/2**
- **Start with the most restrictive clue** (extreme end, fixed position, opposite)
- In a circle, **anchor one person anywhere** — only relative order matters
- Two possibilities → **draw both cases**, eliminate later
- **VERIFY all clues at the end** — protects 4–5 marks at once
- **Do this topic LAST** in the exam, and time-box it to 5 minutes

➡️ **Next:** [18-english-grammar.md](18-english-grammar.md)
