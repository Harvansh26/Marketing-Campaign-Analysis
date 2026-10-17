\# Marketing Campaign Performance Analysis



\*\*Turning marketing data into business decisions.\*\*



An interactive Power BI dashboard exploring campaign revenue, marketing spend, ROI, and regional performance to identify patterns and uncover opportunities for improvement.



\[View Dashboard](dashboard/Marketing-Campaign-Analysis.pbix) · \[Explore the Data](data/) · \[View Insights](#key-findings)







\## Dashboard Preview



!\[Marketing Campaign Performance Dashboard](screenshots/Marketing-Campaign-Performance-Dashboard.png)



\*An interactive view of marketing performance across campaigns, regions, and campaign types.\*



\## The Business Challenge



Marketing teams invest across multiple campaigns and channels, but spending more does not necessarily mean achieving better results.



The challenge was to understand how campaigns compare, where revenue is being generated, and which areas deserve a closer look before making marketing budget decisions.



\*\*The central question:\*\* Which campaigns show stronger returns, and what should the business investigate next?



\## The Analysis



This project follows five steps to connect the data with practical business decisions.



\### 01 — Problem



Understand the challenge behind marketing performance.



The business needs a clearer way to compare campaign investment with reported returns, identify differences between regions, and evaluate the distribution of Digital and Traditional campaigns.



\### 02 — Evidence



Start with the numbers.



| Performance indicator | Dashboard result |

|---|---:|

| Total Revenue | 42.54M |

| Total Spend | 25.69M |

| Average ROI | 68% |

| Highest displayed ROI | Influencer Marketing |

| Digital campaign share | 65.5% |



These figures provide a snapshot of performance and help direct the investigation.



\### 03 — Investigation



Look beyond the headline numbers.



\- \*\*Campaign performance:\*\* Influencer Marketing has the highest bar in the displayed ROI comparison, followed by Social Media Ads.

\- \*\*Regional performance:\*\* Africa records the highest revenue among the regions displayed, while South America records the lowest.

\- \*\*Spending patterns:\*\* Comparing campaign spend with ROI helps identify where investment and reported returns differ.

\- \*\*Campaign mix:\*\* Digital campaigns account for a larger share of campaign records than Traditional campaigns.



These findings describe the available data. They do not automatically establish profitability or prove that a campaign caused a particular result.



\### 04 — Action



Translate findings into next steps.



\- Investigate what contributes to the stronger displayed ROI of Influencer Marketing.

\- Review lower-performing campaigns to identify opportunities for improvement.

\- Compare regional campaign mixes, costs, and conversion performance.

\- Evaluate Digital and Traditional campaigns using consistent performance measures.

\- Test potential budget changes before scaling investment.



The objective is not to increase spending based on a single chart, but to make better-informed decisions using additional evidence.



\### 05 — Conclusion



The dashboard provides a consolidated view of campaign performance and highlights areas worth investigating further.



The main lesson is that marketing decisions should consider spending, revenue, and returns together. A campaign that generates more revenue is not necessarily the most profitable, and a larger share of campaign activity does not necessarily indicate better performance.



Power BI makes these comparisons easier to explore, communicate, and use as a starting point for business decisions.



\---



\## Inside the Dashboard



\*\*Performance overview\*\*  

KPI cards summarise total revenue, total spend, average ROI, and the campaign with the highest displayed ROI.



\*\*Regional comparison\*\*  

A clustered column chart compares revenue and spend across campaign regions.



\*\*Campaign analysis\*\*  

Combination and bar charts compare spending and ROI across campaign names.



\*\*ROI overview\*\*  

A gauge presents the reported average ROI, while a campaign type chart shows the distribution of campaign records.



\*\*Interactive exploration\*\*  

The Campaign Type slicer and Campaign Region treemap help users explore different parts of the dataset.



\## Tools \& Techniques



| Tool | Purpose |

|---|---|

| Microsoft Power BI | Dashboard design and reporting |

| Power Query | Data preparation and transformation |

| DAX | KPI calculations and measures |

| CSV | Source data |

| Business analysis | Interpretation and recommendations |



\## Project Structure



```text

Marketing-Campaign-Analysis/

├── dashboard/

│   └── Marketing-Campaign-Analysis.pbix

├── data/

│   ├── region performance.csv

│   ├── marketing campaign performance.csv

│   └── marketing campaign details.csv

├── screenshots/

│   └── Marketing-Campaign-Performance-Dashboard.png

└── README.md





\## Explore the Project



1\. Open the `.pbix` file using Power BI Desktop.

2\. If necessary, update the data source paths to match the location of the CSV files.

3\. Refresh the data if prompted.

4\. Use the available filters to explore campaign types and regions.

5\. Compare the results and investigate the findings described above.



\## Notes on Interpretation



\- The displayed ROI figures should be validated against the dataset's definition of ROI and the underlying DAX measures.

\- Revenue minus marketing spend does not represent net profit because other costs may apply.

\- Campaign distribution measures activity, not effectiveness.

\- The recommendations are starting points for further investigation, not proof that a specific budget change will improve results.



\---



\*Built as a practical data analytics project focused on turning numbers into clear findings and actionable business questions.\*

