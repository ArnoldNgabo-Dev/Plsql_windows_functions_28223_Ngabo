** GIRA ICT Rwanda: Relational Database Framework for B2B2C Inventory Liquidity**

-GIRA ICT is a Rwandan FinTech startup that bridges the gap between local electronics vendors and underserved buyers (students, SMEs, and low-income individuals). The company targets the "Affordability Roadblock" in the Rwandan hardware market.

-Local shops in districts like Rubavu and Musanze possess "dead stock"—hardware that is physically present but not moving due to high upfront costs. Conversely, students and SMEs require this technology but lack the cash. GIRA ICT needs a unified relational system to track which inventory is stagnant, monitor the liquidity disbursed to vendors, and segment buyers based on their credit reliability.  
This analysis will enable GIRA to prescribe "Inventory Swaps" between districts, identify churn risks in the customer onboarding process, and automate credit limit increases for high-performing SMEs(Small Medium Enterpries)

what happened?

The analysis confirms that 25% of the customer base (SMEs in Quartile 1) generates 55% of the total liquidity volume. Laptops priced under 400,000 RWF move 3x faster than premium units.

Why did it happen?
Using RIGHT JOIN and SELF JOIN, we found that the Rubavu district has 30% higher "dead stock" than Kigali. This is because rural vendors were stocking high-end gaming rigs, which were misaligned with the budgets of the local student population.

what should be  done next
Inventory Swap: GIRA should prescribe moving high-end stagnant stock from Rubavu to Kigali shops while re-routing educational models to rural areas.    

SME Credit Expansion: SMEs in the top 10% of the CUME_DIST() ranking should receive an automated 15% credit limit increase to encourage fleet purchases.    

Youth Engagement: Launch a "Referral Discount" for the inactive youth identified in the LEFT JOIN report to boost device ownership rates.





References
Codd, E.F. (1970). A Relational Model of Data for Large Shared Data Banks. ACM.    

Oracle Corp. (2025). Analytic Window Functions Guide.    

Maniraguha, E. (2025). Lecture 01 - SQL Basics & Normalization. AUCA.    

Jacobsen, S. (2026). Customer Segmentation using RFM and SQL.    

McKinsey & Co. (2017). Prescriptive analytics in retail operations.    



 
