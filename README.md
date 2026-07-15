Corporate Travel Cohort & Retention Intelligence Dashboard
📌 Project Overview
This repository features an enterprise-grade, multi-view Power BI dashboard designed to track, analyze, and optimize corporate travel customer behavior, booking lifecycles, and financial metrics.

By utilizing advanced cohort analysis, user retention modeling, and behavioral segmentation, this dashboard transforms raw booking transactions into strategic insights. It enables business stakeholders to evaluate long-term client retention, isolate purchasing patterns, and identify churn risk across travel categories (Hotels and Flights).

📂 Dashboard Views & Architecture
The analytical suite is structured across four distinct reporting views, each addressing a critical pillar of customer lifetime value (LTV):

1. Cohorts by Registration Months
Purpose: Monitors long-term value retention by tracking specific acquisition cohorts over a multi-year horizon.

Key Components:

Active Customers: Historical segmentation of client tiers (BASIC vs. PRO).

Sales Revenue Matrix: Tracks monthly gross sales contributions (utilizing standard Indian formatting) based on signup cohorts.

Corporate Count Matrix: Measures the volume of active enterprise clients operating over a longitudinal timeline.

2. Cohorts by Customer Type & Product
Purpose: Evaluates comparative customer quality and efficiency using normalized metrics.

Key Components:

Absolute vs. Relative Sales: Side-by-side matrices comparing raw cash flow volume against indexed purchase-power growth.

Absolute vs. Relative Corporate Count: Tracks the physical volume of active corporations against normalized customer retention decay.

3. Cohorts Booking
Purpose: A granular, high-frequency operational view tracking micro-behaviors.

Key Components:

Day-of-Month Booking Lifecycle: Maps booking activities for each day of a billing cycle (Invoice Month) to evaluate transactional velocity and detect mid-month spikes.

Filters by LOB (Line of Business), Official vs. Personal Booking Types, and Total Bookings/Metrics.

4. Search-to-Book Behavioral Cohorts
Purpose: A diagnostic behavioral tool isolating drop-off and engagement gaps.

Key Components:

Corporate Intent Analysis: Isolates lists of specific business clients matching critical drop-off profiles, including:

Search Not Search: Clients active in the current month who did not search in the following month (retention warning).

Book Not Book: Clients who booked this month but failed to return next month (immediate churn warning).

Search Not Book: High-intent clients who searched for options but did not finalize a booking (conversion friction).

💡 Key Business & Analytical Insights
The High-Value "Whale" Phenomenon: In the registration cohort views, older cohorts (such as April 2018) generate incredibly high and consistent revenue despite having a very low absolute customer count. This points to the high loyalty of a small number of enterprise accounts.

Growth Velocity in Early Cohorts: The Relative Sales matrix reveals that while the Feb 2022 cohort starts larger in volume, the Jan 2022 cohort scales up its spending power at a much faster rate (jumping from an index of 4.00 to 16.31 by month two).

Friction and Drop-off Tracking: The Search Not Book segmentation identifies high-intent corporate buyers who are dropping off before finalizing reservations, allowing account managers to run targeted re-engagement campaigns for those accounts.

🛠️ Tech Stack & Skills Demonstrated
Data Visualization: Microsoft Power BI Desktop

Data Modeling & Analytics: Cohort grouping logic, time-series indexing, absolute vs. relative calculations.

Data Engineering & ETL: Data cleaning, date/time formatting, database structuring, and aggregation logic.

Business Intelligence: Customer Lifetime Value (LTV) forecasting, churn diagnostics, and retention rate modeling.

🔒 Data Privacy & Compliance Note
To comply with corporate NDAs and data governance policies, all sensitive company branding elements have been removed or anonymized, and all underlying metrics have been masked, aggregated, or randomized to protect proprietary business data.

✉️ Contact & Collaboration
Developer: Saurabh Gaud

Role: Data Analyst

Skills: SQL | Python | Power BI | Tableau | Advanced Excel

Get in Touch: Feel free to reach out via GitHub or connect on LinkedIn to discuss my work, analytical methodologies, or open opportunities!
