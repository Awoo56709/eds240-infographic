# Recipe Popularity Infographic
### *Bon Data-tite*  
**Author:** Joshua Ferrer‑Lozano  
**Date:** March 9, 2026

## **Overview**

This repository contains the full workflow, code, and final deliverables for my EDS 240 Final Project:  
**a data‑driven infographic exploring what makes a recipe popular on Food.com.**

Using a dataset of more than 188,000 recipes published between 1999 and 2016, I examined how time, complexity, ingredients, and nutrition shape recipe engagement. The final infographic synthesizes these insights into a cohesive, editorial‑style visual narrative.

## **Repository Structure**

---

eds240-infographic/
│
├── data/
│   └── recipes_reviews/        # Raw Food.com  dataset
│
├── images/
│   └── infographic.png         # Final infographic (exported)
│
├── drafting-viz-cleaned.qmd    # Full blog post + code
├── README.md                   # This file
└── LICENSE

---

## **Final Deliverables**

### **Infographic**  
A multi‑panel visual story designed in a “menu” metaphor, featuring:

- The 30‑Minute Sweet Spot  
- Complexity by Rating Tier  
- Ingredient Identity Sunburst  
- Sugar & Popularity Scatterplot  
- Radial Calories Over Time  

The infographic is included in the `images/` folder and embedded in the blog post.

### **Blog Post**  
A 1–2 page science‑communication write‑up describing:

- Motivation & questions  
- Data source  
- Design decisions  
- Ten design elements  
- Final insights  

Rendered via Quarto and published on my personal website.

---

## **Data Source**

Food.com Recipe & Review Dataset (1999–2016)  
Originally compiled by Majumder et al. (2019).  
Includes metadata on ingredients, nutrition, ratings, and user engagement.

---

## **Reproducibility**

All visualizations were generated using:

- **R** (tidyverse, ggplot2, plotly)  
- **Quarto** for rendering  
- **Affinity Designer** for optional layout refinements  

The full code is included in a single foldable chunk at the bottom of the blog post.

---

## **Acknowledgments**

Thanks to the EDS 240 instructional team: 
- Samantha Csik and Annie Adams