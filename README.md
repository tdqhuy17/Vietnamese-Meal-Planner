# Vietnamese Meal Planner: Personalized Nutrition System

**Title:** Meal Plan Generation in Vietnamese Cuisine using Dynamic Programming and Scientifically-Grounded Nutritional Profiling  
**Domain:** Personalized Nutrition, Food Recommendation Systems (FRS), Dynamic Programming, Natural Language Processing (LLM)  

## Overview
This research addresses the severe gap of cultural specificity and scientific rigor in current Food Recommendation Systems (FRS) by proposing a novel computational framework personalized for Vietnamese cuisine. Unlike simple query matching algorithms, the proposed approach synthesizes complete 3-meal daily plans that satisfy complex multi-dimensional nutritional targets.

## Key Contributions
- **Cultural Knowledge Base Construction:** Utilizes Large Language Models (LLMs) to construct a robust, structured knowledge base merging unstructured Vietnamese cookbooks, the USDA Food dataset, and the Vietnamese Food Composition Table (FCT).
- **Scientifically-Grounded Profiling:** Automatically transforms user biometrics and subjective goals into quantitative macro- and micronutrient targets using established formulas (Mifflin-St Jeor equation for BMR/TDEE) and Recommended Dietary Allowances (RDA).
- **Two-Phase Meal Optimization Algorithm:** 
  1. *Macro-Focused Dynamic Programming (DP):* Prunes millions of combinations to efficiently generate candidate 3-meal plans optimized for core caloric and macronutrient targets.
  2. *Holistic Scoring:* Evaluates candidates against complete nutritional limits, heavily penalizing micronutrient deficiencies.
- **Closing the Actionability Gap:** Moves beyond mere passive "recipe matching" to active computational guidance by scaling recipe portions and programmatically supplementing side dishes to fulfill any residual nutritional deficits.

## Authors
- Phu-Trong Mai
- Gia-Huy Nguyen
- Duc-Anh Do
- Quang-Huy Tran
- Hai-Nam Pham
