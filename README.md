# NHL Draft Efficiency Analysis  
### Capstone Project, Baylor University - 12,250 player dataset (1963–2015)

## Overview
This project analyzes how NHL teams have performed in the draft over time by examining the relationship between draft position and long‑term career outcomes. Using a dataset of 12,250 drafted players with complete career statistics through 2015, the report evaluates whether teams gain more or less value from their picks across eras and identifies which franchises consistently outperform expectations.

## Methods
- Exploratory data analysis  
- Multiple linear regression  
- Random forest modeling (expected career points)  
- Residual‑based efficiency scoring  
- Sensitivity analysis and outlier diagnostics  

Players were grouped into three historical eras:
- Expansion Era (1963–1993)
- Dead Puck Era (1994–2004)
- Modern Era (2005–2015)

## Key Findings
- Draft position remains the strongest predictor of NHL career performance across all eras.  
- Earlier picks consistently produce higher point totals, with the Expansion Era showing the steepest decline as draft position increases.  
- A random forest model was used to estimate expected career points; residual analysis showed a downward trend in performance relative to expectations, though this pattern was driven by extreme outliers and became insignificant once removed.  
- Top drafting teams: Detroit Red Wings, Ottawa Senators, San Jose Sharks
- Least efficient teams: Cleveland Barons, Oakland Seals, Arizona Coyotes
- Sensitivity checks confirmed that results were robust to alternative model specifications.

## Conclusion
Overall, the analysis shows that while era‑based differences exist, draft position remains the most reliable predictor of NHL career success. Certain franchises have historically demonstrated superior drafting efficiency, consistently selecting players who outperform expectations.

## Files in This Repository
- `final_report.qmd` — Clean narrative report  
- `appendix_code.qmd` — Full reproducible code  

## Tools Used
- R
- tidyverse
- tidymodels 
- randomForest 
- Quarto
