# My-second-EDA
Analysis of electricity prices from Spain, Portugal and France period 2014-2019 (60 months)

# European Energy Market Analysis (2014-2018)

## What You'll Find Here

This is my second EDA project, and honestly, I went **much deeper** this time. 

If my first project was about learning the basics, this one was about **playing with data** and asking real business questions.

---

## The Challenge

Imagine you want to run a data center in Europe. Energy costs are critical. So the question is:

**Where should you set up to get the cheapest electricity?**

And even more interesting: **Would it be worth moving between countries each month to follow the lowest prices?**

---

## What I Learned (and What You'll Learn Too)

### Data Transformation Skills
You'll see how I transformed a messy long-format dataset into a clean wide-format structure. This was crucial because the original data had countries and prices mixed in rows, making comparisons nearly impossible.

### Time Series Analysis
I worked with **daily electricity prices** from 2014 to 2018 across three countries:
- Spain (ESP)
- France (FRA)  
- Portugal (POR)

You'll see how I aggregated daily data into monthly and annual views to spot patterns.

### Comparative Analysis
I built multiple comparison strategies:
- **Monthly price comparisons** between countries
- **Annual average trends**
- **Cumulative cost analysis** (what would you actually pay over time?)

### Real Business Logic
This wasn't just about plotting graphs. I simulated real scenarios:
- What if you stay in one country for the whole period?
- What if you move every month to wherever energy is cheapest?
- **Is the operational cost of moving worth the savings?**

### Advanced Visualization
You'll find several types of visualizations:
- Line plots showing price evolution over time
- Comparative bar charts
- Cumulative cost curves
- Multi-country overlays

---

## The Surprising Conclusion

After all the analysis, I discovered something counterintuitive:

**Moving between countries every month to chase the lowest energy prices saves you only €220.40 over the entire period.**

That's basically nothing compared to:
- The cost of relocating a data center every month
- The operational complexity
- The risk and downtime

**The real insight?** Just pick a country with consistently good energy prices (like Portugal) and stay there. The difference between the best and worst country is significant, but the difference between "smart monthly moves" and "picking a good country" is negligible.

---

## Technical Skills Applied

- Data cleaning and transformation (long to wide format)
- Feature engineering (creating monthly/annual aggregations)
- Time series visualization
- Cost accumulation modeling
- Comparative statistical analysis
- Business decision-making with data

---

## Why This Matters

This project taught me that **data science isn't just about finding patterns—it's about answering questions that matter.**

Sometimes the answer is: "Don't overthink it. The optimal strategy is simpler than you think."

And that's a valuable lesson.
