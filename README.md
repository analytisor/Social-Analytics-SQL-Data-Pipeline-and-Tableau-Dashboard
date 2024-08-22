## **Project: Revamping Social Analytics Dashboard with Advanced SQL & Tableau**

**Client:** Influencer Marketing Software Company, ASPIRE  
**Tools Used:** PostgreSQL, Redash, Tableau  
**Tableau Dashboard Overview Explanation:** [Link Here](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/Tableau_Visualization_Overview.md)  
**Interactive Tableau Dashboard:** [Link Here](https://public.tableau.com/views/SOCIAL_MEDIA_OVERVIEW/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
**In-depth Explanation of SQL Query:** [Link Here](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/SQL_Overview.md)  
**The Actual SQL Query:** [Link Here](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/social_analytics_query.sql)

---
![Dashboard Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/overview_dashboard_screenshot.png)
---
### **Project Summary**

**Challenge:**  
ASPIRE was at risk of losing a key client due to inadequate day-to-day reporting in its main reporting panel. Without actionable insights, client satisfaction and retention were in jeopardy.

**Solution:**  
I conducted an analysis in SQL to uncover insights on creator types, sign-up registrations, and campaign performance. Over six weeks, I independently audited the company's legacy data sources, revised the data model, ensured accuracy in new data pipelines, and built a Tableau dashboard to visualize trends related to Content Deliverable Status, Post Types, Creator Types, and Engagement Types. The insights and recommendations were aimed at the retail and marketing teams to improve day-to-day campaign performance and creator selections.

**Impact:**  
- **Client Renewal:** The improved reporting capabilities led to a successful agreement renewal with the client.  
- **Internal Recognition:** My work resulted in integration with ASPIRE’s engineering team, where I audited data pipelines in BigQuery and took on additional data visualization responsibilities.

---

### **Metrics and Dimensions**

**Key Metrics:**
- Count of Creators  
- Count of Content  
- Impressions  
- Engagement (Likes, Comments, Saves, Shares)  
- Engagement Rate (%)

**Key Dimensions:**
- Creator Tiers (Macro, Micro, Mid-Tier, Nano)  
- Deliverable Types (LIVE, Approved, Content Review, Locked)  
- Network (Instagram, TikTok, YouTube)  
- Activation Types (New vs. Returning)  
- Campaign Name  
- Mall Locations  
- Date Shortcuts (This Week, Last Week, This Month, Last Month, etc.)  
- Chart Timeframes (Daily, Weekly, Monthly, Annually)

---

### **Summary of Insights**

- **Engagement Per Post:** Despite a 45% increase in 'LIVE' creators between June 2024 and March 2024 and a steady number of posts per creator (1.16 vs. 1.15), there has been a significant 70%+ drop in engagement per post. This decline is primarily attributed to creators on TikTok.
- **Instagram Mid-Tier Creators:** Although Mid-Tier creators on Instagram made up less than 10% of all creators for the network in the first six months of 2024, their engagement rate of 5.85% far exceeds that of Micro and Nano influencers, generating over 7X more engagements than Nano and Micro creators combined.

---

### **Recommendation and Next Steps**

- **Investigate Creator Segments and Content Strategy:** Explore whether the issue lies in the recruitment of creators or the content strategy being promoted.
- **Micro-Tier Creator Budget Allocation:** Examine the content niches and diversification of Micro-Tier creators. Consider dedicating more budget toward this segment, as they are more affordable and could offer a higher return.
- **Expand Visualizations:** Continue expanding the dashboard to include more in-depth visualizations across different performance aspects, including post breakdowns, locations, and more.


