# IFE Exhibition Leads Analysis (SQL & Python)

This project analyzes potential customer leads collected during the  
**IFE – International Food & Drink Exhibition (London)** for a Taiwanese food packaging manufacturer.

The goal is to structure qualitative booth interactions into a **data model**,  
identify promising customer segments, and create a foundation for future **Lead Scoring** and **B2B behavioral insights**.

---

## 🎯 Project Objective

To transform on-site exhibition observations into a structured, analyzable dataset:

- Convert booth interactions into a leads table  
- Capture attributes such as **industry, material needs, MOQ, delivery terms, sustainability preference, and urgency**
- Use SQL to explore demand patterns across visitor segments
- Use Python to design a simple **Lead Scoring Model** for prioritizing follow-ups

---


---

## 🧠 Methods Used

### **Lead Data Modeling**
- Designed a structured dataset from qualitative exhibition notes  
- Defined fields:  
  `Country, Industry, Material_Need, MOQ, Delivery_Term, Sustainability_Preference, Urgency_Level, Followup_Priority`

### **SQL Analysis**
- Segment customers by:
  - Region  
  - Industry  
  - MOQ range  
  - Sustainability interest  
- Identify high-intent categories

### **Python Lead Scoring (In Progress)**
- Weighted scoring based on:
  - Alignment with product capabilities  
  - MOQ feasibility  
  - Urgency  
  - Geographic fit  
- Generates a simple priority ranking for follow-up

---

## 📈 Key Insights (Example — Will be updated)

- Sustainability-driven buyers show higher follow-up potential  
- Ideal MOQ range clusters around 3 segments  
- Some industries show faster buying cycles
- Region-level interest varies significantly based on logistics feasibility

---

## 🚀 Roadmap

- [x] Lead data structure design  
- [x] SQL segmentation  
- [ ] Lead scoring model refinement  
- [ ] Tableau visualization for leadership  
- [ ] Integration into a unified B2B dashboard

---


