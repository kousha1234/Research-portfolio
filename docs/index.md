# Kousha — Research Portfolio
All examples use **synthetic** or **de-identified, aggregated** outputs only.

**Live site:** https://kousha1234.github.io/Research-portfolio/

## Projects
### DEFEAT: BMI (categorised) → PCS status
**Question.** Is PCS associated with BMI category (WHO cutoffs 25, 30)?  
**Methods.** Fisher’s exact tests at BMI cutoffs; logistic regression with grouped categories (reference: BMI < 25).  
→ **Read:** [HTML report](DEFEAT-BMI-categorised/index.html)

### DEFEAT: BMI (continuous) → PROMs
**Question.** How does continuous BMI relate to EQ-5D VAS, FAS, and EQ-5D-3L VAS?  
**Methods.** Descriptives, histograms/scatterplots, **Spearman correlations** (non-parametric); outlier handling noted.  
→ **Read:** [HTML report](DEFEAT-BMI-continuous/index.html)

## Resources
- [Repository README](https://github.com/kousha1234/Research-portfolio#readme)
- [MIT License](https://github.com/kousha1234/Research-portfolio/blob/main/LICENSE)

## How this site is built
- R Markdown rendered to `/docs` and served via GitHub Pages.
- No raw patient data; only synthetic or aggregated outputs.
