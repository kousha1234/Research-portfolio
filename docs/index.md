# Kousha — Research Portfolio
All examples use **synthetic** or **de-identified, aggregated** outputs only.

**Live site:** https://kousha1234.github.io/Research-portfolio/

## Projects
### DEFEAT: DEFEAT: PCS vs BMI (WHO categories 25/30)
**Question** Is PCS associated with overweight (BMI ≥ 25) or obesity (BMI ≥ 30), and across grouped WHO BMI categories?
**Methods** Fisher’s exact tests at BMI cutoffs; logistic regression with grouped categories (reference: normal weight, BMI < 25).  
→ **Read:** [HTML report](DEFEAT-BMI-categorised/index.html)

### DEFEAT: DEFEAT: BMI (continuous) vs PROMs
**Question** How does BMI (continuous) relate to FAS, IMET, and EQ-5D (index & VAS)?
**Methods** Descriptives, histograms/scatterplots, Pearson correlations (non-parametric option noted below); outlier handling noted.
→ **Read:** [HTML report](DEFEAT-BMI-continuous/index.html)

## Resources
- [Repository README](https://github.com/kousha1234/Research-portfolio#readme)
- [MIT License](https://github.com/kousha1234/Research-portfolio/blob/main/LICENSE)

## How this site is built
- R Markdown rendered to `/docs` and served via GitHub Pages.
- No raw patient data; only synthetic or aggregated outputs.
