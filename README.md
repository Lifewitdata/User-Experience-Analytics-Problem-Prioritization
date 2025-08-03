# User-Experience-Analytics-Problem-Prioritization
# User Experience Analytics & Problem Prioritization

## Project Overview
This project analyzes simulated datasets of user activity, complaints, and Net Promoter Scores (NPS) to identify and prioritize key challenges affecting customer and seller experience.

The goal is to:
- Detect trends such as a drop in NPS scores
- Identify frequent complaint categories
- Find users with low engagement
- Rank these problems based on their impact

---

## Key Insights
### 1. NPS Distribution
- **63%** of users are detractors.
- Only 14% are promoters.

![NPS Distribution](images/nps_distribution.png)

### 2. Frequent Complaints
- Top complaint types:
  - Late delivery (18)
  - Poor service (18)
  - App issues (14)

![Complaints Frequency](images/complaints_frequency.png)

### 3. Low Engagement Users
- 2 users have very low engagement (short sessions and few pages visited).

---

## Methodology
1. **Data Preparation**: Simulated data using NumPy and Pandas.
2. **Analysis**:  
   - Categorized NPS scores (Promoters, Passives, Detractors)
   - Counted and ranked complaint types
   - Flagged low-engagement users
3. **Visualization**:  
   - Countplot for NPS scores
   - Bar chart for complaint types
   - Scatterplot for engagement

---

## Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

---

## Next Steps
- Build an alerting system when NPS drops or complaints spike
- Create a dashboard (Streamlit/Dash) for real-time tracking
- Use predictive analytics to forecast engagement and complaints

---

## Project Structure
