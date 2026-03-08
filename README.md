# Data Thinking - Feedback Analysis & Product Recommendations

This repository contains a **Jupyter Notebook** that demonstrates basic data thinking and analysis using raw JSON feedback data from a shopping application.

---

## File Included
**data_thinking.ipynb** – This notebook includes:

1. **Loading Raw JSON Data**  
   - Feedback data from a shopping app with user name, rating, and comment.

2. **Data Cleaning**  
   - Removing missing or unwanted values to make data ready for analysis.

3. **List Operations**  
   - List creation, accessing elements, size calculation, understanding shape, and identifying dimensions (1D / 2D).

4. **Insights Function** (`get_insights(data)`)  
   - Calculates **average product rating**  
   - Calculates **percentage of users with poor rating (<3)**

5. **Product Recommendation Function** (`get_recommendations(data)`)  
   - Suggests **Apple** if user rating ≥ 4  
   - Suggests **Samsung** if user rating < 4  
   - Returns a list of recommendations for all users

---

