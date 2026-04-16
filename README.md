# Bank Customer Conversion Optimization – A Data Analysis Case Study

## Description
Identified key drivers of term deposit conversion (including call duration, channel, and engagement patterns) to inform strategies that improve campaign efficiency and conversion rates.

---

## Executive Summary
The bank’s telemarketing campaigns achieve a low conversion rate (~11%), with limited visibility into what drives successful outcomes.

Conversion increases significantly with longer call duration, prior engagement, and use of cellular channels, while repeated outreach shows diminishing returns. These patterns highlight clear opportunities to improve efficiency and overall campaign performance.

---

## Problem Statement
The bank conducts large-scale outbound campaigns to promote term deposits but lacks clarity on:

- Which customers are most likely to convert  
- Which campaign strategies are effective  
- Where effort is being wasted  

This limits the ability to optimize targeting, improve efficiency, and increase return on outreach efforts.

---

## Methodology
- Cleaned and validated campaign dataset (41K+ records) using Python  
- Performed exploratory analysis to evaluate conversion drivers across:
  - Customer demographics  
  - Campaign execution (channel, duration, frequency)  
  - Timing of outreach  
  - Prior engagement history  
- Engineered key features (call duration, contact frequency, loan status)  
- Quantified conversion rates across segments to identify performance gaps  

---

## Key Findings

1. **Campaign execution outweighs customer profile:** Conversion increases from **0.81% (0–100s)** to **48.61% (600+ seconds)** with call duration, and from **5.21% (telephone)** to **14.74% (cellular)** with channel choice.

2. **Prior engagement is the strongest signal of intent;** Previously successful contacts convert at **65.11%**, compared to **14.23% after prior failure** and **8.83% for first-time outreach**.

3. **Additional outreach reduces effectiveness:** Conversion declines from **13.04% (1st call)** to **6.14% (5+ calls)**, indicating diminishing returns from repeated follow-ups.

---

## Recommendations

1. **Shift targeting toward high-intent segments:** Prioritize previously engaged customers (**65.11% conversion**) and deprioritize cold outreach (**8.83% conversion**).

2. **Optimize for call quality, not volume:** Focus on longer, more effective conversations (3–5+ minutes), where conversion increases from **0.81% (<100s)** to **48.61% (600+s)**.

3. **Reduce excessive follow-ups:** Cap outreach attempts beyond initial contact, as conversion declines from **13.04% (1st call)** to **6.14% (5+ calls)**.

---

## Tools
Python (Pandas, NumPy), Matplotlib, Seaborn

---

## Skills
Exploratory Data Analysis, Descriptive Statistics, Feature Engineering, Segmentation Analysis, Comparative Analysis
