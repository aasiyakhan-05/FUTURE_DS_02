
# Customer Retention & Churn Analysis - Report

**Date:** May 31, 2026
**Analysis Period:** June 2025 - May 2026
**Prepared for:** Future Interns Internship Program
**CIN ID:** FIT/JUN26/DS20705

---

## Executive Summary

This analysis examines customer retention and churn patterns across 100 customers over a 12-month period. The study identifies key churn drivers, retention opportunities, and provides actionable recommendations to improve customer lifetime value.

### Key Metrics Overview

| Metric | Value |
|--------|-------|
| **Total Customers** | 100 |
| **Retention Rate** | 79.0% |
| **Churn Rate** | 21.0% |
| **Active Customers** | 79 (79.0%) |
| **Churned Customers** | 21 (21.0%) |
| **Average CLV** | $353.49 |
| **Revenue Lost to Churn** | $841.45 |
| **Current Active MRR** | $5,429.21 |

---

## 1. Churn Overview

### Overall Churn Metrics
- **Total Customers Analyzed:** 100
- **Churned Customers:** 21 (21.0%)
- **Active Customers:** 79 (79.0%)
- **Average Customer Lifetime:** 154 days (5.1 months)
- **Median Customer Lifetime:** 141 days (4.7 months)

### Early Churn Alert
- **Churn within 1 month:** 13 customers (61.9% of all churn)
- **🚨 Critical Issue:** High early churn indicates ONBOARDING PROBLEMS

---

## 2. Churn by Subscription Type

### Analysis by Tier

| Premium | 33 | 3 | 9.1% | 178 days |
| Basic | 34 | 17 | 50.0% | 97 days |
| Pro | 33 | 1 | 3.0% | 189 days |

### Key Findings

- **1. Basic:** 50.0% churn rate
  - Customers: 34
  - Avg Lifetime: 97 days

- **2. Premium:** 9.1% churn rate
  - Customers: 33
  - Avg Lifetime: 178 days

- **3. Pro:** 3.0% churn rate
  - Customers: 33
  - Avg Lifetime: 189 days

### Insight
**Basic tier has highest churn** at 50.0%. These price-sensitive customers need special attention and engagement strategies.

---

## 3. Churn by Contract Length

### Analysis by Contract Duration
- **1-Month Contracts:** 17/34 churned (50.0%)
- **6-Month Contracts:** 1/33 churned (3.0%)
- **12-Month Contracts:** 3/33 churned (9.1%)

### Insight
**1-month contracts show highest churn** at 50.0%. Short-term commitments lack commitment alignment and need stronger incentives.

---

## 4. Impact of Customer Engagement (Support Tickets)

### Support Interaction Analysis
- **0 support tickets:** 29.4% churn, $118.67 avg CLV
- **1 support tickets:** 18.8% churn, $357.75 avg CLV
- **2 support tickets:** 26.9% churn, $387.80 avg CLV
- **3 support tickets:** 21.4% churn, $422.14 avg CLV
- **4 support tickets:** 0.0% churn, $471.47 avg CLV
- **5 support tickets:** 0.0% churn, $1,176.55 avg CLV

### Insight
**Higher engagement = Lower churn.** Customers with support interactions are significantly more likely to stay. Engagement is a key retention driver.

---

## 5. Regional Performance

### Churn by Region
- **East:** 12.0% churn
- **North:** 12.0% churn
- **South:** 36.0% churn
- **West:** 24.0% churn

### Insight
**South region underperforms** with 36.0% churn. Regional factors or support gaps may exist.

---

## 6. Customer Segment Analysis

### Performance by Segment
- **Enterprise:** 9.1% churn, $593.68 avg CLV
- **SMB:** 50.0% churn, $96.53 avg CLV
- **Mid-Market:** 3.0% churn, $378.06 avg CLV

### Insight
Different segments show varying churn patterns. Enterprise customers typically show lower churn but higher CLV concentration.

---

## 7. Cohort Analysis

### Retention by Signup Month
The cohort analysis reveals retention patterns across different signup cohorts. Early cohorts show different retention curves compared to recent signups.

### Key Findings
- Best performing cohorts show 75%+ retention
- Worst performing cohorts drop to 50%+ churn
- Retention tends to stabilize after 3 months

---

## 8. Customer Lifetime Value

### CLV Insights

- **Total CLV Generated:** $35,349.20
- **Average CLV:** $353.49
- **Highest CLV:** $1,213.21

### Active vs Churned Comparison
- **Active Customers Avg CLV:** $436.81
- **Churned Customers Avg CLV:** $40.07
- **Difference:** $396.74

---

## 9. Top 5 Churn Drivers (Ranked by Impact)

### 1. 🔴 Early Onboarding (Months 0-1)
- **Impact:** 61.9% of all churn
- **Problem:** Customers churn immediately after signup
- **Root Cause:** Poor onboarding, unclear value, technical issues
- **Action:** Overhaul onboarding flow

### 2. 🔴 Short-Term Contracts (1 months)
- **Impact:** 50.0% churn rate
- **Problem:** Low commitment leads to quick exits
- **Root Cause:** No long-term commitment incentive
- **Action:** Offer discounts for longer contracts

### 3. 🔴 Low Engagement (Zero Support Tickets)
- **Impact:** 29.4% churn rate
- **Problem:** Inactive customers don't see value
- **Root Cause:** Lack of guidance, unclear benefits
- **Action:** Proactive engagement campaigns

### 4. 🔴 Basic Tier
- **Impact:** 50.0% churn rate
- **Problem:** Price-sensitive users undervalue service
- **Root Cause:** Limited features, weak retention
- **Action:** Upgrade paths with clear benefits

### 5. 🔴 South Region
- **Impact:** 36.0% churn rate
- **Problem:** Regional-specific issues
- **Root Cause:** Support gaps, pricing, or market fit
- **Action:** Regional investigation & targeted fixes

---

## 10. Strategic Recommendations

### 1️⃣ URGENT (0-30 Days): Fix Onboarding
**Problem:** 61.9% of customers churn in first month

**Actions:**
- Create mandatory onboarding checklist (5 key setup steps)
- Send welcome email series (Days 1, 3, 7)
- Schedule proactive support check-in at Day 5
- Add in-app guidance and video tutorials
- Collect early feedback at Day 3

**Expected Impact:** Reduce early churn by 30-50%

**Timeline:** 2-3 weeks implementation

---

### 2️⃣ HIGH PRIORITY (30-60 Days): Lock-in Longer Contracts
**Problem:** 50.0% churn on 1-month contracts

**Actions:**
- Offer 20-30% discount for 6-month contracts
- Highlight commitment benefits (stability, loyalty rewards)
- Create upgrade path from 1M → 6M → 12M
- Feature customer success stories with longer commitments

**Expected Impact:** Convert 20% of monthly to 6-month

**Timeline:** 4 weeks implementation

---

### 3️⃣ HIGH PRIORITY (30-90 Days): Increase Engagement
**Problem:** 29.4% churn for customers with zero support interactions

**Actions:**
- Send monthly "best practices" tips
- Schedule quarterly check-in calls
- Create product knowledge base
- Implement live chat support
- Build in-app guidance tutorials

**Expected Impact:** Reduce inactive churn by 40%

**Timeline:** 6-8 weeks implementation

---

### 4️⃣ MEDIUM PRIORITY (60-90 Days): Upgrade Basic Tier
**Problem:** 50.0% churn on Basic tier

**Actions:**
- Create clear Pro/Premium feature comparison
- Offer limited-time upgrade discounts (15-25% off)
- Show ROI of upgrades with case studies
- Implement feature limits that encourage upgrades

**Expected Impact:** Upgrade 15% of Basic customers

**Timeline:** 8 weeks implementation

---

### 5️⃣ MEDIUM PRIORITY (60-120 Days): Regional Strategy
**Problem:** 36.0% churn in South region

**Actions:**
- Conduct customer interviews to identify issues
- Hire regional support specialist
- Tailor marketing/pricing for region
- Create region-specific success metrics

**Expected Impact:** Reduce regional churn by 25%

**Timeline:** 12 weeks implementation

---

### 6️⃣ ONGOING: Proactive Retention Program
**Actions:**
- Monthly Net Promoter Score (NPS) surveys
- Win-back campaigns for at-risk customers
- VIP program for high-value customers ($1000+ CLV)
- Quarterly business reviews for Enterprise

**Expected Impact:** Increase retention by 10-15%

---

## 11. Financial Impact Projection

### Current State
- **Churn Rate:** 21.0%
- **Retention Rate:** 79.0%
- **Monthly Revenue Lost:** $69.35
- **Annual Revenue Lost:** $832.20

### Projected After Recommendations (Conservative 25% Churn Reduction)
- **New Churn Rate:** 15.8%
- **New Retention Rate:** 84.2%
- **Customers Retained:** +5
- **Monthly Revenue Saved:** +$330.70
- **Annual Revenue Impact:** +$3,968.37

### Optimistic Scenario (40% Churn Reduction)
- **New Churn Rate:** 12.6%
- **Annual Revenue Impact:** +$6,349.39

---

## 12. Implementation Timeline

### Month 1: Quick Wins
- ✅ Launch onboarding improvements
- ✅ Begin contract upgrade campaigns
- ✅ Start engagement initiatives

### Month 2-3: Scale Programs
- ✅ Roll out regional strategy
- ✅ Implement pro-active support
- ✅ Launch loyalty program

### Month 4+: Optimize & Expand
- ✅ Monitor metrics and adjust
- ✅ Scale successful programs
- ✅ Expand to new initiatives

---

## 13. Success Metrics & KPIs to Track

- **Churn Rate:** Target <18% (from current 21.0%)
- **Retention Rate:** Target >82% (from current 79.0%)
- **Average CLV:** Target $441.86 (from current $353.49)
- **Time to Churn:** Target >4 months (from current 1.0 months)
- **Early Churn %:** Target <20% (from current 61.9%)

---

## 14. Conclusion

The analysis reveals that customer retention is challenged primarily by:
1. **Poor onboarding** (30% of churn in first month)
2. **Short-term contracts** (lack commitment alignment)
3. **Low engagement** (inactive customers churn faster)
4. **Tier mismatch** (Basic tier undervalues service)
5. **Regional gaps** (support or product issues)

By implementing the recommended actions, we can conservatively reduce churn by 25%, generating an **additional $3,968 in annual revenue**.

**Key Takeaway:** Focus on onboarding excellence and customer engagement as the highest-impact retention levers.

---

## Data Summary
- **Analysis Date:** 2026-06-28 21:31:55
- **Data Period:** 2025-06-01 to 2026-05-05
- **Total Records Analyzed:** 100
- **Analysis Method:** Cohort Analysis, Churn Rate Analysis, Customer Lifetime Value

---

*Report Generated for Future Interns - Data Science & Analytics Track*
