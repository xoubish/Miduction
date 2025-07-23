# Miduction  
*Midlife crisis? Nah — just some data science.*

This project started with the **MIDUS 2 dataset**, a rich trove of adult health, psychology, and life satisfaction data. But what really got this going was a curiosity about something more... provocative:

> *Do darker personality traits — narcissism, Machiavellianism, psychopathy — relate to financial success?*

MIDUS doesn’t include a formal **Dark Triad** scale, but it does include dozens of self-descriptive items about confidence, warmth, ambition, empathy, impulsivity, etc. So we're starting here — mapping traits, reducing dimensions, and asking: *Can we trace the shadows of the dark triad in everyday survey data?*

## Traits We Use

We also include the **Big Five** personality traits — a classic model in psychology — because it’s already in the dataset and helps anchor things:

- **Extraversion** – outgoing, social, talkative  
- **Neuroticism** – anxious, moody, easily upset  
- **Agreeableness** – kind, cooperative, warm  
- **Conscientiousness** – organized, responsible, hardworking  
- **Openness to Experience** – curious, imaginative, open-minded  

We also use scales related to agency, purpose, well-being, and emotional health.

## What’s in here?

We:
- Load and clean MIDUS 2 data (ICPSR 04652)
- Use UMAP to visualize personality space in 2D
- Color those maps by “success” variables like financial satisfaction, life satisfaction, and self-rated health
- Explore correlations and patterns across traits — both light and dark

## Early Findings

No grand conclusions yet, but conscientiousness and neuroticism are showing early associations with financial satisfaction. We're still hunting for the dark triad signals in the noise.

## Data

- Source: MIDUS 2 Biomarker Project (ICPSR Study 4652)
- Raw data is **not included** due to license restrictions
- You’ll need to [register and download it yourself from ICPSR](https://www.icpsr.umich.edu/web/NACDA/studies/4652)

## Requirements

```bash
pip install pandas numpy matplotlib seaborn umap-learn pyreadstat scikit-learn
