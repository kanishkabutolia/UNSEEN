# UNSEEN
### An Explainable AI & GIS Framework for Detecting Hidden Gaps in Public Service Delivery

> **UNSEEN** is an AI- and GIS-based decision-support framework designed to identify hidden gaps in public-service delivery by comparing the **expected service reach** of an area with its **observed service reach**.

---

## 📌 Introduction

Access to public services such as **education, healthcare, welfare, transport, and skill development** is essential for inclusive development. However, the presence of a public service does not always guarantee that communities can effectively access or benefit from it.

Traditional monitoring systems mainly focus on the **number of facilities, beneficiaries, or utilization rates**. Such statistics can hide local-level inequalities and may fail to reveal areas where service reach is unexpectedly low despite the availability of resources.

**UNSEEN** addresses this problem by combining **Machine Learning, Explainable AI (XAI), and Geographic Information Systems (GIS)** to identify these hidden gaps in service delivery.

The framework analyses factors such as:

- Population and demographic characteristics
- Socioeconomic conditions
- Geographic accessibility
- Travel distance and connectivity
- Service capacity and availability
- Historical service utilization

Using these factors, UNSEEN estimates the **expected level of service reach** for a geographic area and compares it with the **observed reach**. The difference is used to generate an **Opportunity Gap Score**, helping identify areas that may be underserved.

The system then uses **Explainable AI techniques such as SHAP** to identify the factors associated with the predicted gap and presents the results through an interactive **GIS-based dashboard**.

---

## 🎯 Problem Statement

Existing public-service monitoring approaches are largely descriptive and reactive. They can show where services exist and how many people use them, but they may not identify areas where actual service reach is significantly lower than expected given the area's population, accessibility, capacity, and other contextual factors.

UNSEEN addresses the following research problem:

> **How can heterogeneous demographic, socioeconomic, geographic, accessibility, service-capacity, and historical utilization data be combined using Machine Learning to detect areas with significant hidden gaps in public-service reach, explain the factors associated with those gaps, and provide an interpretable spatial prioritization mechanism for intervention?**

---

## 💡 Core Concept

```text
Public Service Data
        +
Demographic & Socioeconomic Data
        +
Geospatial & Accessibility Data
        +
Historical Utilization
        ↓
  Feature Engineering
        ↓
 Machine Learning Model
        ↓
  Expected Service Reach
        ↓
Expected Reach ↔ Observed Reach
        ↓
 Opportunity Gap Score
        ↓
   Explainable AI
        ↓
    GIS Dashboard
        ↓
Potential Hidden Service Gaps
```

---

## 🔬 Research Focus

The primary research focus of UNSEEN is to investigate whether heterogeneous public-service, demographic, socioeconomic, accessibility, geographic, and historical utilization data can be used to identify areas where the observed service reach is significantly lower than the expected reach.

The project will investigate:

- Which factors contribute most to predicted opportunity gaps?
- Which Machine Learning models are most suitable for estimating expected service reach?
- Can Explainable AI provide interpretable insights into model predictions?
- How effectively can spatial analysis identify potential hidden service gaps?
- Can the proposed framework generalize across different geographic regions?
- How can opportunity-gap analysis support evidence-based prioritization?

---

## 🧠 Key Technologies

| Component | Technology |
|---|---|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, XGBoost |
| Explainable AI | SHAP |
| Geospatial Analysis | GeoPandas, QGIS |
| GIS Visualization | Folium |
| Data Visualization | Plotly |
| Dashboard | Streamlit |
| Database | PostgreSQL / PostGIS |
| Version Control | Git & GitHub |

---

## 📊 Planned Outputs

UNSEEN aims to provide:

- Opportunity Gap Score for geographic areas
- Expected vs. observed service reach analysis
- Identification of potential high-gap areas
- SHAP-based explanations of model predictions
- GIS-based visualization of spatial opportunity gaps
- Comparative evaluation of Machine Learning models
- Feature-level analysis of factors associated with predicted gaps
- Spatial prioritization of areas for further investigation
- An interactive decision-support dashboard

---

## 🏗️ Proposed Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Geospatial Integration
      ↓
Feature Engineering
      ↓
Expected-Reach Modelling
      ↓
Gap Detection
      ↓
Opportunity Gap Scoring
      ↓
Explainable AI (SHAP)
      ↓
GIS Visualization
      ↓
Spatial Prioritization
      ↓
Decision-Support Insights
```

---

## 📐 Opportunity Gap

The central concept of UNSEEN is the difference between the service reach that is expected for an area and the service reach that is actually observed.

```text
Opportunity Gap = Expected Service Reach - Observed Service Reach
```

A larger difference indicates a stronger signal that the area may require further investigation. The **Opportunity Gap Score (OGS)** will be used to represent the relative magnitude of this gap and categorize areas according to their potential level of service under-reach.

> **Note:** An identified opportunity gap is treated as a predictive/statistical signal and does not establish a causal relationship or definitively classify a community as underserved.

---

## 🌍 SDG Alignment

**Primary SDG:** SDG 10 — Reduced Inequalities

UNSEEN primarily aligns with SDG 10 — Reduced Inequalities by helping identify geographic areas where public-service reach may be unequal or unexpectedly low.

Depending on the selected pilot service domain, the framework may also contribute to:

- SDG 3 — Good Health and Well-being
- SDG 4 — Quality Education
- SDG 1 — No Poverty
- SDG 11 — Sustainable Cities and Communities

---

## 🔐 Responsible AI

UNSEEN is designed as a decision-support and prioritization framework, rather than an automated policy-making system. The project will consider:

- Use of aggregated or appropriately anonymized data
- Protection of personally identifiable information
- Transparency of model predictions
- Explainability of important features
- Potential geographic and demographic bias
- Prediction uncertainty
- Distinction between correlation and causation
- Human involvement in interpreting results
- Responsible use of predictions for further investigation

---

## 📌 Scope

The initial implementation will focus on one clearly defined public-service domain and geographic study area using public or appropriately anonymized datasets.

**The initial prototype will focus on:**

- Public-service reach analysis
- Demographic and socioeconomic context
- Geographic accessibility
- Service capacity
- Historical utilization
- Machine Learning-based expected-reach estimation
- Opportunity Gap Score generation
- Explainable AI analysis
- GIS-based visualization

**The framework is designed to be transferable to other public-service domains such as:**

- Healthcare
- Education
- Welfare
- Skill development
- Transport

The initial implementation will be developed as a research prototype, rather than a production government system.

---

## 📈 Evaluation

UNSEEN will compare baseline and advanced Machine Learning approaches.

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

### Regression Metrics
- MAE
- RMSE
- R²

### Additional Evaluation
The project will also evaluate:

- Model calibration
- Prediction errors
- Feature-group ablation
- Spatial validation
- Model generalization across geographic regions
- Explainability and feature importance
- Expected vs. observed service reach

---

## 🚧 Project Status

- **Status:** In Development 🚀
- **Project Type:** Micro Project / Research Prototype
- **Domain:** Artificial Intelligence • Machine Learning • Explainable AI • GIS • Public-Service Analytics
- **Primary SDG:** SDG 10 — Reduced Inequalities

---

## 👥 Team

- Mohammad Kaif
- Kanishka Butolia
- Rishi Sharma

**Department of CSE – AIML**
Bharati Vidyapeeth's College of Engineering, Delhi

---

## 🎯 Vision

UNSEEN aims to make hidden gaps in public-service delivery visible through Artificial Intelligence, Explainable AI, and spatial intelligence — helping transform public-service monitoring from simple reporting into evidence-based identification and prioritization of potential service gaps.