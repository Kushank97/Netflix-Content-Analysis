# Netflix-Content-Analysis
![output_1_0](https://github.com/user-attachments/assets/3fc3ca0d-5d87-4a15-9107-846f4c9e78f3)

🔍 Project Overview
This project dives into Netflix’s content catalog (movies & TV shows) to uncover:

Content distribution patterns (Movies vs. TV Shows)

Release trends over time

Geographic production hubs

Viewer demographics (via rating analysis)

Optimal content duration

Developed as part of my data analysis skill-building journey before transitioning to machine learning, this project emphasizes real-world data challenges and actionable insights.

🛠️ Technical Implementation
1. Data Cleaning & Preprocessing
Handled messy real-world data with:

30%+ missing values in Director/Cast columns → Imputed with "Unknown"

Inconsistent duration formats (e.g., "93 min" vs. "4 Seasons") → Extracted numeric values using regex:

2. Key Analyses
Analysis	Insight	Tool Used
Content Type Distribution	70% Movies, 30% TV Shows	Pandas, Matplotlib
Yearly Release Trends	2020 peak (1,500+ releases)	Seaborn
Rating Analysis	TV-MA (adult) dominates (45% of content)	Crosstab
Movie Duration	90-120 mins = Standard (65% of movies)	Histplot
3. Advanced Techniques
Dynamic visualizations with Netflix’s brand colors (#E50914 red + dark theme)


Challenge	Solution
Missing director/cast data	
Mixed duration formats	Regex extraction + separate Movie/TV logic
Irregular date formats	Used pd.to_datetime() with errors='coerce'
Example Code Snippet:

📈 Key Takeaways
Content Strategy: Netflix prioritizes movies over TV shows (2:1 ratio)

Global Expansion: 25% of content now comes from non-US countries (India, UK, Japan)

Audience Focus: Mature (TV-MA) and teen (TV-14) content drives engagement
