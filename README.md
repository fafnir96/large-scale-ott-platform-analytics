\# 🎬 Large-Scale OTT Platform Analytics: Unlocking Audience Growth \& Engagement



> \*\*⚠️ CONFIDENTIALITY NOTICE:\*\* > \*The raw dataset used in this analysis is proprietary and strictly confidential. To comply with NDA and data privacy standards, this repository \*\*does not\*\* contain the raw data files (CSV/GZ). It only contains the data processing logic (`.ipynb`), analytical scripts, and aggregated business insights (`.pdf`). No raw or personally identifiable information (PII) is exposed.\*



\## 📌 Executive Summary

This project explores a massive-scale user interaction dataset (approx. 14GB) from a major Video-on-Demand (OTT) platform. The primary objective is to translate raw viewing logs into actionable business strategies across four key pillars: \*\*Marketing ROI, Technical User Experience (UX), Product Feature Effectiveness, and Content Monetization.\*\*



By processing millions of rows using highly memory-efficient techniques, this analysis provides clear, data-driven recommendations to optimize ad spend, reduce churn rate, and maximize platform loyalty.



\## 🛠️ Technical Approach \& Tools Used

Handling large-scale datasets requires robust engineering methods to prevent memory overload (Out-of-Memory errors). 

\* \*\*Language \& Environment:\*\* Python, Jupyter Notebook (Google Colab).

\* \*\*Big Data Processing:\*\* Implemented \*\*Pandas Chunking\*\* (`chunksize=500,000`) to process massive data iteratively without crashing system memory.

\* \*\*Data Cleaning \& Recovery:\*\* Utilized \*\*Regular Expressions (RegEx)\*\* and URL decoding to recover corrupted marketing UTM parameters, salvaging critical attribution data.

\* \*\*Data Manipulation:\*\* Applied complex aggregation, conditional mapping, and `.explode()` methods to flatten arrays (e.g., multi-genre content) for fair statistical weighting.

\* \*\*Data Visualization:\*\* Seaborn and Matplotlib (focusing on clean, stakeholder-friendly storytelling).



\## 📊 Key Business Questions Solved

This analysis answers 5 critical business questions, detailed fully in the presentation deck:



1\. \*\*Marketing ROI \& Acquisition Quality:\*\* Which marketing campaigns bring in \*high-intent\* users (highest Quality View Rate) rather than just clickbait traffic?

2\. \*\*Technical UX \& Churn Analysis (The Drop-off Cliff):\*\* What is the maximum tolerance for latency (buffering duration) before users abandon a video, and how does it impact the completion rate?

3\. \*\*Product Feature Effectiveness:\*\* Does the \*Autoplay\* feature genuinely increase user engagement, or does it contribute to a higher Bounce Rate?

4\. \*\*Content Monetization Strategy:\*\* In the Premium (Paid) segment, which mega-genres have the highest binge-watching (completion) rates compared to the Free segment?

5\. \*\*Platform Loyalty (Core Audience):\*\* Across various ecosystems (Smart TV, Mobile App, Web-Mobile), where do the most loyal users reside based on the average watch duration?



\## 💡 Highlighted Insights

\* \*\*Marketing:\*\* Instagram Promo and Internal Share features generate the highest Quality View Rate (~19.5%), significantly outperforming YouTube Ads.

\* \*\*Technical UX:\*\* The critical latency threshold is \*\*6 seconds\*\*. Buffering beyond this point causes the completion rate to plummet, indicating a strict zero-buffering SLA requirement for Web platforms.

\* \*\*Product:\*\* \*Autoplay\* is highly effective, yielding a 43.1% completion rate with a lower bounce rate compared to manual play, proving its value in driving binge-watching behavior.

\* \*\*Loyalty:\*\* While Web-Mobile drives the highest traffic volume, \*\*Smart TVs and Mobile Apps\*\* are the true retention ecosystems, with users spending an average of 16 to 29 minutes per session.



\## 📂 Repository Contents

\* `analysis\_dataset.ipynb`: The core Python notebook containing the ETL process, data cleaning logic, chunking iteration, and EDA.

\* `LARGE-SCALE-OTT-PLATFORM-ANALYTICS.pdf`: The executive pitch deck presenting the Observation, Insight, and Recommendation (O-I-R) for C-Level stakeholders.



\## 📬 Let's Connect

I am a Data Analyst specializing in solving complex operational and product problems through data. I am actively looking for new opportunities.

\* \*\*Email:\*\* mau.irfan730@gmail.com

\* \*\*LinkedIn:\*\* https://www.linkedin.com/in/maulana-irfan/

