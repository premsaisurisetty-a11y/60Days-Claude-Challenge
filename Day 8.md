# Day 8 – Environmental Health Analyzer Dashboard

## Challenge Topic

Context Engineering + AI-Powered Dashboard Generation

## Objective

Build a complete Environmental Health Analyzer dashboard using Claude that combines air quality, water quality, health insights, visual analytics, and personalized recommendations into a single interactive application.

---

# Prompt Used

Act as a Senior Data Analyst, Environmental Researcher, UX Designer, and Frontend Dashboard Developer.
Create a Claude Artifact called:
🌍 Personal Environmental Health Analyzer
DATA RULES
If a dataset is provided, use it. If no dataset is provided, automatically search the web for the latest AQI and water-quality data for the user's current city/location. If location is unavailable, ask for the city name first. Use the most recent available data, cite sources, clean the data, handle missing values, and validate quality before analysis.
ANALYSIS
Generate: cleanest city, most polluted city, highest AQI city, lowest AQI city, average AQI, number of cities analyzed, trends, anomalies, most surprising observation, executive summary.
INTERACTIVE DASHBOARD
Create a fully interactive Claude Artifact with:
📊 Key Metrics: average AQI, highest AQI city, lowest AQI city, number of cities analyzed, environmental health score.
📈 Visualizations: AQI comparison chart, PM2.5 comparison chart, PM10 comparison chart, city ranking chart, AQI distribution chart.
🎛 Interactive Filters: city selector, AQI range filter, pollutant selector, health-risk filter, date filter (if available), city comparison mode.
📋 City Detail Cards: AQI, PM2.5, PM10, air-quality category, health score, water-quality score.
🚦 AQI Categories: Good (Green), Satisfactory (Light Green), Moderate (Yellow), Poor (Orange), Very Poor (Red), Severe (Dark Red).
ENVIRONMENTAL HEALTH ANALYSIS
For the selected city explain AQI impact on lungs, sleep, energy levels, exercise performance, long-term health, and water-quality impact on hair fall, hair dryness, scalp health, skin dryness, acne, and sensitive skin.
Use risk indicators: 🟢 Low, 🟡 Moderate, 🔴 High.
PERSONAL REPORT CARD
Generate an Environmental Health Score (0–100) with breakdowns for Air Quality Score, Water Quality Score, and Overall Environmental Score.
Assign grades for Air Quality (A–F), Water Quality (A–F), Hair Risk, and Skin Risk.
INSIGHTS PANEL
Include: top 3 cleanest cities, top 3 most polluted cities, biggest anomaly, most surprising observation, recommended actions.
PERSONALIZED RECOMMENDATIONS
Provide: daily actions, indoor air improvements, outdoor activity guidance, hair-care recommendations, skin-care recommendations, water-quality improvement suggestions.
DESIGN
Modern, professional, mobile responsive, dark theme, smooth animations, premium UI, clean typography, dashboard-style layout, highly visual, colourful, LinkedIn-shareable.
OUTPUT
Generate a complete downloadable HTML application that is fully responsive and ready to save as index.html.
IMPORTANT
Do not provide code snippets. Create a complete interactive Claude Artifact with working charts, filters, cards, insights, report cards, and dashboards that users can interact with directly.

---

# Project Generated

##  Personal Environmental Health Analyzer

An interactive dashboard that analyzes environmental conditions across multiple Indian cities and provides actionable health recommendations.

### Key Features

###  Dashboard Metrics

* Average AQI
* Highest AQI City
* Lowest AQI City
* Cities Analyzed
* Environmental Health Score

###  Visual Analytics

* AQI Comparison Chart
* PM2.5 Analysis
* PM10 Analysis
* City Ranking Visualization
* AQI Distribution Radar Chart
* Environmental Trend Graphs

###  Interactive Filters

* City Selection
* Pollutant Selection
* AQI Range Filtering
* Health Risk Filtering
* City Comparison Mode

###  City Analysis

* AQI Score
* PM2.5 Levels
* PM10 Levels
* Water Quality Score
* Water Hardness
* Environmental Health Rating

###  Health Impact Assessment

Air Quality Impact:

* Lung Health
* Sleep Quality
* Energy Levels
* Exercise Performance
* Long-Term Health Risk

Water Quality Impact:

* Hair Fall Risk
* Hair Dryness
* Scalp Health
* Skin Dryness
* Acne Risk
* Sensitive Skin Risk

###  Environmental Report Card

* Air Quality Score
* Water Quality Score
* Overall Environmental Score
* Grade System (A–F)
* Risk Assessment

###  Insights Panel

* Top 3 Cleanest Cities
* Top 3 Most Polluted Cities
* Biggest Anomaly
* Executive Summary
* Trend Analysis

###  Personalized Recommendations

* Daily Actions
* Indoor Air Improvements
* Outdoor Activity Guidance
* Hair Care Recommendations
* Skin Care Recommendations
* Water Quality Improvements

---

# Screenshots

## Dashboard Overview

<img width="632" height="731" alt="Screenshot 2026-06-08 123428" src="https://github.com/user-attachments/assets/5fac5390-c858-4643-a370-fbda94816875" />

## AQI & Pollution Analysis

<img width="638" height="797" alt="Screenshot 2026-06-08 124124" src="https://github.com/user-attachments/assets/7fe90f56-191a-4411-9dbb-6d696411d256" />


## City Ranking & Distribution

<img width="628" height="642" alt="Screenshot 2026-06-08 124046" src="https://github.com/user-attachments/assets/38cb73d2-f9e9-47d8-813a-572076b7de7e" />

## City Comparison Cards

<img width="645" height="807" alt="Screenshot 2026-06-08 123655" src="https://github.com/user-attachments/assets/116a22d6-45e0-4cb2-a9a5-98b608f1c526" />


## Health Impact Analysis

<img width="645" height="776" alt="Screenshot 2026-06-08 123729" src="https://github.com/user-attachments/assets/f8cd0c9a-465a-4cf6-8628-d2c2d4651e70" />

## Environmental Report Card

<img width="620" height="746" alt="Screenshot 2026-06-08 123805" src="https://github.com/user-attachments/assets/cb5cd787-14a2-4076-a268-73719c3f11db" />

## Insights & Findings

<img width="636" height="798" alt="Screenshot 2026-06-08 123846" src="https://github.com/user-attachments/assets/a9d56a55-a4e5-4993-b9be-e8bcdf7ebd08" />


## Trend Analysis

<img width="618" height="361" alt="Screenshot 2026-06-08 123919" src="https://github.com/user-attachments/assets/3dcdd547-7391-4e2c-ac76-8bf9074a286f" />


## Daily Recommendations

<img width="615" height="359" alt="Screenshot 2026-06-08 123938" src="https://github.com/user-attachments/assets/8532c53d-39e6-40c8-9bd4-9c228e81d6df" />

## Hair, Skin & Water Recommendations

<img width="634" height="674" alt="Screenshot 2026-06-08 124012" src="https://github.com/user-attachments/assets/101e8502-725f-4284-bcdb-634015d46630" />


---

# Key Learnings

### 1. Context Creates Better Results

Providing detailed context allowed Claude to generate a complete dashboard instead of a simple report.

### 2. AI Can Build End-to-End Applications

Claude generated an entire dashboard including analytics, charts, filters, health insights, and recommendations.

### 3. Structured Prompts Matter

Clearly defining sections, outputs, UI requirements, and analysis requirements significantly improved the quality of the result.

### 4. AI Can Combine Multiple Roles

The prompt combined:

* Data Analyst
* Environmental Researcher
* UX Designer
* Frontend Developer

This resulted in a much more sophisticated application.

### 5. Dashboards Improve Data Understanding

Visual analytics made environmental data easier to interpret compared to raw numbers.

---

# Biggest Insight

The quality of AI-generated applications depends heavily on the level of context and specificity provided in the prompt. Detailed instructions transformed Claude from a chatbot into a full-stack dashboard generator.

---

# Outcome

Successfully generated a complete Environmental Health Analyzer dashboard featuring:

* Real-world environmental metrics
* Interactive data visualizations
* Health impact assessments
* Environmental scorecards
* Personalized recommendations
* Professional dashboard UI

This demonstrated the power of Context Engineering in building practical AI-powered applications.

---

## Challenge Progress

Day: 8/60
