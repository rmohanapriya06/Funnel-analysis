# AlfidoTech – Internship Conversion Funnel Analysis  

OBJECTIVE:  
The objective of this task was to analyze Alfido Tech’s internship recruitment funnel to identify where candidates drop off, understand the factors influencing offers and joining, and provide actionable recommendations to improve conversion rates.

DATA: 

Source:Synthetic internship funnel dataset (generated using Python in Google Colab).  
Contents:Candidate ID, source (LinkedIn, Referral, Website, Campus), education level, GPA, stage (Applied → Screen → Assessment → Interview → Offer → Join), stage date, offer status, join status.  
Size:500 candidate records covering multiple recruitment stages.  

ANALYSIS PERFORMED:

Data Cleaning & Preprocessing: Removed duplicates, standardized stage order, validated timestamps.  
Funnel Analysis: Counted candidates at each stage and calculated conversion rates between stages.  
Segment Analysis: Compared conversion rates by source (LinkedIn, Referral, Campus) and education level.  
Bounce/Drop‑off Identification: Highlighted the largest drop‑off between Applied → Screen stage.  
Predictive Modeling: Built logistic regression models to estimate probability of offer and joining based on GPA, source, and education.  
Feature Importance: Interpreted coefficients to identify key drivers of offers and joins.  
Visualizations: Created bar charts for funnel counts, conversion tables, and feature importance plots.  

TOOLS USED:  
Python– for data generation and analysis  
Pandas – for data cleaning, aggregation, and funnel metrics  
Matplotlib – for funnel and feature importance visualizations  
Scikit‑learn – for logistic regression modeling and evaluation  
Google Colab – for running notebooks and sharing results  

OUTCOMES:
The analysis generated actionable insights into the internship recruitment funnel:  
Drop‑off: The largest candidate loss occurred between Applied → Screen, suggesting screening is the bottleneck.  
Sources:  Referrals and campus hires showed higher offer and join rates compared to LinkedIn applicants.  
Predictors: Higher GPA and certain education streams (e.g., M.Tech) were positively correlated with offers.  
Joining Behavior: Candidates sourced via campus drives were more likely to accept and join after an offer.  

BUSINESS IMPACT:
These insights can guide Alfido Tech to streamline screening processes, prioritize high‑yield sourcing channels, and tailor communication strategies to improve join rates.
  
Would you like me to also draft a **1‑page executive summary version with screenshots placeholders** (like “Insert Funnel Chart Here”) so you can submit it exactly as required?
