<img width="191" height="163" alt="Substance declaration VDA-Logo" src="https://github.com/user-attachments/assets/f6610f12-2a07-4cbb-bd99-76f156b219e4" />

# Subschema Substance Declaration

## Purpose and Scope

The **Substance Declaration** subschema is part of the **VDA 231‑301** standard and provides a **standardized, machine‑readable representation of substance‑related information** within digital sampling and approval processes.

It enables a **structured, JSON‑based data exchange** that supports regulatory requirements, integrates established industry solutions (e.g. IMDS), and remains **applicable across different industries**.

The main objectives of the subschema are:

- Transparent representation of the **chemical composition** of materials and articles  
- Support of **regulatory compliance assessments**  
- Harmonization of existing substance declaration approaches  
- Seamless, automated data exchange along the supply chain  

> [!IMPORTANT]
> This subschema provides data only and does not perform regulatory evaluation, classification, or compliance decisions.

---

## Regulatory Framework

The obligation to declare substances is primarily driven by international and regional chemicals and product legislation. Key regulatory drivers include:

### European Union

- **REACH Regulation (EC) No. 1907/2006**  
  Requires manufacturers and importers to identify and communicate information on substances contained in products, in particular:
  - Registration obligations for substances  
  - Information duties within the supply chain (Articles 31–33)  
  - Declaration of **SVHC substances** above 0.1% w/w in articles  

- **CLP Regulation (EC) No. 1272/2008**  
  Governs the classification and labeling of substances and mixtures and forms the basis for hazard‑related attributes.

- **RoHS Directive 2011/65/EU** (for electrical and electronic equipment)  
  Defines substance restrictions with explicit concentration limits.

### Other International Regulations (selection)

- **TSCA** (United States)  
- **China REACH / MEE Order No. 12**  
- **GHS** as the globally harmonized system for classification and labeling  

➡️ **Implication:** Companies must provide substance‑related information in a structured, traceable, and auditable manner. The Substance Declaration subschema provides the technical foundation for this purpose.

---

## Substance Declaration in the Automotive Industry – IMDS

In the automotive industry, the **International Material Data System (IMDS)** has been the established solution for many years:

- Full declaration of the **substance composition** of materials and parts  
- Use of **CAS numbers** for unambiguous substance identification  
- Hierarchical data structure (part → material → substance)  
- Mandatory for nearly all automotive OEMs  

### Relationship to VDA 231‑301

The Substance Declaration subschema:

- Is **conceptually compatible** with IMDS  
- Represents core IMDS information in a **neutral and standardized form**  
- Is **system‑ and industry‑independent**  
- Enables **integration of IMDS data** without replicating or replacing the IMDS system  

➡️ The objective is **interoperability**, not replacement.

---

## Substance Declaration Outside the Automotive Industry

Outside the automotive sector, **no single global system** comparable to IMDS exists. Instead, various heterogeneous approaches are used:

### Electronics & Consumer Goods

- IEC 62474 / Declarable Substance List (DSL)  
- XML‑based substance declarations  
- Strong focus on restricted substances and compliance statements  

### Chemical Industry

- Safety Data Sheets (SDS)  
- Formulation and mixture information  
- Highly regulated, but predominantly **document‑based rather than data‑driven**  

### Construction Products, Textiles, Medical Devices

- Sector‑specific regulatory requirements (e.g. CPR, MDR)  
- Often project‑specific Excel or PDF‑based declarations  

➡️ These approaches are characterized by **high heterogeneity**, limited automation, and low interoperability.

---

## Role of the Substance Declaration Subschema

The Substance Declaration subschema addresses these challenges by providing:

- A **JSON‑based exchange format**  
- Unambiguous substance identification (e.g. CAS number)  
- Structured specification of:
  - Substance content  
  - Concentration values or ranges  
    
The subschema is therefore:

- **Applicable across industries**  
- **Extensible** for additional regulations or use cases  
- Suitable as a **common data language** between OEMs, suppliers, IT systems, and regulatory reporting processes  

---

## Relation to the VDA 231‑301 Overall Standard

Within VDA 231‑301, the Substance Declaration subschema represents a **core functional component** and is typically used in combination with:

- Sampling and approval workflows
- Material and substance schemas  
- Compliance and evaluation logic  


It directly supports the strategic objective of VDA 231‑301:

> **End‑to‑end digital, standardized material and substance data across the industrial value chain.**

---

## Target Audience of This Repository

- OEMs and suppliers  
- Software and platform providers  
- Standardization and expert bodies  
- Regulatory and compliance specialists  

----
## Explicit Non-Goals

The Substance Declaration subschema is intentionally limited in scope.

It does **not**:

- Perform regulatory, toxicological, or legal evaluations  
- Determine regulatory compliance or conformity  
- Replace or replicate existing domain-specific systems such as IMDS  

The subschema focuses exclusively on the **standardized exchange of substance-related data**.
Any legal interpretation, assessment, or compliance decision remains the responsibility of the data-providing organization and its downstream users.

---
## Disclaimer

This repository provides a **technical data schema** only and does **not constitute legal advice**.  
Responsibility for regulatory interpretation and compliance remains with the data‑providing organization.
