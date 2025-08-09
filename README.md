# Splunk Logs and Investigations

In this project I am creating three different excercises all of which include different data, different tasks, but similar controls. The goals of this project are to: 

1. How to use SAP data, explore the issue, and decided the next steps
2. Select and Review data sources to help troubleshoot the issue 
3. Determine tools required to resolve the issue
4. Answer key questions crucial to client

Through this project I have gained a comprehensive understanding of Splunk's architecture, written many detection-related SPL searches, and applied attacker TTPs and analytics for defensive cybersecurity tasks. I am now well prepared to leverage Splunk in real-world log analysis, detection, and incident response scenarios. 
## Table of Contents

- [Task One Scenario](#splunk-and-spl)
	- [Task](#splunk-as-a-siem)
	- [Resources](#identify-available-data)
	- [Responses](#practice-queries)

## Task One Scenario

After dominating the European luxury footwear market, Chausseur Élégant, a premium French shoe manufacturer, launched an aggressive North American expansion. The initial rollout surpassed expectations, with rapid retail partnerships established across major U.S. metropolitan areas. 

However, six months into operations, the CX team observed alarming patterns: a 217% spike in return rates from Texas and Florida locations, coupled with scathing social media reviews mentioning "glue failures" and "misaligned stitching" – issues completely antithetical to Élégant's 0.3% defect rate in Europe. 

You're now in a high-stakes meeting with their VP of North American Operations (formerly of Louis Vuitton) and Chief Quality Officer (ex-Hermès), who've intercepted three shipments containing suspiciously subpar materials. Their internal forensic team confirmed these weren't manufacturing defects, but rather sophisticated knockoffs entering through their Miami distribution hub. 

The board demands: (1) immediate geospatial analysis of counterfeit hotspots correlated with social sentiment, (2) supply chain vulnerability assessment focusing on third-party logistics partners, and (3) a blockchain-based authentication prototype for their premium line within 45 days. With $28M in projected Q4 revenue at risk and their Milan Fashion Week showcase approaching, every decision carries existential weight for this 93-year-old maison.

### Analyzing Data Set

### Data Set Questions

1. Which of the following datasets would you rather get access to for this task?
 	a. Qualtrics NPS Data about the customer satisfaction
 	b. Amplitude Analytics Web and app user intelligence data
 	c. SAP Inventory Reports data
	d. Social Media Brand Metrics data

Correct Answer: a. Qualtrics NPS Data about the customer satisfaction.
Reason: Tracking customer sentiment across regions and time periods helps pinpoint quality issues, service gaps, or potential counterfeit problems before they escalate.

2. What other data would be a good addition to Qualtrics NPS Data?
   	a. Employee NPS A measure of employee satisfaction within the company
	b. Order Returns Dataset with all returns of orders made by customers
	c. Group interviews with questionnaires filled by small margin of early users of the products and services
	d. Customer Satisfaction Surveys to identify areas for improvement in products or services

Correct Answer: b. Order Returns Dataset with all returns of orders made by customers
Reason: Data on whether orders are successfully completed or not can provide valuable insights when analyzing statistics by company location.

3. What software should you use to analyze the given data?
	a. Text Editor Load up the CSV in a plain text editor and look manually through the data.
	b. A Spreadsheet editor like MS Excel
	c. Professional Business Intelligence & Analytics softwarelike SAP Analytics Cloud, Tableau, etc.
	d. Professional Data Storage Solution like Oracle Database, SAP HANA, Microsoft SQL Server

## Task Two Scenario

Your second task is to import the client's data into SAP Analytics Cloud and to analyze it.


