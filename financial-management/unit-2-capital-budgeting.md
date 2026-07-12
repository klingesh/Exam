# Financial Management — Unit II: Capital Budgeting

Investment Decisions & Criteria, Methods: Payback, ARR, NPV, IRR, PI.

---

## 1. What is Capital Budgeting?

**Capital Budgeting** is the process of **planning and evaluating long-term investment decisions** — deciding which big projects (new machine, factory, product line) are worth the money.

**Why it's crucial:**
- Involves **large amounts** of money.
- Effects are **long-term** and **irreversible** (hard to undo).
- Affects the firm's **future growth & risk**.
- Wrong decisions can **sink the company**.

### Types of Investment Decisions
- **Expansion** (grow existing business), **Diversification** (new products), **Replacement** (old machine → new), **Modernization**, **Mandatory** (safety/legal).

### Key idea: Cash Flows, not profits
Capital budgeting uses **cash flows**, and often the **time value of money** (₹1 today > ₹1 tomorrow).
- **Initial Investment / Cash Outflow** at year 0.
- **Cash Inflows** = Profit After Tax + Depreciation (depreciation is a non-cash expense, added back).

---

## 2. Two Groups of Methods

| Traditional (Non-discounted) | Modern (Discounted Cash Flow) |
|------------------------------|-------------------------------|
| Ignore time value of money | Consider time value of money |
| 1. Payback Period | 3. Net Present Value (NPV) |
| 2. Accounting Rate of Return (ARR) | 4. Internal Rate of Return (IRR) |
| | 5. Profitability Index (PI) |

---

## 3. Payback Period (PBP)

**Time taken to recover the initial investment** from cash inflows.

**When inflows are equal (even):**
> **Payback Period = Initial Investment ÷ Annual Cash Inflow**

**When inflows are unequal:** add up cash inflows year by year until the investment is recovered.

**Decision rule:** Accept the project with the **shortest** payback (or below a set maximum).

**Example:** Investment ₹1,00,000; annual inflow ₹25,000.
- Payback = 1,00,000 ÷ 25,000 = **4 years**

**Pros:** Simple; emphasizes liquidity & quick recovery.
**Cons:** Ignores time value of money; ignores cash flows *after* payback; ignores overall profitability.

*(Variation: **Discounted Payback Period** uses discounted cash flows — fixes the time value flaw.)*

---

## 4. Accounting Rate of Return (ARR) / Average Rate of Return

Based on **accounting profit**, not cash flow.

> **ARR = (Average Annual Profit after tax ÷ Average Investment) × 100**
> **Average Investment = (Initial Investment + Scrap Value) ÷ 2**
> *(Sometimes ARR is calculated on original investment instead of average.)*

**Decision rule:** Accept if ARR > required rate; choose the **highest** ARR.

**Example:** Avg annual profit ₹20,000; Initial investment ₹1,00,000, scrap ₹0.
- Average Investment = 1,00,000 ÷ 2 = ₹50,000
- ARR = (20,000 ÷ 50,000) × 100 = **40%**

**Pros:** Simple; uses familiar profit figures.
**Cons:** Ignores time value of money; uses profit not cash flow.

---

## 5. Net Present Value (NPV) ⭐ (most important)

**NPV** = Present Value of all cash **inflows** − Present Value of cash **outflows** (initial investment). It discounts future cash flows to today using the cost of capital.

> **NPV = Σ [ Cash Inflowₜ ÷ (1 + r)ᵗ ] − Initial Investment**
> r = discount rate (cost of capital), t = year.

**Decision rule:**
- **NPV > 0** → Accept (adds value).
- **NPV < 0** → Reject.
- Among projects, choose the **highest positive NPV**.

**Example:** Investment ₹1,00,000; inflows ₹40,000/year for 3 years; r = 10%.

| Year | Inflow | PV factor @10% | Present Value |
|------|--------|----------------|---------------|
| 1 | 40,000 | 0.909 | 36,360 |
| 2 | 40,000 | 0.826 | 33,040 |
| 3 | 40,000 | 0.751 | 30,040 |
| | | **Total PV** | **99,440** |

- NPV = 99,440 − 1,00,000 = **−₹560** → slightly negative → **Reject**.

**Pros:** Considers time value & all cash flows; gives value in ₹; best for wealth maximisation.
**Cons:** Needs a discount rate; absolute figure (not ideal to compare projects of different sizes).

---

## 6. Internal Rate of Return (IRR)

**IRR** = the discount rate at which **NPV = 0** (inflows PV = outflows). It's the project's own "yield."

**Decision rule:**
- **IRR > Cost of Capital** → Accept.
- **IRR < Cost of Capital** → Reject.

**Finding IRR (interpolation formula):**
> **IRR = L + [ NPV at L ÷ (NPV at L − NPV at H) ] × (H − L)**
> L = lower rate (positive NPV), H = higher rate (negative NPV).

**Pros:** Considers time value; expressed as a % (easy to understand).
**Cons:** Complex calculation; can give multiple IRRs with unconventional cash flows; assumes reinvestment at IRR.

---

## 7. Profitability Index (PI) / Benefit-Cost Ratio

> **PI = Present Value of Cash Inflows ÷ Initial Investment**

**Decision rule:**
- **PI > 1** → Accept.
- **PI < 1** → Reject.
- Useful to **rank** projects when capital is limited (capital rationing).

**Example:** PV of inflows = ₹1,20,000; Investment = ₹1,00,000.
- PI = 1,20,000 ÷ 1,00,000 = **1.2** → Accept.

---

## 8. NPV vs IRR (exam point)
- Both are discounted methods and usually agree for independent projects.
- For **mutually exclusive** projects they may conflict (due to size/timing differences). **NPV is generally preferred** because it directly measures rupee value added (aligns with wealth maximisation).

---

## ✅ Quick Recap (Unit II)
- **Cash inflow = PAT + Depreciation.**
- **Payback = Investment ÷ Annual inflow** (shortest is best; ignores time value).
- **ARR = Avg profit ÷ Avg investment × 100.**
- **NPV = PV of inflows − Investment**; accept if **> 0**.
- **IRR** = rate where NPV = 0; accept if **IRR > cost of capital**.
- **PI = PV of inflows ÷ Investment**; accept if **> 1**.
- **NPV is the most preferred** method.
