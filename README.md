# Topsis-on-Text-Sentence-Similarity
# Assignment 3
# TOPSIS Model Evaluation

## Overview
This repository contains an analysis of different models using the **TOPSIS** method (Technique for Order of Preference by Similarity to Ideal Solution). The models evaluated are:
- **SBERT**
- **USE**
- **SimCSE**
- **DistilBERT**

## Methodology
The TOPSIS method evaluates each model based on the following criteria:
- **Accuracy** (Higher is better)
- **Inference Time** (Lower is better)
- **Memory Usage** (Lower is better)

The models are ranked based on the weighted distances from the ideal best and worst solutions.

## Results

| Model       | Accuracy | Inference Time (ms) | Memory Usage (MB) | TOPSIS Score |
|-------------|----------|---------------------|-------------------|--------------|
| SimCSE      | 0.88     | 8                   | 120               | 0.802546     |
| DistilBERT  | 0.80     | 7                   | 110               | 0.780908     |
| USE         | 0.82     | 10                  | 140               | 0.373025     |
| SBERT       | 0.85     | 12                  | 150               | 0.148493     |



## Conclusion
Based on the analysis, **SimCSE** is the best model according to the TOPSIS ranking, followed closely by **DistilBERT**. **SBERT** ranks the lowest due to its higher inference time and memory usage.

## References
- [TOPSIS Methodology](https://en.wikipedia.org/wiki/TOPSIS)
