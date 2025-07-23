# Miduction

**Midlife crisis? Nah — just some data science.**

This project explores how personality traits relate to life outcomes using the MIDUS 2 dataset — a big national study about how adults in the U.S. are doing in terms of health, happiness, and money. We’re asking things like: *Can your personality shape your satisfaction with life? Or your finances?*

## The Big Five (no psych degree needed)

We focus on the **Big Five** personality traits — a popular model in psychology:

- **Extraversion** – outgoing, social, talkative
- **Neuroticism** – anxious, moody, easily upset
- **Agreeableness** – kind, cooperative, warm
- **Conscientiousness** – organized, responsible, hardworking
- **Openness to Experience** – curious, imaginative, open-minded

Each person in the dataset has scores on these traits based on questionnaires.

## What's in here?

We:
- Load and clean MIDUS 2 data (ICPSR 04652)
- Use UMAP (a dimensionality reduction tool) to turn personality traits into 2D visual maps
- Color the maps by “success” variables like financial satisfaction and emotional well-being

## Data

- Source: MIDUS 2 Biomarker Project (ICPSR)
- Raw data not included — you’ll need to download it yourself from ICPSR and agree to their terms

## Requirements

```bash
pip install pandas numpy matplotlib seaborn umap-learn pyreadstat scikit-learn
