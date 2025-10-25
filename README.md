# nyc-airbnb-blogpost

# What Drives Airbnb Prices in New York City?
*Data-driven insights for smarter pricing decisions*

**Authors:** Yinuo Zhao & Guochen Li  
*University of Helsinki – Faculty of Science*

---

## 🏙️ Introduction

New York City — one of the world’s most dynamic and competitive short-term rental markets.  
Thousands of Airbnb listings compete daily for guests' attention. But what really drives the nightly price of a stay?

This project takes a closer look at Airbnb data from across New York City to uncover **what factors truly influence price** — and how both hosts and guests can benefit from these insights.

Our goal was simple:
- 🎯 **For hosts:** help set fair, competitive prices using real data.  
- 🏡 **For guests:** help identify listings that match preferences and budget.  

---

## 📊 The Data Behind the Story

We started from the **New York City Airbnb Open Data** available on Kaggle.  
Each record represents one Airbnb listing — including its location, room type, availability, host information, and nightly price.

Before analysis, we ensured that the dataset reflected *genuine and valid* Airbnb offers.  
We removed:
- Listings without price information  
- Clearly unrealistic prices (e.g., \$0 or over \$10,000)  
- Inactive or duplicate entries  

After cleaning, we focused on **real, active listings across all NYC boroughs**, allowing us to analyze fair and balanced pricing patterns.

---

## 💵 Price Distribution: What Does the Market Look Like?

![Price Distribution of Airbnb Listings in NYC](price_distribution.png)

Most listings in New York City fall between **\$50 and \$200 per night**, with a small group of luxury apartments charging above \$500.  
This means that the market is dominated by affordable short-term stays — but the high-end segment still drives a long tail of expensive offers.

The distribution is strongly **right-skewed**, meaning that while most homes are reasonably priced, a few extremely expensive listings pull the average upward.

---

## 🗺️ Location Matters: Mapping Airbnb Prices Across NYC

![Geospatial Heatmap](nyc_airbnb_heatmap.png)

We visualized Airbnb prices using a **geospatial heatmap**, revealing a clear pattern:
- Manhattan shines the brightest — prices are the highest near Times Square and Downtown.  
- Brooklyn follows, with popular areas like Williamsburg and DUMBO commanding strong prices.  
- Outer boroughs like Queens and the Bronx tend to be more affordable.

This shows how geography alone can explain a major portion of pricing variation.  
If you’re a host, *location is your first advantage*.  

---

## 🏠 What Else Drives Price?

After analyzing tens of thousands of listings, three main drivers emerged:

| **Factor** | **Effect on Price** |
|-------------|--------------------|
| **Room Type** | Entire apartments are 2–3× more expensive than shared rooms. |
| **Neighbourhood Group** | Manhattan and central Brooklyn have consistently higher rates. |
| **Host Activity** | Experienced hosts with more listings tend to price more competitively. |
| **Availability (days/year)** | More available properties are often slightly cheaper. |

In other words, **location and room type dominate**, while host activity and listing availability add nuance.

---

## 📈 How These Factors Interact

![Feature Importance](feature_importance.png)

Our model helped visualize how each factor “moves” the average price:  
- Properties located closer to the city center predict higher nightly rates.  
- Room type heavily skews price — entire homes or apartments dominate premium categories.  
- Host experience (number of listings and reviews) also plays a secondary role.

Even without technical details, one insight is clear:  
> **The Airbnb market rewards accessibility, privacy, and trust.**

---

## 💬 Key Insights & Takeaways

- 🏙️ **Location and room type** are the strongest drivers of price.  
- 📍 **Proximity to Manhattan** significantly raises the nightly rate.  
- 👤 **Host experience and reputation** subtly influence pricing trends.  

These findings can guide:
- **Hosts:** to set competitive, fair prices based on their area and room type.  
- **Guests:** to identify listings that balance cost and convenience.  
- **Platforms:** to support more transparent and data-informed pricing models.  

---

## 🔮 Looking Ahead

Our next steps include:
- Exploring **seasonal and temporal** patterns (e.g., holiday price spikes).  
- Extending the analysis to **other major cities** for comparison.  
- Developing a simple **interactive dashboard** that helps hosts and guests simulate price scenarios.

---

## 🌟 Final Thoughts

Data doesn’t just describe the Airbnb market — it empowers better decisions.  

Understanding what drives price helps hosts grow sustainably and helps guests make smarter travel choices.  
Together, this makes the rental ecosystem more transparent, fair, and efficient.

---

*This project was developed as part of the Data Science course at the University of Helsinki, Faculty of Science (2025).*  
