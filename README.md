# CRM Sales Opportunities Performance Analysis  
## Table of Content 
A Power BI Project Title CRM Sales Opportunities Performance Analysis: Evaluating Team Effectiveness, Agent Productivity, Product Performance, and Revenue Trends
## Project Scope 
This analysis was conducted to evaluate the effectiveness of the sales organization by examining sales opportunities, revenue generation, conversion rates, team performance, agent productivity, product success, and quarterly trends.
The objective was to identify:
-	Top-performing sales teams 
-	High and low-performing sales agents 
-	Best-selling products 
-	Revenue trends over time 
-	Conversion efficiency across the sales pipeline 
The analysis provides management with actionable insights to improve revenue growth, optimize sales resources, and enhance overall sales effectiveness.
________________________________________
## Business Problem 
Organizations generate numerous sales opportunities, but not all opportunities result in successful conversions.
Management needs answers to the following questions:
1.	Which sales teams contribute most to revenue? 
2.	Which sales agents are driving business performance? 
3.	Which products have the highest success rates? 
4.	How effective is the sales pipeline? 
5.	Is revenue improving over time? 
6.	Where should management focus improvement efforts? 
________________________________________
## Aim of the Project 
To analyze CRM sales opportunity data and uncover insights that improve sales performance, increase conversion rates, and maximize revenue generation.
________________________________________
## Objectives of the Analysis 

**Revenue Analysis**

-	Measure total revenue generated 
-	Identify top-performing sales teams 
-	Identify top-performing sales agents 

**Sales Effectiveness**

-	Calculate win rates 
-	Analyze won versus lost opportunities 
-	Evaluate pipeline conversion efficiency 

**Product Analysis**

-	Determine products generating the highest revenue 
-	Identify products with the strongest win rates 

**Trend Analysis**

-	Analyze quarterly performance 
-	Identify revenue growth patterns 
________________________________________
## Use Case 
This project provides value to multiple stakeholders across the organization. Each stakeholder uses the dashboard differently to support decision-making.

**1. Board of Directors**

**How It Helps**

The board focuses on the overall health and growth of the business.

**Key Questions Answered**
- Is revenue growing?
- Are sales targets being achieved?
- Which products drive business growth?
- Which teams contribute most to revenue?
- Is the sales organization becoming more effective?

**Benefits**

- Strategic decision-making
- Revenue growth monitoring
- Investment planning
- Performance oversight

**Dashboard Areas Used**

- Total Revenue
- Quarterly Growth
- Win Rate
- Revenue Trends

**2. Chief Executive Officer (CEO)**
**How It Helps**

The CEO needs a high-level view of company performance.

**Key Questions Answered**
- How is the sales organization performing?
- Are sales efforts translating into revenue?
- Which business areas need attention?

**Benefits**

- Business performance visibility
- Strategic planning
- Growth management

**Dashboard Areas Used**
- Executive KPI Cards
- Revenue Trends
- Team Performance Summary

**3. Sales Director / Head of Sales**
**How It Helps**

This is one of the primary users of the dashboard.

**Key Questions Answered**

- Which teams are performing best?
- Which agents need support?
- Which products are easiest to sell?
- How effective is the sales pipeline?

**Benefits**

- Team management
- Performance monitoring
- Sales strategy optimization

**Dashboard Areas Used**
- Revenue by Agent
- Win Rate by Agent
- Top & Bottom Agents
- Product Performance

**4. Sales Managers**
**How It Helps**

Sales managers supervise individual sales teams.

**Key Questions Answered**

- Which agents are underperforming?
- Which agents need coaching?
- Which opportunities are converting?

**Benefits**
- Team coaching
- Performance improvement
- Resource allocation

**Dashboard Areas Used**
- Agent Rankings
- Agent Revenue
- Win Rate Analysis

**5. Sales Agents**
**How It Helps**

Sales agents can benchmark their performance against peers.

**Key Questions Answered**
- How do I compare to other agents?
- Am I meeting expectations?
- What products should I focus on?

**Benefits**
- Self-performance monitoring
- Motivation
- Skill development

**Dashboard Areas Used**
- Agent Ranking
- Revenue Performance
- Product Win Rates

**6. Marketing Department**

**How It Helps**

Marketing teams need to know which products generate successful sales outcomes.

**Key Questions Answered**

- Which products convert best?
- Which products need additional promotion?
- Which offerings generate the most revenue?

**Benefits**
- Campaign planning
- Budget allocation
- Product positioning

**Dashboard Areas Used**
- Product Revenue
- Product Win Rate
- Quarterly Trends

**7. Product Management Team**
**How It Helps**

Product managers use the analysis to evaluate market acceptance.

**Key Questions Answered**

- Which products perform best?
- Which products struggle to close deals?
- What product improvements are needed?

**Benefits**
- Product strategy improvement
- Product lifecycle management
- Feature prioritization

**Dashboard Areas Used**
- Product Revenue
- Product Win Rate
- Lost Opportunity Analysis

**8. Finance Department**

**How It Help**

Finance teams use sales performance data for budgeting and forecasting.

**Key Questions Answered**

- What revenue can be expected?
- Are sales trends improving?
- Which quarters perform best?

**Benefits**

- Revenue forecasting
- Financial planning
- Budget preparation

**Dashboard Areas Used**
- Revenue Trends
- Quarterly Analysis
- QoQ Growth

**9. Data Analysts & Business Intelligence Teams**
**How It Helps**

Analysts use the dashboard to monitor business performance and identify opportunities for deeper analysis.

**Key Questions Answered**

- What factors influence revenue?
- What causes opportunity losses?
- Which performance patterns exist?

**Benefits**
- Insight generation
- Root cause analysis
- Decision support

**Dashboard Areas Used**
- Entire Dashboard

## Skills Demonstrated 

- Data Connection in Power BI
- Data Profiling
- Data Cleaning and Transformation in Power Query
- Data Modelling
- Data Analysis
- Data Visualization

## Data Source 

The dataset for this project is sourced from [Maven Analytics website](https://app.mavenanalytics.io/datasets?search=cr) designed specifically for practice purposes. The project utilizes a dataset containing information on sales, stores, inventory and products. The dataset used for this analysis was downloaded from Maven Analytics website where datasets are available for practice purpose. The dataset is an Csv file and it consist four main table which are, Account Table, Product Table, Sales Pipeline, and Sales Team table. A fifth table was created which is Calander Table. 

**Account Table** contain information about the about the company’s account, it has 7 columns and 85 rows which are Account, Sector, Year Established, Revenue, Employees, Office Location, Subsidiary of. Account is the Company name, Sector is the Industry, Year establish is the year the industry was establish, Revenue is the Annual revenue in (in millions of USD), Employee is the number of employees, Office location is the headquarters, Subsidiary of is the parent company. .

**Product Table** contain information about the company’s product, it has 3 columns and 7 rows which are Product, Series, and Sales Prices. Product is the product name, Series is the Product series, Sales price is the suggested retail price.  

**Sales Team Table** contains information about the company’s sales team, it has 3 columns and 35 rows which are Sales Agent, Manger, Regional office. Sales agent is the sales agent, Manager is the Respective sales manager, regional office is the regional office.

**Sales Pipeline** contains information about the company’s sales team, it has 8 columns and 1000 rows which are Opportunity Id, Sales agent, Product, Account, Deal stage, Engage Date, Close Date, Close Value. Opportunity Id is the Unique identifier, Sales agent is the sales agent of the company, Product is the product name, Deal stage is the sales pipeline stage (Prospecting, Engaging, Won / Loss), Engage Date is the date in which the “Engaging” deal stage was initiated, Close date is the Date in which the deal was "Won" or "Lost", Close revenue is the revenue from the deal

## Data Preparation & Cleaning Process 

Before analysis, the dataset was cleaned and transformed in Power BI Power Query.

**Step 1: Data Type Validation**

Ensured:

| Column         | Data Type |
| -------------- | --------- |
| Opportunity ID | Text      |
| Sales Agent    | Text      |
| Sales Team     | Text      |
| Product        | Text      |
| Close Date     | Date      |
| Close Value    | Decimal   |


**Step 2: Remove Duplicate Records**

Based on:

Opportunity ID

Power Query:

Remove Duplicates

Step 3: Handle Missing Values

Checked:

- Sales Agent
- Product
- Close Value
- Close Date

Removed or corrected incomplete records.

**Step 4: Standardize Text Fields**

Applied:

Trim
Clean
Capitalize Each Word

To:

Sales Agent
Sales Team
Product

**Step 5: Calendar Table Creation**

Created a dedicated Date Table:

Calendar = CALENDAR(

MIN('sales_pipeline'[Close Date]),

MAX('sales_pipeline'[Close Date])
)

**Step 6: Time Intelligence Columns**
Year
Year =
YEAR(Calendar[Date])
Quarter
Quarter =
"Q" & FORMAT(Calendar[Date],"Q")
Quarter Sort
Quarter Number =
QUARTER(Calendar[Date])
Year Quarter
Year Quarter =
FORMAT(Calendar[Date],"YYYY")
& " Q" &
QUARTER(Calendar[Date])

**7. Data Modeling**

Relationship created:

Calendar[Date]
        ↓
sales_pipeline[Close Date]

Relationship Type:

One-to-Many

**8. KPI Measures Used**
Total Revenue
Revenue =
SUM('sales_pipeline'[Close Value])

Measures total value of successfully closed opportunities.

Total Opportunities
Total Opportunities =
COUNT('sales_pipeline'[Opportunity ID])

Measures total sales opportunities created.

Won Deals
Won Deals =
CALCULATE(
COUNT('sales_pipeline'[Opportunity ID]),
'sales_pipeline'[Deal Stage]="Won"
)

Measures successfully converted opportunities.

Lost Deals
Lost Deals =
CALCULATE(
COUNT('sales_pipeline'[Opportunity ID]),
'sales_pipeline'[Deal Stage]="Lost"
)

Measures unsuccessful opportunities.

Win Rate
Win Rate =
DIVIDE(
[Won Deals],
[Won Deals] + [Lost Deals]
)

Measures conversion effectiveness.

Agent Ranking
Agent Rank =
RANKX(
ALLSELECTED('sales_pipeline'[Sales Agent]),
[Revenue],
,
DESC,
DENSE
)

Ranks agents by revenue generated.

**9. Dashboard Components**
Executive KPI Cards

Displayed:

Total Revenue
Total Opportunities
Won Deals
Lost Deals
Win Rate

Purpose:

Provides an instant overview of sales performance.

Revenue Trend Analysis

Chart:

Line Chart

Measures:

Revenue by Month
Revenue by Quarter

Purpose:

Identify growth and seasonal patterns.

Sales Team Performance

Chart:

Clustered Bar Chart

Metrics:

Revenue
Win Rate

Purpose:

Compare team effectiveness.

Agent Performance

Charts:

Top 10 Agents
Bottom 10 Agents

Purpose:

Identify top performers and coaching opportunities.

Product Analysis

Charts:

Revenue by Product
Win Rate by Product

Purpose:

Determine strongest and weakest products.

**10. Key Findings**
Finding 1: Revenue Concentration

Revenue is concentrated among a small number of sales teams.

This indicates:

Certain teams consistently outperform others.
Revenue dependency exists on a limited number of teams.
Business Risk

Heavy reliance on a few teams creates operational risk.

Finding 2: Agent Performance Gap

Top-performing agents contribute significantly more revenue than lower-performing agents.

Observation:

Revenue generation is unevenly distributed.
High-performing agents demonstrate stronger conversion skills.
Business Impact

Training opportunities exist for lower-performing agents.

Finding 3: Product Performance Differences

Certain products consistently achieve higher win rates.

Possible reasons:

Better market demand
Easier value proposition
Stronger pricing strategy
Business Impact

Marketing and sales focus should prioritize these products.

Finding 4: Opportunity Conversion

Win rate analysis indicates a percentage of opportunities fail to convert.

Potential causes:

Poor qualification process
Pricing concerns
Competitive pressure
Finding 5: Quarterly Trends

Revenue trends reveal periods of growth and slowdown.

Understanding these patterns helps management:

Forecast future revenue
Allocate resources efficiently
Prepare for seasonal fluctuations
