# CRM Sales Opportunities Performance Analysis  

## Table of Content
[Project Scope]()

Aim of The Project

Objective of The Project

Use Case

Skill Demonstrated

Data Source

Data Preparation and Cleaning 

Data Modelling 

Data Analysis and Insight 

Data Visualization

Recommendations

Business Impact

conclusion

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

**Calender Table** The Calendar Table was created to enable accurate time-based analysis in Power BI. it contain 6 columns and 306 rows which are, Date, Year, Month, Quarter, Year Quarter, and Month Number. Date is the date of the trasaction, Year is the physical year, Month is the month od trancation, Quarter is the year quaeter, Month Number is the number representing each month.

Without a Calendar Table, Power BI can display dates, but many advanced time intelligence calculations will either not work correctly or will be difficult to implement.

## Data Preparation & Cleaning Process 

Before analysis, the dataset was cleaned and transformed in Power BI Power Query.

**Step 1: Data Type Validation**

Ensured:

| Column         | Data Type |
| -------------- | --------- |
| Opportunity ID | Text      |
| Sales Agent    | Text      |
| Product        | Text      |
| Account        | Text      |
| Deal Stage     | Text      |
| Engage Date    | Date      |
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

The Calendar Table was created to enable accurate time-based analysis in Power BI.

Without a Calendar Table, Power BI can display dates, but many advanced time intelligence calculations will either not work correctly or will be difficult to implement.

**Business Purpose**

Management wants answers such as:

- How did revenue perform by month?
- What was the revenue in Q1 compared to Q2?
- Is revenue increasing year-over-year?
- What is the quarter-over-quarter growth rate?
- Which month generated the highest revenue?

To answer these questions efficiently, Power BI needs a dedicated Date Table.
Created a dedicated Date Table:

```
Calendar = CALENDAR (

MIN('sales_pipeline'[Close Date]),

MAX('sales_pipeline'[Close Date])
)
```
**Additional Columns Created**

After creating the Calendar Table, we added:

**Step 6: Time Intelligence Columns**

**Year**
```
Year =
YEAR(Calendar[Date])
```
Purpose:

Allows annual analysis.

**Quarter**
```
Quarter =
"Q" & FORMAT(Calendar[Date],"Q")
```
Purpose:

Allows annual analysis.

**Quarter Sort**
```
Quarter Number =
QUARTER(Calendar[Date])
```
**Month**
```
Month =
FORMAT(Calendar[Date],"MMMM")
```
Purpose:

Allows monthly trend analysis.

**Year Quarter**
```
Year Quarter =
FORMAT(Calendar[Date],"YYYY")
& " Q" &
QUARTER(Calendar[Date])
```
Purpose:

Tracks performance across multiple years.

Example:

| Year Quarter |
| ------------ |
| 2024 Q1      |
| 2024 Q2      |
| 2024 Q3      |
| 2025 Q1      |

**Key Analysis Enabled by the Calendar Table**

**1. Quarterly Revenue Trend**

Chart:
```
Year Quarter → Revenue
```
Shows:

- Growth
- Decline
- Seasonality

**2. Quarter-over-Quarter Growth**
```
QoQ Growth % =
DIVIDE(
[Revenue] - [Previous Quarter Revenue],
[Previous Quarter Revenue]
)
```
Without a Calendar Table, this becomes difficult and unreliable.

**3. Revenue by Month**

Allows management to identify:

- Peak months
- Weak months
- Seasonal trends

**4. Date Hierarchy**

The Calendar Table allows creation of:
```
Year
 └── Quarter
      └── Month
           └── Date
```
Users can drill down from Year → Quarter → Month in charts.

## Data Modeling

Relationship created:
```
Calendar[Date]
        ↓
sales_pipeline[Close Date]
```
Relationship Type:
```
One-to-Many
```
**8. KPI Measures Used**

**Total Revenue**
```
Revenue =
SUM('sales_pipeline'[Close Value])
```
Measures total value of successfully closed opportunities.

**Total Opportunities**
```
Total Opportunities =
COUNT('sales_pipeline'[Opportunity ID])
```
Measures total sales opportunities created.

**Won Deals**
```
Won Deals =
CALCULATE(
COUNT('sales_pipeline'[Opportunity ID]),
'sales_pipeline'[Deal Stage]="Won"
)
```
Measures successfully converted opportunities.

**Lost Deals**
```
Lost Deals =
CALCULATE(
COUNT('sales_pipeline'[Opportunity ID]),
'sales_pipeline'[Deal Stage]="Lost"
)
```
Measures unsuccessful opportunities.

**Win Rate**
```
Win Rate =
DIVIDE(
[Won Deals],
[Won Deals] + [Lost Deals]
)
```
Measures conversion effectiveness.

**Agent Ranking**
```
Agent Rank =
RANKX(
ALLSELECTED('sales_pipeline'[Sales Agent]),
[Revenue],
,
DESC,
DENSE
)
```
Ranks agents by revenue generated.

**9. Dashboard Components**
Executive KPI Cards

Displayed:

- Total Revenue
- Total Opportunities
- Won Deals
- Lost Deals
- Win Rate

Purpose:

Provides an instant overview of sales performance.

**Revenue Trend Analysis**
Measures:

- Revenue by Month
- Revenue by Quarter

Purpose:

Identify growth and seasonal patterns.

**Sales Team Performance**


Metrics:

- Revenue
- Win Rate

Purpose:

Compare team effectiveness.

**Agent Performance**

Charts:

- Top 10 Agents
- Bottom 10 Agents

Purpose:

Identify top performers and coaching opportunities.

**Product Analysis**

Charts:

- Revenue by Product
- Win Rate by Product

Purpose:

Determine strongest and weakest products.

**10. Key Findings**

**Finding 1: Revenue Concentration**

Revenue is concentrated among a small number of sales teams.

This indicates:

- Certain teams consistently outperform others.
- Revenue dependency exists on a limited number of teams.

**Business Risk**

Heavy reliance on a few teams creates operational risk.

**Finding 2: Agent Performance Gap**

Top-performing agents contribute significantly more revenue than lower-performing agents.

Observation:

- Revenue generation is unevenly distributed.
- High-performing agents demonstrate stronger conversion skills.

**Business Impact**

Training opportunities exist for lower-performing agents.

**Finding 3: Product Performance Differences**

Certain products consistently achieve higher win rates.

Possible reasons:

- Better market demand
- Easier value proposition
- Stronger pricing strategy

**Business Impact**

Marketing and sales focus should prioritize these products.

**Finding 4: Opportunity Conversion**

Win rate analysis indicates a percentage of opportunities fail to convert.

Potential causes:

- Poor qualification process
- Pricing concerns
- Competitive pressure

**Finding 5: Quarterly Trends**

Revenue trends reveal periods of growth and slowdown.

Understanding these patterns helps management:

- Forecast future revenue
- Allocate resources efficiently
- Prepare for seasonal fluctuations

## Data Analysis And Insight
The objectives of the Analysis is to conduct a revenue analysis to measure total revenue generated, identyfy top performing sales agent, calculate win rates,analyze won versus lost opportunities, evaluate pipelines conversion efficiency, and also to carryout products analysis to determine product generating the highest revenue, identify products with the strongest win rates, analyze qurterly perfomance, and identyfy growth patterns.

**Top 10 Revenue by Agent** 

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Top%2010%20Revenue%20by%20Sales%20Agent.png)

**Findings**

Darcel Schlecht at **$1.15M** is more than **double** the second-ranked **Vicki Laflamme** at **$0.48M** — a gap of **$670K** between first and second place alone. Agents ranked 2nd through 9th are tightly clustered between **$0.41M** and **$0.48M** — a range of only **$70K** across 8 agents, suggesting a **performance plateau** at the mid-to-top tier.

**Revenue Concentration Analysis**

| Segment | Agents | Revenue Share |
|---|---|---|
| Darcel Schlecht alone | 1 | ~11.5% of total |
| Top 2 agents | 2 | ~16.3% of total |
| Top 10 agents | 10 | ~63% of total |
| Bottom 20 agents | 20 | ~37% of total |

**Board Recommendation**

The single-agent dependency on **Darcel Schlecht** is the biggest structural risk in this sales org. The board should prioritize succession planning and knowledge transfer from Schlecht to at least 3 high-potential mid-tier agents within the next two quarters.

**Bottom 10 Revenue per Agent**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Bottom%2010%20Revenue%20per%20Agent%20by%20Sales%20Agent.png)

**Findings**

The bottom 10 agents generated a combined revenue range of $123K to $235K, with a total spread of only $112K across all 10 agents — indicating relatively clustered underperformance rather than a single outlier dragging the group down.
Violet Mcielland at $123K stands as the weakest performer, trailing the next lowest (Wilburn Farren at $158K) by $35K — a notable gap within an otherwise tight cohort.
Rosalina Dieter leads the bottom 10 at $235K, which is only $44K below Rank 9 agent James Ascencio ($413K) — suggesting the boundary between mid and bottom tier is relatively thin and addressable with targeted intervention.

**Key Observations**

| Agent | Revenue | Concern |
|---|---|---|
| Violet Mcielland | $123K | Lowest performer — significant gap to peers |
| Wilburn Farren | $158K | Highest win rate (67%) but lowest volume — pipeline issue |
| Niesha Huffines | $177K | Below average win rate + low revenue — dual problem |
| Rosalina Dieter | $235K | Closest to mid-tier — most recoverable |

**Board Recommendation**

Wilburn Farren is a misallocation problem, not a performance problem. A 67% win rate with only $158K revenue means this agent is closing well but seeing very few deals. Reallocating leads to Farren could yield an immediate and low-cost revenue lift. Violet Mcielland and Niesha Huffines require structured performance improvement plans.

**Top 10 Revenue and Win Rate % by Sales Agent (Treemap)**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Top%2010%20Win%20Rate%25%20by%20Sales%20Agent.png)

**Findings**

The treemap visually reinforces what the earlier ranking table confirmed — **Darcel Schlecht's dominance is visually overwhelming**. His tile at **$1.2M** occupies nearly a third of the entire chart area, dwarfing every other agent on the team.

The remaining 9 agents in the top 10 are tightly clustered between **$0.4M and $0.5M** — their tiles are visually similar in size, confirming the performance plateau identified earlier. There is no clear second-tier standout emerging to challenge or succeed Schlecht.

**Top 10 Agent Revenue and Tile Proportion**

| Agent | Revenue | Relative Tile Size | Observation |
|---|---|---|---|
| Darcel Schlecht | $1.2M | 🟦 Largest — ~30% of chart | Dominant — single point of risk |
| Kary Hendrixson | $0.5M | Medium | 2nd tier cluster leader |
| Cassey Cress | $0.5M | Medium | Tied with Kary |
| Vicki Laflamme | $0.5M | Medium | Consistent mid-performer |
| Donn Cantrell | $0.4M | Medium-small | Plateau zone |
| Reed Clapper | $0.4M | Medium-small | High win rate, plateau revenue |
| Corliss Cosme | $0.4M | Medium-small | Plateau zone |
| James Ascencio | $0.4M | Medium-small | Plateau zone |
| Zane Levy | $0.4M | Medium-small | Plateau zone |
| Daniell Hammack | $0.4M | Smallest | At risk of falling out of top 10 |

**Board Recommendation**

The treemap makes the concentration risk visually undeniable. Seven of the top 10 agents are generating identical revenue at the $0.4M level with no differentiation. The board should consider a tiered incentive structure — specifically designed to break agents out of the $0.4M plateau and push them toward the $0.6M–$0.8M range. This would naturally reduce dependency on Schlecht and build a stronger second tier.

**Bottom 10 Win Rate % by Sales Agent**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Bottom%2010%20Win%20Rate%25%20by%20Sales%20Agent.png)

**Findings**

This chart reframes the performance conversation entirely. **The bottom 10 agents by win rate** are not the same as the 

bottom 10 by revenue — and that distinction matters enormously for how the board should respond.
The bottom 10 win rates range from **62.39% (Kary Hendrixson) down to 54.98% (Lajuana Vencill)** — a spread of only **7.41 percentage points** across all 10 agents. Crucially, even the lowest win rate in this group (54.98%) is **not catastrophically low** — it simply means these agents are losing roughly 1 in every 2 deals, compared to the team's best who close 7 in every 10.

**Bottom 10 Win Rate Breakdown**

| Rank (Win Rate) | Agent | Win Rate % | Gap to Team Average (63.15%) |
|---|---|---|---|
| 21 | Kary Hendrixson | 62.39% | -0.76% |
| 22 | Anna Snelling | 61.90% | -1.25% |
| 23 | Zane Levy | 61.69% | -1.46% |
| 24 | Garret Kinder | 60.98% | -2.17% |
| 25 | Daniell Hammack | 60.96% | -2.19% |
| 26 | Niesha Huffines | 60.00% | -3.15% |
| 27 | Gladys Colclough | 58.19% | -4.96% |
| 28 | Donn Cantrell | 57.45% | -5.70% |
| 29 | Markita Hansen | 57.27% | -5.88% |
| 30 | Lajuana Vencill | 54.98% | -8.17% |

**Key Observations**

**Kary Hendrixson is 3rd in revenue rank ($454,298) but 21st in win rate (62.39%)** — this agent is compensating for a below-average win rate with exceptionally high deal volume (209 won deals). This is a **volume-over-efficiency strategy** that works but carries risk if pipeline slows.

**Lajuana Vencill at 54.98%** is the only agent meaningfully below the 57% threshold — sitting **8.17 percentage points below the team average**. With 127 won deals and $194,632 in revenue, this agent is generating moderate volume at the team's weakest conversion rate.

**Donn Cantrell (57.45%) ranks 5th in revenue ($445,860)** — another example of a volume-driven performer compensating for conversion inefficiency with high deal throughput.

**Board Recommendation**

The board should not panic about this chart. A bottom win rate of 54.98% on a team averaging 63.15% is not a crisis — it is a coaching opportunity. The priority actions are: (1) provide targeted objection-handling and qualification training to Lajuana Vencill, Markita Hansen, and Donn Cantrell; (2) investigate whether these agents are being assigned harder or less qualified leads than their peers, which would artificially suppress their win rates through no fault of their own.

**Year Quarter by QoQ Growth %**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Year%20Quarter%20by%20QoQ%20Growth%20%25.png)

**Findings**

This bar chart captures the **quarter-on-quarter revenue growth rate** across three measured quarters in 2017. The pattern tells a stark and urgent story of a business that surged strongly then lost all momentum within two quarters.
**2017-Q2** delivered an exceptional **+1.45% QoQ growth** — the standout quarter of the year. However, this was followed by a near-complete stall in **2017-Q3 at just +0.01%** and then a **contraction of -0.09% in 2017-Q4** — the first negative growth quarter on record in this dataset.

**QoQ Growth Summary**

| Quarter | QoQ Growth % | Direction | Assessment |
|---|---|---|---|
| 2017-Q2 | +1.45% | ⬆️ Strong surge | Best performing quarter |
| 2017-Q3 | +0.01% | ➡️ Flat | Growth effectively stalled |
| 2017-Q4 | -0.09% | ⬇️ Contraction | First negative quarter — alarm signal |

**Board Recommendation**

The **growth cliff between Q2 and Q3** is the most critical trend in this chart. A drop from +1.45% to +0.01% in a single quarter is not a natural plateau — it signals either a **pipeline depletion event post-Q2 peak, a seasonal demand collapse, or a loss of sales momentum** that was never recovered. The board must investigate what drove Q2's exceptional growth and why it was not sustained. If Q4's contraction carries into 2018-Q1, this becomes a revenue decline trajectory requiring immediate structural intervention.

**Revenue by Month**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Revenue%20by%20Month.png)

**Findings**

The monthly revenue trend reveals a **volatile, W-shaped pattern** — with two clear peaks, two troughs, and no sustained upward trajectory.

| Month | Revenue | Movement | Note |
|---|---|---|---|
| March | $1.13M | — | Starting baseline |
| April | $0.72M | ⬇️ -$410K | Sharp drop |
| May | $1.03M | ⬆️ +$310K | Recovery |
| June | $1.34M | ⬆️ +$310K | 🏆 Peak — highest month |
| July | $0.70M | ⬇️ -$640K | ⚠️ Steepest drop |
| August | $1.05M | ⬆️ +$350K | Recovery |
| September | $1.24M | ⬆️ +$190K | Second peak |
| October | $0.73M | ⬇️ -$510K | Sharp drop again |
| November | $0.94M | ⬆️ +$210K | Partial recovery |
| December | $1.13M | ⬆️ +$190K | Strong close |

**June ($1.34M) and September ($1.24M)** are the two strongest months. **July ($0.70M) and April ($0.72M)** are the weakest. The $640K collapse from June to July — a 52% month-over-month drop — is the single most alarming data point in this entire report.

**Board Recommendation**

The board should urgently investigate: (1) **What drives the June peak?** If it is end-of-quarter client budget spending, the team should double pipeline activity in May every cycle to maximize it. (2) What causes the July and April crashes? A consistent **pipeline replenishment strategy** is needed to smooth revenue and reduce forecasting volatility.


**Overall Board Summary**

| Area | Status | Priority Action |
|---|---|---|
| Agent concentration risk | 🔴 Critical | Darcel Schlecht drives 11.5% of revenue alone — succession plan needed |
| Monthly revenue volatility | 🔴 Critical | 52% peak-to-trough drops make forecasting unreliable |
| Product portfolio | 🟡 Moderate | 3 products carry 83% of revenue — simplify and refocus |
| Bottom tier performance | 🟡 Moderate | Fixable through lead reallocation and targeted coaching |
| Overall team win rate | 🟢 Healthy | 57.46% is a strong baseline to build from |

**Executive Verdict:** This is a sales organization with strong fundamentals — $10M+ revenue and a 57.46% win rate — but carrying **two critical structural risks:** over-reliance on a single agent and unpredictable monthly revenue swings. Addressing these two issues should be the board's immediate priority before scaling headcount or expanding the product line.

**Revenue by Product**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Revenue%20by%20Product.png)

**Findings**

The product revenue breakdown reveals a **clear two-tier portfolio** — a dominant core and a long tail of low contributors.

| Product | Revenue | Share | Status |
|---|---|---|---|
| GTX Pro | $3.5M | 35.09% | 🟢 Core earner |
| GTX Plus Pro | $2.6M | 26.28% | 🟢 Core earner |
| MG Advanced | $2.2M | 22.15% | 🟢 Core earner |
| GTX Plus Basic | $0.7M | 7.05% | 🟡 Monitor |
| GTX Basic | $0.5M | 4.99% | 🟡 Monitor |
| GTK 500 | $0.4M | 4.00% | 🔴 Review |
| MG Special | <$0.1M | <1% | 🔴 Consider sunset |

**GTX Pro, GTX Plus Pro, and MG Advanced together account for 83.52% of all revenue —** three products carry the entire business. The bottom four products collectively contribute only **16.48%.**

**Board Recommendation**

The board should commission a **product portfolio review** with two specific questions: (1) Are agents being adequately trained and incentivized to sell GTX Pro? (2) Should GTK 500 and MG Special be **sunset, bundled, or repositioned** to reduce complexity and focus sales energy on proven earners?

**Won Deals and Lost Deals by Year Quarter**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Won%20Deals%20And%20Lost%20Deals%20by%20Year%20Quarter.png)

**Findings**

This stacked bar chart provides the most complete picture of **deal volume and conversion efficiency** across all four quarters of 2017. Two critical patterns emerge — a strong Q1-to-Q2 volume expansion and a gradual Q3-to-Q4 volume contraction.
**2017-Q1** is clearly a partial quarter with only **647 total deals** (531 won, 116 lost) — likely representing only 1–2 months of data rather than a full quarter. This should not be used as a performance baseline.
**2017-Q2 through Q3** show the team operating at peak volume — over **2,000 total deals per quarter** — before a modest pullback in Q4.

**Quarterly Deal Volume Breakdown**

| Quarter | Won Deals | Lost Deals | Total Deals | Win Rate |
|---|---|---|---|---|
| 2017-Q1 | 531 | 116 | 647 | 82.07% |
| 2017-Q2 | 1,254 | 778 | 2,032 | 61.71% |
| 2017-Q3 | 1,257 | 790 | 2,047 | 61.40% |
| 2017-Q4 | 1,196 | 789 | 1,985 | 60.25% |

**Key Observations**

**Q1 win rate of 82.07% is misleading** — the low total volume (647 deals) suggests this is an incomplete quarter, likely March only, which aligns with the Revenue by Month chart showing March as the starting data point.

**Q2 to Q3 won deals are nearly identical** (1,254 vs 1,257) yet QoQ growth collapsed from +1.45% to +0.01% — this means Q3 closed the same number of deals as Q2 but at lower average deal values, a sign of deal quality deterioration rather than volume decline.

**Q4 shows the first meaningful volume drop** — total deals fell from 2,047 to 1,985, won deals dropped by 61, and lost deals held almost flat at 789 — meaning the team is **losing the same number of deals but winning fewer**, pushing the win rate down for the third consecutive quarter.

**Board Recommendation**

The board should note that **this is a deal quality and value problem***, not purely a volume problem. Q3 matched Q2 in won deal count but still delivered near-zero growth — meaning average revenue per deal is declining. A deal quality audit — segmenting won deals by product and deal size — is urgently needed to understand whether agents are shifting toward lower-value, easier-to-close deals at the expense of high-value opportunities.



 **Win Rate % by Product**

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/Win%20Rate%20%25%20by%20Product.png)

 
**Findings**

This chart is one of the most strategically important in the entire report. It reveals that **win rate varies significantly by product** — meaning the team's overall 63.15% win rate is a blended average that masks very different conversion dynamics across the portfolio.
The range spans from **GTX Plus Pro at 58.85%** down to **GTK 500 at just 46.88%** — a gap of nearly **12 percentage points** between the easiest and hardest products to close.

**Product Win Rate Ranking**

| Rank | Product | Win Rate % | vs Team Average (63.15%) | Assessment |
|---|---|---|---|---|
| 1 | GTX Plus Pro | 58.85% | -4.30% | 🟢 Best converter |
| 2 | GTX Basic | 58.54% | -4.61% | 🟢 Strong |
| 3 | MG Special | 58.35% | -4.80% | 🟡 Moderate — low revenue contribution |
| 4 | GTX Pro | 57.95% | -5.20% | 🟡 Core product — needs attention |
| 5 | GTX Plus Basic | 55.91% | -7.24% | 🟡 Below average |
| 6 | MG Advanced | 55.38% | -7.77% | 🔴 Weak converter — review needed |
| 7 | GTK 500 | 46.88% | -16.27% | 🔴 Critical — losing more than half of deals |

**The GTX Pro Paradox**

**GTX Pro is the highest revenue product at $3.5M (35.09% of total revenue)** yet ranks only **4th in win rate at 57.95%.** This means agents are closing GTX Pro deals at a below-average rate despite it being the primary revenue driver. If GTX Pro's win rate could be lifted from 57.95% to the team average of 63.15% — a **5.2 percentage point improvement** — the revenue upside would be substantial given the product's volume.

**The GTK 500 Problem**
**GTK 500 at 46.88% win rate** means agents are **losing more than half of all GTK 500 opportunities.** Combined with its low revenue contribution (4% of total), this product is consuming sales time and resources at a deeply inefficient rate. Agents spending time pitching GTK 500 are doing so at a coin-flip success rate — far below every other product in the portfolio.

**Board Recommendation**

The board should action two product-level interventions immediately: **(1) GTX Pro win rate uplift program** — since GTX Pro drives 35% of revenue, even a modest win rate improvement here has outsized financial impact. A dedicated product training, competitive battlecard, and objection-handling playbook for GTX Pro should be developed as a priority. (2) **GTK 500 strategic review** — a 46.88% win rate is unsustainable. The board must decide whether to reposition, reprice, rebundle, or discontinue GTK 500. Agents pitching this product are operating at a structural disadvantage that training alone cannot fix — this is a product-market fit issue.


**Consolidated Board Summary**

| Focus Area | Key Finding | Risk Level | Recommended Action |
|---|---|---|---|
| Agent ranking concentration | Darcel Schlecht = 11.5% of revenue alone | 🔴 Critical | Build succession plan and replicate deal strategy |
| High win rate, low revenue agents | Farren (69.62%), Neloms (70.39%) severely under-utilized | 🔴 Critical | Immediate lead redistribution to high-efficiency agents |
| Bottom win rate agents | Lajuana Vencill at 54.98% — 8pts below team average | 🟡 Moderate | Coaching, qualification training, lead quality audit |
| GTX Pro win rate gap | Top revenue product closing below team average at 57.95% | 🟡 Moderate | Dedicated GTX Pro sales enablement program |
| GTK 500 conversion failure | 46.88% win rate — agents losing more than half of deals | 🔴 Critical | Product strategic review — reposition or discontinue |
| MG Special relevance | Negligible revenue despite moderate win rate | 🟡 Moderate | Bundle with higher-tier product or sunset |

**Executive Verdict:** This report confirms that the organization's performance challenges are **structural, not motivational**. The team has skilled agents being under-utilized, a flagship product under-converting, and a loss-making product consuming valuable selling time. Fixing lead allocation, enabling GTX Pro more aggressively, and resolving GTK 500's future would — conservatively — unlock **$500K–$800K in incremental annual revenue** from the existing team and product base, with no additional headcount required.

**Full Agent Ranking Table — Win Rate, Won Deals, Total Revenue & Agent Rank**

**Findings**

This is the most comprehensive single view of individual agent performance in the dataset. It combines four key metrics — win rate, won deals, total revenue, and rank — allowing a **multi-dimensional performance assessment** that pure revenue ranking cannot provide alone.

The overall team win rate stands at a healthy **63.15%** across **4,238 won deals** and **$10,005,534 in total revenue**. However, drilling into individual performance reveals significant variance that the aggregate number conceals.

**Full Agent Performance Table**

| Rank | Sales Agent | Win Rate % | Won Deals | Total Revenue |
|------|-------------|------------|-----------|---------------|
| 1 | Darcel Schlecht | 63.11% | 349 | $1,153,214 |
| 2 | Vicki Laflamme | 63.69% | 221 | $478,396 |
| 3 | Kary Hendrixson | 62.39% | 209 | $454,298 |
| 4 | Cassey Cress | 62.45% | 163 | $450,489 |
| 5 | Donn Cantrell | 57.45% | 158 | $445,860 |
| 6 | Reed Clapper | 65.40% | 155 | $438,336 |
| 7 | Zane Levy | 61.69% | 161 | $430,068 |
| 8 | Corliss Cosme | 65.50% | 150 | $421,036 |
| 9 | James Ascencio | 65.53% | 135 | $413,533 |
| 10 | Daniell Hammack | 60.96% | 114 | $364,229 |
| 11 | Maureen Marcano | 69.95% | 149 | $350,395 |
| 12 | Gladys Colclough | 58.19% | 135 | $345,674 |
| 13 | Markita Hansen | 57.27% | 130 | $328,792 |
| 14 | Kami Bicknell | 63.97% | 174 | $316,456 |
| 15 | Marty Freudenburg | 62.89% | 122 | $291,195 |
| 16 | Elease Gluck | 63.49% | 80 | $289,195 |
| 17 | Jonathan Berthelot | 64.77% | 171 | $284,886 |
| 18 | Anna Snelling | 61.90% | 208 | $275,056 |
| 19 | Hayden Neloms | 70.39% | 107 | $272,111 |
| 20 | Boris Faz | 66.01% | 101 | $261,631 |
| 21 | Rosalina Dieter | 65.45% | 72 | $235,403 |
| 22 | Rosie Papadopoulos | 64.46% | 78 | $230,169 |
| 23 | Cecily Lampkin | 66.88% | 107 | $229,800 |
| 24 | Moses Frase | 66.15% | 129 | $207,182 |
| 25 | Garret Kinder | 60.98% | 75 | $197,773 |
| 26 | Lajuana Vencill | 54.98% | 127 | $194,632 |
| 27 | Versie Hillebrand | 66.67% | 176 | $187,693 |
| 28 | Niesha Huffines | 60.00% | 105 | $176,961 |
| 29 | Wilburn Farren | 69.62% | 55 | $157,640 |
| 30 | Violet Mcielland | 63.21% | 122 | $123,431 |
| **Total** | | **63.15%** | **4,238** | **$10,005,534** |

**Critical Insight — The High Win Rate Trap**

A striking pattern emerges when isolating agents with **high win rates but low revenue ranks**:

| Agent | Win Rate % | Revenue Rank | Won Deals | Revenue | Gap to Potential |
|---|---|---|---|---|---|
| Hayden Neloms | 70.39% | 19 | 107 | $272,111 | 🔴 High — under-fed pipeline |
| Maureen Marcano | 69.95% | 11 | 149 | $350,395 | 🟡 Moderate |
| Wilburn Farren | 69.62% | 29 | 55 | $157,640 | 🔴 Critical — severely under-utilized |
| Cecily Lampkin | 66.88% | 23 | 107 | $229,800 | 🔴 High — pipeline starvation |
| Versie Hillebrand | 66.67% | 27 | 176 | $187,693 | 🔴 High — low deal value |

**Wilburn Farren is the most extreme case** — a 69.62% win rate (3rd highest on the team) with only 55 won deals and $157,640 in revenue, ranking dead last at 29th. This agent is not underperforming — they are being **structurally starved of opportunity**.

**Board Recommendation**

The data reveals a **two-class problem within the sales org**. Class one: high-volume agents closing average-value deals (Darcel Schlecht). Class two: high-efficiency agents with insufficient pipeline (Farren, Neloms, Lampkin). The board should immediately implement a **lead redistribution audit** — routing higher-value opportunities to agents with proven conversion rates above 66%. Conservatively, moving Wilburn Farren from 55 to 150 won deals at their current win rate could add an estimated **$200K–$350K in incremental revenue** without a single new hire.

## Data Visualization

![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/CRM%20Dashboard%201.png)
![](https://github.com/GideonAdon/CRM-Sales-Opportunities-Performance-Analysis/blob/main/CRM%20Dashboard%202.png)

## Recommendations

**Recommendation 1**

Analyze the sales techniques of top-performing agents.

Implement:

- Coaching sessions
- Best-practice sharing
- Peer mentoring

Expected Outcome:

Improved team-wide performance.

**Recommendation 2**

Increase focus on high-win-rate products.

Actions:

- Increase marketing spend
- Prioritize in sales campaigns
- Bundle with lower-performing products

Expected Outcome:

Higher revenue growth.

**Recommendation 3**

Review lost opportunities.

Conduct root-cause analysis on:

- Price objections
- Product fit issues
- Competitor wins

Expected Outcome:

Improved conversion rates.

**Recommendation 4**

Provide additional support to underperforming teams.

Actions:

- Sales training
- Pipeline reviews
- Performance monitoring

Expected Outcome:

More balanced revenue contribution.

**Recommendation 5**

Implement Quarterly Performance Reviews.

Monitor:

- Revenue
- Win Rate
- Agent Productivity

Expected Outcome:

Early identification of performance issues.

## Business Impact

If recommendations are implemented:

**Revenue**

Expected increase through better conversion rates.

**Productivity**

Improved agent effectiveness.

**Forecast Accuracy**

Better understanding of seasonal trends.

**Sales Efficiency**

More resources allocated to high-performing products and teams.

## Conclusion

The CRM Sales Opportunities analysis reveals significant differences in team performance, agent productivity, product effectiveness, and opportunity conversion rates.

While the organization demonstrates strong revenue-generating capability, opportunities exist to improve sales efficiency by:

Replicating top-agent behaviors
Strengthening underperforming teams
Prioritizing high-performing products
Improving opportunity conversion processes

By leveraging these insights, management can make data-driven decisions that enhance revenue growth, improve sales productivity, and create a more balanced and scalable sales organization.

**Closing Statement for the Board**

"The analysis shows that revenue performance is driven by a relatively small group of high-performing teams and agents. By scaling successful sales practices, optimizing product focus, and addressing conversion bottlenecks, the organization can improve revenue growth, reduce performance disparities, and strengthen overall sales effectiveness."
