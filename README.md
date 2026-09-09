# Meta Ad Performance Dashboard

![Instagram](https://github.com/shivrajsinghsisodiya9351-alt/Meta-Ad-Performance-Analysis/blob/main/Instagram.png)
![Facebook](https://github.com/shivrajsinghsisodiya9351-alt/Meta-Ad-Performance-Analysis/blob/main/Facebook.png)

*Page: Meta Ad Performance Overview*

---

## 📌 Project Description

The **Meta Ad Performance Dashboard** is a Power BI report built to analyze advertising performance across **Facebook** and **Instagram** ad campaigns. It tracks reach, engagement, and conversion metrics across ad types (Carousel, Image, Stories, Video), and breaks performance down by audience demographics, geography, time, and campaign. The dashboard helps marketing teams identify which ad formats, audiences, and time windows drive the best engagement and purchase outcomes.

---

## 📊 Key KPIs

| KPI | Value |
|---|---|
| Impressions | 216.0K |
| Clicks | 25.4K |
| Engagements | 242.6K |
| Comments | 2.6K |
| Shares | 1.3K |
| Purchases | 1.3K |
| Conversion Rate | 5.21% |
| CTR (Control) | 11.76% |
| Engagement Rate | 112.35% |
| Purchase Rate | 61.26% |
| Avg. Campaign Budget | $50.72K |
| Total Budget | $2.5M |

---

## 🔄 Process

- **Data Collection** – Ad performance data (impressions, clicks, engagements, comments, shares, purchases) collected at the campaign/ad-type level for Facebook & Instagram.
- **Data Preparation** – Structured raw data into fact/dimension format (campaigns, ad type, audience, date/time, country).
- **Data Cleaning** – Removed duplicates, standardized ad type and country labels, fixed inconsistent date/time formats.
- **Data Modeling** – Built relationships between campaign, audience, geography, and time tables; created DAX measures for CTR, Engagement Rate, Conversion Rate, and Purchase Rate.
- **Dashboard Development** – Designed a single-page interactive report with KPI cards, demographic breakdowns, weekly/hourly trends, geo map, and a calendar heatmap.
- **Testing & Deployment** – Validated KPI calculations against raw totals, tested slicer interactions (Campaign Name, Target Interests, Dynamic Slicer), and published the final .pbix.

---

## ❓ Business Questions Answered

- Which ad type (Carousel, Image, Stories, Video) drives the highest CTR and Purchase Rate?
- Which gender and age group engages most with Meta ads?
- Which countries generate the most engagement?
- How does engagement vary by week and by hour of day?
- Which weeks/days see spikes or drops in comment activity?
- How efficiently is the ad budget converting into purchases?

---

## 🔎 Observations & Data Highlights

- Female users (43%) engage slightly more than male users (22%) on comments.
- The 20–30 age group contributes the highest comment volume, tapering off after age 35.
- **Image** and **Carousel** ad types lead in impressions and clicks, while **Video** shows the highest CTR.
- Engagement shows a recurring weekly rhythm, with a spike around Event Hour 15–20.
- Purchase Rate (61.26%) is comfortably ahead of the overall Conversion Rate (5.21%), indicating strong down-funnel intent once a purchase-stage user is reached.
- Engagement Rate exceeding 100% reflects multiple engagement actions (likes, comments, shares) per impression.

---

## 📈 Visuals & Analytics Used

- KPI Cards – Impressions, Shares, Comments, Clicks, Engagements, Purchases, Conversion Rate, Avg. Campaign Budget, Total Budget, CTR, Engagement Rate, Purchase Rate
- Donut Chart – Comments by Gender
- Histogram – Comments by Age
- Stacked Bar Chart – Comments by Week (split by Ad Type)
- Line Chart – Comments by Event Hour
- Bubble Map – Comments by Country
- Calendar Matrix – Comments by Week/Day (heatmap style)
- Table – Ad Type-level breakdown (Clicks, Shares, Impressions, Engagements, CTR, Purchase Rate)
- Slicers – Campaign Name, Target Interests, Dynamic Slicer (Comments), Platform (Facebook/Instagram)

---

## 💡 Actionable Insights

- Shift more budget toward **Video** ads given its lead in CTR relative to Image/Carousel.
- Time campaign pushes around peak engagement hours (Event Hour 15–20) to maximize reach.
- Target the 20–30 age segment more heavily, as it's the primary driver of engagement.
- Double down on top-performing countries identified on the map to scale reach efficiently.
- Since Purchase Rate is high but Conversion Rate is comparatively low, focus optimization on the top-of-funnel (impressions → clicks) rather than the checkout stage.

---

## 🎯 Expected Outcomes

- Better allocation of ad budget across ad types and time windows.
- Improved targeting based on age, gender, and geography.
- Clearer visibility into which campaigns/ad formats are underperforming vs. overperforming.
- Faster, data-backed decisions for future Meta ad campaigns.

---

## ✅ Conclusion

This dashboard consolidates fragmented Meta Ads data into a single interactive view, making it easy to compare ad formats, audiences, and timing at a glance. It turns raw ad metrics into a decision-making tool — helping marketing teams spend budget where it performs best and cut down on guesswork in campaign planning.

---

## 📂 More About This Project

Want to explore the full interactive report, drill into any visual, or check the DAX measures and data model? Download the `.pbix` file from this repository and open it in Power BI Desktop.

---

## 📬 Contact Me

**Shivraj Singh Sisodiya**
Data Analyst | Power BI Developer

- Portfolio: [datascienceportfol.io/shivraj](https://datascienceportfol.io/shivraj)
- GitHub: [github.com/shivrajsinghsisodiya9351-alt](https://github.com/shivrajsinghsisodiya9351-alt)
