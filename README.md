# Miduction

**Midlife crisis? Nah — just some data science.**

This project dives into the MIDUS 2 dataset to see how personality traits (think Big Five: extraversion, neuroticism, etc.) line up with things like financial satisfaction, life satisfaction, and mental health. Basically: can your personality predict how well life’s going?

## What's in here?

We:
- Load and clean data from the MIDUS 2 study (ICPSR 04652)
- Use UMAP to reduce those juicy personality variables into 2D space
- Color-code the plots by self-reported “success” metrics (like money and life satisfaction)
- Try to answer questions like: *are chill, responsible people doing better?*

## Data

- Data comes from the **MIDUS 2 Biomarker Project**, downloaded via ICPSR.
- Due to licensing, the raw data isn’t included here. You’ll need to get it yourself if you want to run the code.

## Requirements

You'll need Python and some usual suspects:

```bash
pip install pandas numpy matplotlib seaborn umap-learn pyreadstat scikit-learn
