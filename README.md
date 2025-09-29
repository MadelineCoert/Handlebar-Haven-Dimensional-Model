# Handlebar-Haven-Dimensional-Model
Designed a Kimball-style dimensional model and star schema for Handlebar Haven to analyse profitability across customers, products, suppliers, territories and time, enabling data-driven decision making.

## Final Report  
**[🔗 View the full PDF report here](HandlebarHaven_Model_MadelineCoert.pdf)**  
*A complete star schema design with fact/dimension tables, hierarchies, keys and ETL considerations.*

This project develops a dimensional model and star schema for Handlebar Haven, a bicycle retailer preparing for expansion. The model enables the leadership team to analyse profitability by customer, product, supplier, territory and time, supporting confident, data-driven decisions.

---

## Project Overview

- **Client:** Handlebar Haven  
- **Role:** Data Analyst (Dimensional Modelling)  
- **Tools Used:** SQL, ERD tools, dimensional modelling (Kimball methodology)  
- **Dataset:** Simulated operational data covering customers, products, sales orders and suppliers  
- **Deliverable:** Full star schema design + PDF report + data dictionary  

---

## Key Insights

- **Granularity is critical:** The fact table is designed at the transaction (line item) level to support flexible analysis across multiple dimensions.  
- **Profitability focus:** Contribution margin, ROI%, and cost metrics highlight which products, customers, and suppliers drive value.  
- **Strong dimension design:** Product, customer, time, territory, and supplier dimensions enable natural hierarchies and drill-down paths.  
- **Traceability & extensibility:** Use of natural and surrogate keys ensures auditability and supports slowly changing dimensions.  
- **Business alignment:** The schema directly answers strategic questions of management while being adaptable for future analytics projects.

---

## Recommendations

- **Implement data governance:** Maintain historical cost accuracy, discount tracking, and dimension consistency.  
- **Adopt margin & ROI metrics:** Use these as core KPIs rather than revenue alone.  
- **Use territorial analytics:** Leverage region and sales performance insights for expansion strategy.  
- **Evolve toward predictive analytics:** Extend the schema for forecasting, churn analysis, and scenario testing.

---

## Techniques Applied

- Transaction-level fact table capturing units sold, sales amount, costs, margins, ROI, discounts  
- Dimension modelling with hierarchies in product, customer, time, supplier, territory  
- Use of surrogate keys for performance, with natural keys retained for auditability  
- Considerations for ETL, slowly changing dimensions, and historical discount/cost alignment  
- Data dictionary to document attributes, sources, and transformations  

---

## Repository Structure

Handlebar-Haven-Dimensional-Model/  
├── README.md                                # Project overview  
├── BSAN7206_A1_MadelineCoert_s4973657.pdf   # Final PDF report with full design  
├── star_schema_diagram.png                   # Star schema visual   
├── data_dictionary.xlsx                      # Data dictionary 
├── scripts/                                  # SQL / ETL / transformation scripts  
└── figures/                                  # Supporting diagrams, visuals  

---

## Reflections

This project deepened my understanding of dimensional modelling by assembling a robust schema that balances analytical flexibility with performance. Through designing fact and dimension tables, choosing grain, and planning for change over time, I strengthened my ability to translate business needs into scalable data models. The experience emphasised the importance of aligning technical design with strategic decisions.

---

## Author

**Madeline Coert**  
Graduate Certificate in Business Analytics – University of Queensland  

📍 Brisbane, Australia  
📧 madelinecoert@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madeline-coert-546667309)  
