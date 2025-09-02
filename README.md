# T20wc_22-Dashboard
End-to-End Cricket Data Analytics Project:
Building the Best 11 with ESPN T20 World Cup 2022 Data, Pandas, and Power BI:
This project features a complete data analytics workflow to identify the Best 11 T20 cricket players, using extracted data from the ESPN T20 World Cup 2022 and visualizing the results in Power BI
Problem Statement Details

**Project Overview and Problem Statement:**
The key challenge addressed was: “How do we objectively identify the best 11 cricket players for T20 matches who can score and defend runs at a world-class level?”.
Specific requirements included: The team should consistently score at least 180 runs and also be able to defend a target of 150 runs.
Player evaluation was broken down by specialist roles: Openers, Anchors/Middle Order, Finishers/Lower Order Anchors, All Rounders, and Specialist Bowlers, each with unique performance criteria.

Data Extraction and Preprocessing
Data Source: Raw match and player data was extracted directly from the ESPN T20 World Cup 2022, ensuring reliable and current insights for analysis.
Data Cleaning: Python (with Pandas) was used to preprocess and clean the datasets—standardizing metrics, managing missing values, and generating derived statistics like boundary percentages and strike rates.
CSV Conversion: The cleaned, structured data was exported to CSV files, making it straightforward to ingest into visualization and BI tools for exploration and reporting.

Dashboard Design in Power BI
Interactive Exploration: Power BI’s dashboard visualizes player statistics by role, featuring filters for phases (e.g., Qualifier, Super 12 and comprehensive tables that allow cross-role comparison.
Role-Based Metrics: Each player type is assessed by a tailored set of criteria. For example:
Openers: Batting average (>30), strike rate (>140), boundary % (>50), and innings batted.
Anchors: Batting average (>40), strike rate (>125), innings, average balls faced.
Finishers: Batting average (>25), strike rate (>140), average balls faced, and both batting/bowling contributions if applicable.
All-Rounders / Lower Order: Evaluated by batting average (>15), strike rate (>140), matches batted and bowled (>4 each), economy (<8), and bowling strike rate (<20).
Specialist Fast Bowlers: Key parameters include minimum matches bowled (>4), bowling economy (<7), strike rate (<16), bowling average (<20), and dot ball percentage (>40).
Visual Tools: Statistical trends, key performance indicators, and role summaries make it easy to interpret which players excel in each category for team optimization.

Analytical Approach and Result
By connecting real match data to robust preprocessing and visualization workflows, the project supports fully transparent, criteria-driven team selection.
The dashboard facilitates experimentation—selectors can adjust criteria or compare individuals to finalize a balanced, high-performing team for any scenario.
