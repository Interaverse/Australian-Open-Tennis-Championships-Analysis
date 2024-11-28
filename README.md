# Australian Open Tennis Championships Analysis

## Overview
This project analyzes historical data from the Australian Open tennis tournaments. It explores trends in player performance, country dominance, and evolving patterns across different eras of the competition. The dataset spans tournaments from 1905 to 2024 and includes information on champions, runner-ups, scores, and player statistics.

## Key Features
- **Data Types**: Includes nominal, ordinal, and ratio data such as player seeds, match durations, and nationalities.
- **Visualization Tools**: Data visualizations created using Tableau, focusing on trends, outliers, and key insights.
- **Insights**:
  - Historical dominance of Australia and the United States in earlier decades.
  - Modern shifts in global competitiveness with rising European dominance.
  - Patterns in player performance across sets, highlighting top-seeded players' consistency.

## Data Preparation
- **Transformations**:
  - Cleaned `Year` column for uniformity.
  - Removed redundant columns like `Champion Nationality`.
  - Normalized set scores for visual clarity.
  - Introduced calculated fields, such as overall and set-specific win rates.
- **Missing Data**:
  - Handled null values for seeds before 1923 by marking them as "N/A."
  - Removed attributes like `Mins` with insufficient data.

## Visualizations
1. **Tree Map**: Total champions per country.
   - Highlighted dominance of Australia and the U.S., with emerging contributions from smaller nations.
2. **Parallel Coordinates**: Set win rates by champion seed and gender.
   - Showcased consistent performance by top seeds and outliers among lower seeds.
3. **Geographic Map**: Distribution of champions by country and seed.
   - Visualized regional strengths, emphasizing Europe's dominance in top-seeded players.
4. **Scatter Plots**: Champions and runner-ups by country over time.
   - Illustrated historical and modern shifts in player dominance.
5. **Top Player Performance**: Parallel coordinate chart and scatter plots.
   - Compared performance consistency and winning streaks among legendary players like Djokovic, Federer, and Serena Williams.

## Trends and Insights
- **Historical Patterns**:
  - Australia dominated early tournaments; Europe has risen to prominence in recent years.
  - Top seeds generally exhibit stronger performance, but unexpected victories by lower-seeded players add intrigue.
- **Player Performance**:
  - Late-set stamina differentiates champions like Serena Williams and Novak Djokovic.
  - Male champions often display more variability in late sets compared to women.
- **Country Dominance**:
  - Australia and the U.S. remain key contributors, but nations like Serbia and Switzerland have emerged as modern powerhouses.

## Challenges in Tableau
- **Strengths**:
  - Intuitive interface and versatile visualization options.
  - Effective dashboard and story features for combining visual insights.
- **Limitations**:
  - Limited data preprocessing capabilities.
  - Challenges with customizing annotations and formatting.

## Conclusion
This analysis highlights the Australian Open's evolving history, from predictable top-seeded dominance to surprising upsets. As the tournament grows more global, it showcases a rich tapestry of established champions and emerging talents, cementing its place in tennis history.

---
### Tools Used
- **Data Visualization**: Tableau
- **Data Cleaning and Preprocessing**: Excel
- **Programming**: Python (optional for future automation)
