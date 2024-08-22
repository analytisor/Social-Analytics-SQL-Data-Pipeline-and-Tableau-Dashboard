## **Visualization Overview Using Tableau**

This Tableau visualization was designed with a modular approach, starting with an **Overview** page and extending into individual pages that delve deeper into specific topics. These individual pages provide rich storytelling through detailed charts focused on unique aspects such as posts, geographic locations, creator tiers, and more.

The core objective was to empower the end user with the ability to slice and dice data across multiple dimensions, ensuring they could answer specific business questions efficiently. To achieve this, **smart navigational dropdowns** were incorporated, allowing for dynamic exploration across various elements. These include:

![Navigation Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/tableau_dropdown_filterations.png)

- **Activation Type:** Differentiates between _New Activations_ (first-time creators for a brand) and _Reactivations_ (creators who have worked with the same brand before).
- **Creator Tier:** Groups creators by their influence and follower count:
  - **Mega:** 1M+ followers
  - **Macro:** 200K - 1M followers
  - **Mid-Tier:** 60K - 200K followers
  - **Micro:** 10K - 60K followers
  - **Nano:** Less than 10K followers
- **Campaign Name:** Filters by the name of campaigns conducted throughout the year.
- **Network:** Specifies the social network where the activity occurred, such as Instagram, TikTok, YouTube, and others.
- **Post Type:** Differentiates the type of content, such as Instagram Posts, Instagram Reels, Instagram Stories, TikTok videos, or YouTube mentions.
- **Mall Location:** Identifies the exact mall locations across the US that the original posts were intended for.

### **Unique Features**

- **Date Range Selector:** Users can narrow the data to any sequence of days across the calendar year for highly customizable date range analysis.
- **Date Shortcuts:** Pre-built parameters enable quick navigation to frequently analyzed date ranges, such as "This Week," "Last Week," "This Month," and "Last Month."
- **Chart Timeframe Selector:** Allows users to adjust the granularity of the charted data by selecting different timeframes—daily, weekly, monthly, or yearly—so the charts adapt to provide the most effective user experience based on the selected date range.

### **Calculated Field Working with a Parameter to create the shortcut for 'Date Range Selector'**

![Date_selector Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/selected_date_range.png)

### **Chart Dimension Broken By Month**

![Monthly Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/engagement_chart_by_month.png)

### **Chart Dimension Broken By Week**

![Weekly Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/engagement_chart_by_week.png)

### **Chart Dimension Broken By Day**

![Daily Screenshot](https://github.com/analytisor/Social_Analytics_Dashboard/blob/main/engagement%20chart%20by%20day.png)

This comprehensive and interactive approach allows end users to explore social media performance data with ease, facilitating better decision-making and deeper insights into creator performance and campaign success.

**To access the actual interactive Tableau Dashboard:** [Link Here](https://public.tableau.com/views/SOCIAL_MEDIA_OVERVIEW/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
