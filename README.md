# Pre-Clinical Animal Body Weight Study

## Project Description
This SAS project analyzes body weight changes in 7 groups of animals across a pre-clinical diabetes study:
- NC = Normal Control
- DC = Disease Control
- STD = Metformin
- HEC_LD = Herbal Extract Combination (Low Dose)
- HEC_HD = Herbal Extract Combination (High Dose)
- STD_HEC_LD = STD + HEC Low Dose
- STD_HEC_HD = STD + HEC High Dose

### Objectives
1. Generate **SDTM-like VS dataset** (baseline & final body weight)
2. Create **ADaM-like ADVS dataset** with change from baseline
3. Summarize body weight data (mean, SD)
4. Generate figures (line plot, boxplot)
5. Perform **ANOVA and pairwise comparisons** to assess treatment effects
6. Export CSV files for SDTM, ADaM, and summary tables
-------------------------------------------------------------------------------
## How to Run
1. Open `bodyweight_analysis.sas` in SAS OnDemand.
2. Run the entire code.
3. CSV files will be saved in `/home/u63324261/PreClinical Dataset Project/`.

## Interpretation
- ANOVA indicated significant differences in body weight change among groups (p=0.0267).
- Disease Control (DC) lost the most weight, NC remained stable.
- STD + HEC High Dose showed the least weight loss, suggesting the best protective effect.
