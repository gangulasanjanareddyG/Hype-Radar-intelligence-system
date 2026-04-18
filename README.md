# 🌈 Hype Radar

**A system for understanding how attention turns into product momentum**

---

## 🚀 Live App

https://hype-radar-sanjana.streamlit.app

---

## Where this started

Why do some products suddenly feel like they are everywhere?

One week you’ve barely heard of them.
The next week they’re in videos, people are discussing them, articles are being published — and suddenly they feel important.

That shift in attention is what we usually call “hype.”
But in practice, it’s difficult to measure — and even harder to interpret.

---

## The business problem

In real-world scenarios, product attention is spread across multiple platforms:

* Search data shows curiosity
* Social platforms show discussion
* Video content shows engagement
* News shows amplification

Each of these captures a different piece of the story.

The challenge is that these signals are fragmented and often misleading when viewed individually.

This makes it difficult to answer key questions:

* Is this product gaining traction or losing interest?
* Is the attention consistent or just temporary noise?
* Should action be taken now, or later?

---

## Approach

Hype Radar treats this as a **multi-source signal integration problem**.

Instead of relying on one metric, it combines multiple indicators into a single framework that captures both:

* current visibility
* and direction of change

---

## How the system works

Each product is evaluated across four signals:

* Google Trends → search behavior
* Reddit → discussion
* YouTube → content engagement
* News → media coverage

### 1. Standardization

All signals are normalized (Z-score) and scaled to a 0–100 range.

### 2. Hype Score

A weighted score represents overall visibility:

* YouTube: 30%
* Google Trends: 25%
* News: 25%
* Reddit: 20%

### 3. Momentum Analysis

A separate metric tracks whether interest is:

* increasing
* stable
* declining

### 4. Consistency Adjustment

Signals are evaluated for variability.
More consistent trends are treated as more reliable.

### 5. Final Score

Final Score =
**70% Hype + 30% Momentum**

---

## What this enables

## 📸 Inside the app

Here’s a quick look at how the system translates data into insights:

![Dashboard](Screenshot1.png)
![Recommendation](Screenshot2.png)
![Trend](Screenshot3.png)

The system converts raw data into decision-oriented outputs:

* Ranked list of products
* Signal breakdown across platforms
* Momentum-based outlook
* Recommendation:

  * 🚀 Buy Now
  * 📈 Emerging
  * 👀 Watch Closely
  * ⚠️ Overhyped
  * ❌ Avoid
* Human-readable explanation linked to real-world behavior

---

## A simple example

A product like the iPhone often shows high hype immediately after launch, followed by a gradual decline as attention shifts to the next release cycle.

On the other hand, a product gaining traction through social media may start with lower hype but strong upward momentum.

Both situations involve attention — but they imply very different decisions.

---

## Why this matters

In practice, timing matters as much as popularity:

* High hype + declining momentum → potential overexposure
* Moderate hype + rising momentum → early opportunity

This system is designed to capture that difference.

---

## Tech stack

* Python
* Streamlit
* Pandas
* NumPy
* Plotly

---

## Future improvements

* Real-time data integration
* More advanced forecasting models
* Product comparison features
* Expanded product coverage

---

## About  

Sanjana Reddy Gangula

Master’s student in Business Analytics at California State University, East Bay  

Interested in building data-driven systems that connect real-world behavior with decision-making.

---

At its core, this project is about turning scattered signals into clearer decisions.
This was an attempt to make product hype easier to understand — not just to measure.
If you made it this far, thank you for reading!
