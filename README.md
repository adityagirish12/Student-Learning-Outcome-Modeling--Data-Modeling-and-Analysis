## 📘 Student Learning Outcome Modeling
*A Quantitative Research Project | B.Tech Thesis (Manipal Institute of Technology)*  

### 🔍 Short Description  
This project investigates how different elements of online course design—course information, content design, content delivery, and assessment—impact overall student learning outcomes. Using **SmartPLS 3** and **PLS-SEM**, the study models relationships across five constructs and validates them using reliability, validity, mediation, and bootstrapping techniques. The research is based on **400+ survey responses** collected through Google Forms.

---

### 🧪 What This Project Involves  
- Built a full **statistical modeling pipeline** using:  
  - PLS-SEM  
  - Regression & Mediation Analysis  
  - Bootstrapping (5,000 samples)  
  - Reliability & Validity tests (Cronbach’s Alpha, AVE, Fornell–Larcker, HTMT)
- Conducted a cross-sectional quantitative study using a structured Likert-scale survey.
- Modeled 5 constructs:  
  **Course Information → Content Design → Content Delivery → Assessment → Learning Outcome**
- Evaluated structural model significance, convergent & discriminant validity.

---

### 📊 Key Insights  
- Clear and well-structured **course information** improves both **content design** and **content delivery**, which positively influence learning outcomes.  
- Strong **content design** enhances assessment effectiveness and learner engagement.  
- Formative assessments and transparent grading criteria improve comprehension and retention.  
- Final SEM model demonstrated strong reliability and validity (Cronbach’s Alpha > 0.8, AVE > 0.5, Composite Reliability > 0.87).

---

### 🛠️ Tech & Tools Used  
- **SmartPLS 3** (PLS-SEM, Bootstrapping, Mediation)  
- **Google Forms** (Data collection)  
- **Excel/CSV** (Data cleaning & preprocessing)  
- Statistical Methods: SEM, Mediation, Regression-on-Regression, Convergent & Discriminant Validity Testing

---

### 📁 Suitable For  
- Data modeling & analytics portfolios  
- Educational research or EdTech case studies  
- Demonstrating applied statistical modeling  
- Showcasing cross-functional research & analysis skills

---

## 🧩 SEM Model — Conceptual Flow Diagram (PLS-SEM)

```mermaid
flowchart LR
    CI[Course Information] --> CD[Content Design]
    CI --> DL[Content Delivery]
    CD --> AS[Assessment]
    DL --> AS
    AS --> LO[Learning Outcome]

    style CI fill:#b3d1ff,stroke:#003d99,stroke-width:2px
    style CD fill:#d2e8b6,stroke:#4f772d,stroke-width:2px
    style DL fill:#ffe3b3,stroke:#cc8800,stroke-width:2px
    style AS fill:#ffcccc,stroke:#b30000,stroke-width:2px
    style LO fill:#dab6ff,stroke:#5e239d,stroke-width:2px



