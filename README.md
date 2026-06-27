# 📊 Meta Ad Performance Dashboard

> **Power BI Dashboard** — A complete performance analysis of Meta (Facebook & Instagram) advertising campaigns, all in one place.

---

## 🗂️ Dashboard Pages

### 📄 Page 1 — Facebook Performance

This page provides an **overview of all metrics**, covering everything from impressions to purchases. The **Dynamic Slicer is set to "All"**, meaning it displays combined data across all ad types and campaigns.

#### 🔢 Top KPI Cards:
| Metric | Value |
|---|---|
| Impressions | 216.0K |
| Shares | 1.3K |
| Comments | 2.6K |
| Clicks | 25.4K |
| Engagements | 242.6K |
| Conversion Rate | 5.21% |
| Avg. Campaign Budget | $50.72K |
| Total Budget | $2.5M |
| CTR | 1175.57% |
| Engagement Rate | 112.35% |

#### 📊 Visuals:
- **By Gender (Donut Chart):** Gender-wise breakdown of Engagements, Impressions, Purchases, and Comments
- **By Age (Bar Chart):** Distribution of Comments, Clicks, Impressions, and Engagements across user age groups (13–50+) — the 25–35 age group is the most active
- **By Weekly (Stacked Bar):** Weekly performance of Carousel, Image, Stories, and Video ad types from Week 18 to 32
- **By Country (Map):** Geographic view of ad reach across different countries around the world
- **By Calendar:** Month-wise weekly calendar with active days highlighted
- **By Event Hour (Line Chart):** Pattern of Comments, Clicks, Impressions, Engagements, Purchases, and Shares across different hours of the day
- **Ad Type Table:** Detailed breakdown of Image, Carousel, Stories, and Video — including Clicks, Shares, Impressions, Engagements, CTR, and Purchase Rate

#### 🖼️ Dashboard Preview:

![Meta Ad Performance Dashboard - Page 1](https://github.com/shivrajsinghsisodiya9351-alt/Meta-Ad-Performance-Analysis/blob/main/Facebook.png)

---

### 📄 Page 2 — Instagram Performance

This page focuses **exclusively on the Comments metric**. The **Dynamic Slicer is set to "Comments"**, so all charts are filtered from a comments perspective.

#### 🔢 Top KPI Cards (with Comments Filter):
| Metric | Value |
|---|---|
| Impressions | 123.8K |
| Shares | 682.0 |
| Comments | 1.5K |
| Clicks | 14.7K |
| Engagements | 139.2K |
| Conversion Rate | 4.82% |
| Avg. Campaign Budget | $50.72K |
| Total Budget | $2.5M |
| CTR | 1186.21% |
| Engagement Rate | 112.41% |

#### 📊 Visuals:
- **Comment by Gender (Donut Chart):** Comments share across three gender segments — Male (28%), Female (37%), and All (36%)
- **Comment by Age (Bar Chart):** Age-wise comment distribution — peak comments observed in the 20–35 age group
- **Comment by Weekly (Stacked Bar):** Weekly comments for Carousel, Image, Stories, and Video from Week 18 to 32
- **Comment by Country (Map):** Geographic spread of comments across different countries
- **Comment by Calendar:** Month-wise weekly calendar with active days
- **Comments by Event Hour (Line Chart):** A noticeable spike in comments after 8 PM — useful for identifying the best posting time
- **Ad Type Table (Comments filtered):** Detailed view of Carousel, Stories, Video, and Image — with CTR and Purchase Rate

#### 🖼️ Dashboard Preview:

![Meta Ad Performance Dashboard - Page 2 (Comments)](https://github.com/shivrajsinghsisodiya9351-alt/Meta-Ad-Performance-Analysis/blob/main/Instgram.png)

---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design & visualization |
| **Meta Ads Data** | Facebook & Instagram campaigns |
| **Bing Maps** | Geographic distribution visual |
| **DAX** | Calculated measures (CTR, Engagement Rate, etc.) |

---

## 📁 Repository Structure

```
📦 meta-ad-dashboard/
├── 📊 MetaAdDashboard.pbix       # Power BI file
├── 🖼️ dashboard_all.png          # Page 1 screenshot
├── 🖼️ dashboard_comments.png     # Page 2 screenshot
└── 📄 README.md                  # This file
```

---

## 🚀 How to Use

1. **Clone** this repository
   ```bash
   git clone https://github.com/your-username/meta-ad-dashboard.git
   ```

2. **Open** `MetaAdDashboard.pbix` in Power BI Desktop

3. **Connect** your Meta Ads data source (or use sample data)

4. **Explore** different metrics by adjusting the Dynamic Slicer filters

---

## 📌 Key Insights

- 🎯 **Stories** ad type has the **highest CTR** (1175.06%)
- 👥 **Female audience** leads slightly in comments (37%)
- ⏰ Comments and engagement **peak between 8–10 PM**
- 📅 **Weeks 22–24** showed the best overall performance
- 💰 **Image ads** have the highest Purchase Rate (57.35%)

---

## 👤 Author

**[Shivraj Singh Sisodiya]**
- LinkedIn: [your-linkedin](https://www.linkedin.com/in/shivraj-singh-sisodiya/)

> **Power BI Dashboard** — A complete performance analysis of Meta (Facebook & Instagram) advertising campaigns, all in one place.


> ⭐ If this dashboard was helpful, please consider giving it a **Star**!
