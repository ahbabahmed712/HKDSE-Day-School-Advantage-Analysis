Project Overview
This project investigates whether the advantage of attending day school differs between STEM and Arts/Humanities subjects in the 2025 HKDSE examination. The advantage is measured by comparing day school candidates against all candidates (including private candidates and self-studying individuals). The analysis reveals which academic areas are most dependent on formal schooling environments.

Key achievement levels analyzed: Level 4 (competent) and Level 5 or above (excellent)

Data Source
Official HKDSE 2025 examination results for all Category A subjects, obtained from public examination data releases. The dataset includes:

Subject-level performance with candidate numbers and percentages at different grade levels

Separate files for day school candidates and all candidates

Citizenship and Social Development (binary Attained/Unattained) vs. other subjects (Level 5** to U scale)

Key Findings
Discipline Comparison
At Level 4: Arts/Humanities shows substantially larger day school advantage (+1.10%) compared to STEM (+0.25%)

At Level 5+: STEM shows slight disadvantage (-0.24%); Arts shows essentially no gap (+0.01%)

Subject-Level Insights
Largest Arts gap: Literature in English (+1.04%) - reflects need for teacher guidance in textual analysis and essay writing

Smallest Arts gap: Chinese Language (+0.07% at Level 4, -0.33% at Level 5+)

Largest STEM gap: Information and Communication Technology (+0.46%)

Negative STEM gap: Physics (-0.36%) at Level 5+ - self-studiers outperform day school students

Popularity Analysis
No clear linear relationship between subject popularity and performance gap. Subject-specific factors dominate.

Implications
Resource allocation: Schools should focus on discussion-based learning for Arts up to Level 4 competence

Self-study support: Provide materials for students aiming for top grades, especially in STEM

Targeted investment: Subjects with large gaps (Literature in English, ICT) may benefit from additional school resources

Investigation needed: Subjects with negative gaps (Physics, Chinese Language at Level 5+) require examination to understand self-studier success

Technical Implementation
ETL Process: Power Query transformations (filtering, unpivoting grade columns, appending files)

DAX Measures: Day School %, All Candidates %, Performance Gap, Avg Gap by Discipline

Custom Columns: Level Group (achievement categorization), Popularity Category (enrollment-based classification)

Visualizations: Clustered bar charts, performance gap bar charts with discipline slicer, scatter plots

Limitations
Citizenship and Social Development excluded from level-specific comparisons (binary vs. scaled grading)

"All Candidates" includes day school students → performance gap underestimates true schooling advantage

Unweighted averages across subjects (small subjects equal weight to large ones)

Findings reflect only the 2025 cohort

"All Candidates" includes day school students → performance gap underestimates true schooling advantage

Unweighted averages across subjects (small subjects equal weight to large ones)

Findings reflect only the 2025 cohort
