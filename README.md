# 📊 Push Notification Analysis

This repository contains analysis notebooks for evaluating and optimizing the performance of push notifications and related user navigation behavior within the Braze platform.

## 🧩 Repository Structure

```
.
├── Push Analysis.ipynb
├── Braze Link Navigation.ipynb
└── README.md
```

### 1. `Push Analysis.ipynb`
This notebook explores **push notification performance metrics** to identify patterns that drive engagement and conversion.  
It typically includes:
- **Data preprocessing:** cleaning message titles, bodies, and timestamps.
- **Exploratory analysis:** open rates, text formatting success, push image colorfulness.  
- **Segmentation:** comparing performance across message types, audiences, or time windows.  
- **Visualization:** trends over time, device or platform differences, and message type heatmaps.  
- **Insights:** highlighting underperforming campaigns and suggesting content or timing adjustments.

### 2. `Braze Link Navigation.ipynb`
This notebook analyzes **link behavior and destination tracking** from Braze push campaigns to understand user journey and retention.  
It may include:
- **Mapping Braze campaign links** to final destination URLs using link resolution or UTM parsing.  
- **Attribution modeling:** measuring which links or push types drive the most conversions.  
- **Error and redirect detection:** identifying broken or misdirected campaign links.  

---

## 🧠 Key Objectives

- Evaluate how **push notification content and timing** influence engagement metrics.  
- Track **URL destinations** to measure user flow and effectiveness of in-app vs. external links.  
- Provide **data-driven recommendations** for improving Braze campaign performance.

---

## 📈 Expected Outputs

- Tables summarizing **open rate correlations with 20+ variables**.  
- Charts comparing **performance across campaigns**.
- Exportable CSVs or plots for reporting to marketing or product teams.  
- Final insights section proposing **changes to push frequency, content, or targeting.**

---

## 🧩 Future Improvements

- Integrate automated **Braze API pulls** for daily refresh.  
- Build a **dashboard** for live visualization.  
- Implement **A/B testing logic** to evaluate notification variants.  
- Use **NLP sentiment analysis (TextBlob)** on message content to correlate tone with engagement.
