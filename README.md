# Kaggle-NLP-Competition-Real-or-Not
This competition is hosted by Kaggle https://www.kaggle.com/c/nlp-getting-started/overview. 
I am participating in the competition in order to try my hands on the field of Artificial Intelligence known as Natural Language Processing.

## INTRO:
This repository will be an insigthful one for does who want to dabble into the Natural Language Processing (NLP).

## NOTEBOOKS BREAKDOWN:

1) BASIC EDA: This notebook gives us a brief insight of the data we will be working with.
2) NULL MODEL:This notebook creates a predictive model using a DUMMY CLASSIFIER which predicted the most frequent occurence of the TARGET column. This NULL MODEL will be a basis to measure our other predictive models against.
3) MODEL-LOCATION-KEYWORDS: This notebook uses the "location" and "keyword" columns alone to create a predictive model comparing it to the NULL MODEL.
4) MODEL-TEXT: This notebook uses the "text" column alone to create a predictive model, here NLP Packages, Libraries and Modules like "CountVectorizer" and "TfidfVectorizer" were used.
5) MODEL-FEATURE-ENGINEERING: This notebook combines engineered features (i.e features not initailly in the dataset) with the "text" column to create a predictive model, here Python Packages, Libraries and Modules like "make_pipeline", "make_union", "Pipeline", "FunctionTransformer" and "FeatureUnion" were used.

## CONCLUSION:

IT WAS A NICE RUN AND MY BEST MODEL SCORED 0.79959 ON THE KAGGLE LEADERBOARD

TAKE AWAYS: 
- MY MODEL (0.79959) OUTPERFORMED THE NULL MODEL (0.57055) WITH A REASONABLE MARGIN
- THIS REPOSITORY GIVES A BEGINNER GUIDELINE TO WORKING WITH TEXT DATA
- THE CONCEPT OF FEATURE ENGINEERING WAS APPLIED IN SIMPLE CODES
- CountVectorizer, TfidfVectorizer, Pipeline and FeatureUnion were all touched
