# Technical Decision Examples

This repository presents three key technical decisions from my career. Each example illustrates my technical depth, decision rationale, and impact. Each decision is described in a concise format with responses under 250 words per section.

---

## Decision 1: Medallion Lakehouse Architecture at Imperial Tobacco

- **Company:** Imperial Tobacco  
- **Type:** Other (Manufacturing/Consumer Goods)  
- **Employees:** Large enterprise (10K+)  
- **Project Name & Purpose:**  
  *Medallion Lakehouse Architecture Implementation* – Streamlined reporting and analytics by organizing data into bronze, silver, and gold layers, supporting unified enterprise data models and advanced predictive analytics.  
- **Architecture & Scale:**  
  Multi-layered Lakehouse architecture integrating diverse data sources and powering global Power BI dashboards and AI/ML workflows.  
- **Team Size:** ~15 engineers  
- **Role:** Senior Data Specialist – Led architectural design and implementation.  
- **Decision-Making Role:** Sole or main decision-maker  
- **Problem to Solve:**  
  Fragmented data pipelines and inconsistent reporting hindered timely decision-making and predictive analytics.  
- **Solutions Considered:**  
  Rebuild the traditional data warehouse; Implement a conventional star schema; **Adopt a medallion Lakehouse architecture with incremental refinement**  
- **Reasons for Choice:**  
  This approach enabled scalable data ingestion, improved data quality, and provided a robust foundation for AI/ML integration—essential for actionable insights and robust data governance.

---

## Decision 2: Integrating GenAI in an Energy Trading Analytics Platform at Shell PLC

- **Company:** Shell PLC  
- **Type:** Other (Energy Trading)  
- **Employees:** 100K+  
- **Project Name & Purpose:**  
  *Energy Trading Analytics Platform Enhancement* – Empower real-time decision-making for energy trading with automated insights.  
- **Architecture & Scale:**  
  Cloud-based, distributed system using Azure Functions, Data Factory, MSSQL, and Power BI for live dashboards and KPIs.  
- **Team Size:** ~10 engineers  
- **Role:** BI Engineer – Focused on process automation and dashboard integration.  
- **Decision-Making Role:** Contributed to decision  
- **Problem to Solve:**  
  Manual dashboard interpretation and delayed insights were limiting timely trading decisions.  
- **Solutions Considered:**  
  Rely solely on BI dashboards; Develop custom alerting systems; **Integrate a GenAI module for natural language summaries and predictive insights**  
- **Reasons for Choice:**  
  Leveraging GPT-4 (with domain-specific fine-tuning) provided immediate, contextual insights that reduced cognitive load and accelerated decision-making.  
- **Generative AI Tools:**  
  GPT-4

---

## Decision 3: AI Theft Detection Software (Personal Project)

- **Company:** Personal Project  
- **Type:** Personal project  
- **Employees:** 1 (sole developer)  
- **Project Name & Purpose:**  
  *AI Theft Detection Software* – A system to identify and alert on theft using video analytics and contextual pattern recognition.  
- **Architecture & Scale:**  
  Cloud-based AI solution integrating computer vision models and GenAI for contextual analysis with a modular design for scalability.  
- **Team Size:** Sole developer  
- **Role:** Independent Developer/Founder  
- **Decision-Making Role:** Sole or main decision-maker  
- **Problem to Solve:**  
  Traditional surveillance systems often miss subtle theft behaviors, resulting in undetected losses.  
- **Solutions Considered:**  
  Upgrade existing camera systems; Use rule-based motion detection; **Develop an AI-powered theft detection system integrating GenAI for contextual analysis and real-time alerts**  
- **Reasons for Choice:**  
  GenAI integration (via GPT-4 and complementary computer vision models) enabled dynamic behavior interpretation, significantly enhancing detection accuracy and reducing false positives.  
- **Generative AI Tools:**  
  GPT-4, TensorFlow (YOLO)

---
