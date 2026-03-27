# retail-growth-opportunities-and-revenue-drivers-metabase
End-to-end retail analytics project using SQL and Metabase to analyse customer behaviour, revenue drivers, and identify actionable growth opportunities.
Retail Performance & Growth Opportunities

Overview
This project presents an end-to-end retail analytics solution designed to evaluate business performance and identify actionable growth opportunities. Using SQL and Metabase, the analysis moves beyond descriptive reporting to a structured growth driver framework, enabling data-driven strategic decision-making.

The work is divided into two parts:

Part I – Performance Analysis: Answering key business questions on customer behaviour and category growth

Part II – Growth Model & Strategy: Decomposing revenue into drivers and identifying scalable opportunities

Business Objective

The objective of this project is to support senior stakeholders in answering:

What is driving revenue performance?

Where are the key growth opportunities?

How can customer behaviour be leveraged to increase sales?

Dataset & Data Preparation

The dataset consists of transactional retail data including:

Customer-level transactions

Basket-level purchases

Product categories (L2)

Sales channels

Country information

Data Cleaning Steps

To ensure analytical accuracy:

Removed transactions with non-positive quantities

Excluded records with negative sales values

Filtered out incomplete reporting period (May 2024)

Ensured consistent aggregation at basket and customer level

Part I – Performance Analysis

This section focuses on answering targeted business questions.

Key Questions Addressed

What share of customers transacted in more than one category (Dec 2022)?

Which day of the week had the highest customer activity (Dec 2022)?

Which L2 category has shown the fastest growth since Jan 2022?

Key Insights

Nearly half of customers (~48%) engaged across multiple categories, indicating strong cross-sell potential

Saturday emerged as the peak trading day for customer activity

Several L2 categories demonstrated high growth trajectories, highlighting emerging demand segments

Part II – Growth Model & Strategic Analysis

A structured growth framework was developed to diagnose performance:

Revenue Decomposition

Revenue was analysed as a function of:

Customer volume

Purchase frequency (transactions per customer)

Basket value (ATV)

Basket size (items per basket – IPB)

Customer Dynamics

Monthly breakdown of new, returning, and churned customers

Identification of retention pressure and acquisition trends

Segmentation Analysis

Performance evaluated across:

Countries

Sales channels

Product categories

Opportunity Identification

Category Opportunity Matrix (Growth vs Size) to identify high-potential segments

Cross-category purchasing behaviour to assess upsell potential

Channel-level monetisation (Sales per Customer) to identify high-value segments

Key Business Insights

Revenue growth is primarily driven by customer acquisition, with limited expansion in basket size

Cross-category engagement remains moderate, indicating untapped bundling opportunities

Certain categories exhibit high growth but low market share, representing scalable opportunities

Signs of retention pressure in later periods suggest the need for customer lifecycle strategies

Channel performance varies significantly in terms of customer value (SPC)

Strategic Recommendations
1. Scale High-Growth Categories

Invest in categories with strong growth but lower current share to maximise future revenue potential.

2. Improve Customer Retention

Introduce loyalty programs and targeted promotions to reduce churn and increase repeat purchases.

3. Increase Basket Size

Implement bundling strategies and cross-category promotions to improve Items per Basket (IPB).

4. Optimise Channel Strategy

Focus on channels with higher customer value while improving monetisation in underperforming channels.

Dashboard Design & Interactivity

The Metabase dashboards were designed with a clear storytelling structure:

Big Picture – KPIs and overall performance

Drivers – Revenue decomposition and trends

Segmentation – Country, channel, and category analysis

Opportunities – Growth matrix and customer behaviour

Action – Business recommendations

Features

Interactive filters (date, country, channel, category)

Dynamic exploration of growth drivers

Clean and executive-level visualisation design

Tools & Technologies

SQL (Athena / Presto) – Data extraction and transformation

Metabase – Dashboarding and visualisation

GitHub – Documentation and project presentation