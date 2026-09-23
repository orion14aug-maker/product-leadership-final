# Financial Model: Fable Growth — Team Tier Expansion Gate

> Module 5 · Master Product Financials & Strategic Bets, ★ Deliverable 5
>
> The business case for funding the Fable Team Tier bet, the assumptions carrying the model, and the explicit kill criteria that determine when to stop.

## Strategic fit

The course-provided Fable financial case evaluates a **Team & Enterprise Tier**: a B2B expansion path in which highly engaged individual Fable users become the acquisition channel into paid team plans.

This is deliberately treated as a **gated later-stage growth bet**, not a replacement for the current post-acute retention strategy. The existing Fable roadmap prioritises personalised post-acute engagement, reliable re-engagement, and everyday wellbeing value first. Team expansion should only scale if the economics hold and it does not displace those core retention bets.

---

## 1. Business case

### Strategic bet

Fable will test a Team Tier priced at **$12 per seat per month**, targeted at SMB wellness leads. Individual users who complete **three AI check-ins per week** become the acquisition channel into team plans. At week four, Fable generates a productivity and wellbeing report that the user can share with their manager, creating the conversion mechanism from individual usage to a six-seat team subscription.

### Core assumptions and economics

| Assumption | Value | Source / rationale |
|---|---:|---|
| Team price | **$12 / seat / month** | Course-provided Fable Case A |
| Average team size | **6 seats** | Course-provided Fable Case A |
| First-year revenue per converted team | **$864** | $12 × 6 seats × 12 months |
| Weekly-active individual pilot base | **3,000 users** | Course-provided Fable Case A |
| Individual-to-team conversion | **4%** | Course-provided assumption and the model's load-bearing assumption |
| Expected team conversions | **120 per quarter** | 3,000 × 4% |
| Annual team churn | **15%** | Course-provided assumption |
| Individual CAC | **$38** | Current paid-social CAC supplied in the case |
| Conversion-adjusted CAC per team | **$950** | $38 ÷ 4% conversion; this is the more decision-useful acquisition cost for one converted team |
| Simplified revenue LTV per team | **$5,760** | $864 annual revenue ÷ 15% annual churn; revenue-based approximation because contribution margin is not provided |
| LTV:CAC | **~6.1:1** | $5,760 LTV ÷ $950 conversion-adjusted CAC |
| Payback period — stated in case | **4.7 months** | Course-provided headline figure |
| Payback period — recalculated from supplied assumptions | **~13.2 months** | $950 conversion-adjusted CAC ÷ $72 monthly team revenue |
| Investment required | **TBD — not supplied** | Full engineering, product, design, AI/infrastructure, GTM and support investment is not provided in the case and must be quantified before scale approval |
| Expected return | **$103,680 net new ARR in Q1** | 120 conversions × $864 first-year team revenue |

### The case in one paragraph

> **Fable has a potentially attractive expansion path if highly engaged individual users can reliably convert into six-seat team accounts at the assumed 4% rate. At that conversion level, 3,000 weekly-active individuals generate 120 team conversions per quarter and $103,680 in net new ARR, with a simplified revenue LTV of approximately $5,760 per team. However, the headline economics require correction before scale approval: the supplied $38 CAC is an individual-user CAC, so at 4% conversion the effective acquisition cost per converted team is approximately $950, implying a payback period of roughly 13.2 months rather than the stated 4.7 months. I would therefore fund this only as a gated validation bet, not as a current-quarter strategic replacement for post-acute retention, and would require the corrected unit economics and full investment requirement to be established before Q3 headcount or scale investment is committed.**

---

## 2. Financial stress-test

### 2.1 Load-bearing assumption

The **4% individual-to-team conversion rate** carries the most weight because it controls both conversion volume and effective team acquisition cost.

| Conversion rate | Change vs. model | Team conversions / quarter | Net new ARR | Effective CAC / converted team | Approx. payback |
|---:|---:|---:|---:|---:|---:|
| **4.0%** | Base case | 120 | $103,680 | $950 | 13.2 months |
| **3.2%** | 20% below assumption | 96 | $82,944 | $1,187.50 | 16.5 months |
| **3.0%** | Kill threshold | 90 | $77,760 | $1,266.67 | 17.6 months |
| **2.8%** | 30% below assumption | 84 | $72,576 | $1,357.14 | 18.8 months |

**Finding:** A 20–30% miss on conversion does not merely reduce ARR; it materially increases the effective acquisition cost and lengthens payback.

### 2.2 Retention sensitivity

If annual churn is **10 percentage points higher**, rising from 15% to **25%**:

- Simplified revenue LTV falls from **$5,760 to $3,456**.
- At the base conversion-adjusted CAC of $950, LTV:CAC falls from approximately **6.1:1 to 3.6:1**.
- The economics remain above the course's 3:1 reference point, but the margin of safety becomes much thinner.

**Finding:** The bet remains economically plausible under the churn stress test, but only if conversion and acquisition costs hold close to plan.

### 2.3 CAC / payback sensitivity

If individual CAC is **20% higher**, increasing from $38 to **$45.60**:

- Effective CAC per converted team rises from **$950 to $1,140** at 4% conversion.
- Recalculated payback rises from approximately **13.2 months to 15.8 months**.
- If churn simultaneously rises to 25%, simplified LTV:CAC falls to approximately **3.0:1**.

**Finding:** The case has limited headroom if acquisition cost and churn deteriorate together. The business should not rely on the stated 4.7-month payback until the CAC unit and conversion mechanics are reconciled.

### 2.4 Structural problem

The model mixes **individual-user acquisition cost** with **team-account revenue**. A $38 individual CAC cannot be directly compared with $72 of monthly team revenue when only 4% of acquired individuals are expected to become team conversions.

The financially relevant acquisition cost for the team account is approximately:

> **$38 ÷ 4% = $950 per converted team**

Using that cost against $72 in monthly team revenue produces an approximate **13.2-month payback**, so the stated **4.7-month payback does not reconcile with the other supplied assumptions**.

This must be resolved before the model is used for a scale-funding decision.

---

## 3. Funding decision

### Verdict: FUND WITH CONDITIONS

The bet is promising enough to validate because the base case produces meaningful incremental ARR and the simplified LTV:CAC remains above 3:1 under a 10-point churn stress test. However, it should **not receive scale funding or committed Q3 headcount yet** because the payback calculation is structurally inconsistent and the total investment required is not supplied.

### Conditions before scale funding

1. **Validate individual-to-team conversion at or above 3% by the end of Q2.**
2. **Rebuild CAC and payback using conversion-adjusted team acquisition cost**, rather than comparing individual CAC directly with team revenue.
3. **Quantify the full investment requirement** across product, engineering, design, AI/infrastructure, GTM and support before approving scale.
4. **Do not displace the current post-acute retention Rocks** unless the strategic roadmap is explicitly changed based on new evidence.

---

## 4. Kill criteria

The original case says the GTM approach will be **“reassessed”** if conversion remains below 3% by the end of Q2. That is not a complete kill criterion because it specifies a metric, threshold and timeline but does not force a financial consequence.

### Final kill criterion

> **If individual-to-team conversion does not reach at least 3% by the end of Q2, we will stop scaling the Team Tier, commit no additional Q3 headcount to the initiative, and reallocate the planned Q3 product, engineering and GTM capacity to Fable's core post-acute retention roadmap.**

### Secondary funding gate

> **Even if conversion reaches 3%, no scale investment will be approved until the conversion-adjusted CAC, payback period and full initiative investment are reconciled and documented.**

This makes the decision enforceable without requiring another meeting to decide what “reassess” means.

---

## 5. Key financial takeaways

- **Load-bearing assumption:** 4% individual-to-team conversion.
- **Base expected return:** $103,680 net new ARR from 120 quarterly team conversions.
- **Simplified team LTV:** approximately $5,760.
- **Conversion-adjusted team CAC:** approximately $950.
- **Simplified LTV:CAC:** approximately 6.1:1.
- **Corrected base payback:** approximately 13.2 months using the supplied inputs.
- **20% higher CAC payback:** approximately 15.8 months.
- **25% churn LTV:CAC:** approximately 3.6:1 at base CAC.
- **Main model risk:** the supplied 4.7-month payback does not reconcile with the stated CAC, conversion rate and team revenue.
- **Funding posture:** validate first; do not commit scale headcount until the unit economics and total investment are corrected.

---

## Related artifacts

- [Product Strategy & OKRs](../01-strategy/strategy-and-okrs.md)
- [Outcome Roadmap & Trade-off Memo](../02-roadmap/outcome-roadmap.md)
- [Team Charter](../03-team-charter/team-charter.md)

---

## Link to full artifact

[Financial Model & Kill Criteria](https://github.com/orion14aug-maker/product-leadership-final/blob/main/05-financial-model/financial-model.md)
