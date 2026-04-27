---
layout: default
---

# Data Analysis Project

## Summary of Analysis
This project analyzes a dataset related to a COMP 110 student survey data. The goal was to explore patterns and relationships between variables using Python.

I cleaned the data and created visualizations to better understand trends and answer key questions about the dataset.

---

## Visualizations

### Chart 1
<img src="/Comp110project2/static/imgs/PNG image.png" width="500"/>

### Chart 2
<img src="/Comp110project2/static/imgs/PNG image 2.png" width="500"/>

### Chart 3
<img src="/Comp110project2/static/imgs/PNG image 3.png" width="500"/>

---

## Conclusions
The data provides moderate-to-strong support for the idea that beginners would benefit from optional pre-lecture videos:

Beginners rate the course ~1.45 points harder and desire pre-lecture videos ~0.65 points more strongly than their most-experienced peers. The box plots confirm this isn't driven by outliers — the *median* difficulty for novices sits at 5/7, while for experienced students it sits at 3/7. The violin plots show that novices cluster at lower understanding scores. The scatter plot shows a mild positive correlation between difficulty and video desire, most pronounced in the beginner group (red dots).

Potential Costs, Trade-offs, and Affected Stakeholders

- Instructional staff workload: Producing high-quality short videos takes significant time. If the course is already producing lesson videos, incremental pre-lecture "preview" clips (5–8 min) may be manageable, but this is not negligible.
- Risk of false security: Students who watch a preview video may believe they understand the material without engaging in active practice. Framing and design of videos matter.
- Experienced students: If videos are optional and well-labeled, they impose no cost. If the course were to make them *required*, experienced students would be burdened with redundant content.
- Equity: Students with poor internet access at home would be disadvantaged if videos are mandatory; keeping them optional and downloadable mitigates this.

Extensions and Future Work

1. A/B test with opt-in cohort: Offer pre-lecture videos to a volunteer subset of novice students in the next offering and compare quiz scores and self-reported understanding vs. a matched control group.
2. Track video completion vs. comprehension: If videos are deployed, correlate watch-through rate with understanding and difficulty survey responses at end-of-semester.
3. Targeted content: Rather than one video per lecture, produce videos only for the two or three topics where novice students report the greatest difficulty spike (e.g., loops, recursion, dictionaries) — data from future surveys could identify those topics.
4. Peer-made videos: Upper-level TA or students who were once in COMP110 could produce videos, reducing faculty workload while providing a relatable perspective.

---