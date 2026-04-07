<img width="191" height="163" alt="Substance Declaration VDA Logo"
src="https://github.com/user-attachments/assets/f6610f12-2a07-4cbb-bd99-76f156b219e4" />

# Subschema Substance Declaration
🔗 This subschema is part of the **VDA 231‑301 open JSON standard ecosystem**
➡ https://github.com/VDA231-301

## Purpose and Scope

The **Substance Declaration** subschema is a specialized extension of the **VDA 231‑301 recommendation**.  
It provides a **standardized, machine‑readable data structure** for the exchange of substance‑related information within digital sampling, approval, and regulatory documentation processes.

The subschema enables a **structured JSON‑based data exchange** that supports regulatory information requirements, interoperability across IT systems, and traceability along complex supply chains.

Its main objectives are:
- Transparent representation of the **chemical composition** of materials and articles
- Support of **regulatory information duties** through structured data
- Harmonization of existing substance declaration approaches
- Seamless and automated **data exchange across organizational and industry boundaries**

---

## Position within VDA 231‑301 and Relation to Existing Systems

This subschema is part of the **VDA 231‑301 JSON Schema ecosystem** and builds upon the generic VDA 231‑301 data model.

> [!IMPORTANT]
> ⚠️ **Important clarification:**
> - This subschema defines the **data structure only**.
> - It **does not replace** existing systems or tools.
> - It **does not perform regulatory evaluation, legal interpretation, classification, or compliance decisions**.

The authoritative legal and regulatory interpretation of substance data remains the responsibility of the applicable legal framework and the systems or processes in which the data is used.

Any changes intended to become part of the official VDA 231‑301 recommendation must follow the formal VDA committee and release process.

---

## Regulatory Framework

The obligation to declare substances is driven by international and regional chemicals and product legislation.  
Typical regulatory drivers include (⚠️This list is not intended to be complete):

### European Union
- **REACH Regulation (EC) No. 1907/2006**  
  - Registration obligations for substances  
  - Information duties within the supply chain (Articles 31–33)  
  - Declaration of **SVHC substances** above 0.1% w/w in articles
  - Annex XIV & XVII
- **CLP Regulation (EC) No. 1272/2008**  
  Basis for hazard‑related substance attributes
- **RoHS Directive 2011/65/EU**  
  Substance restrictions for electrical and electronic equipment
- **ELV Directive 2000/53/EC / upcoming ELV Regulation (ELVR)**  
  - Substance restrictions and information requirements for vehicles and vehicle components at end‑of‑life  
  - Obligations regarding the declaration of restricted substances (e.g. heavy metals) in vehicles and materials  
  - Increasing focus on digital, structured substance information to support circular economy, reuse, and recycling concepts  
- **POP Regulation (EU) 2019/1021**  
  - Restriction and prohibition of **persistent organic pollutants (POPs)** in substances, mixtures, and articles  
  - Information duties along the supply chain for articles containing POPs above defined concentration limits  
  - Requirement for traceable substance information to support waste management and end‑of‑life treatment
  

### Other International Regulations (selection)
- **TSCA** (United States)
- **China REACH / MEE Order No. 12**
- **GHS** as the globally harmonized system for classification and labeling

➡️ **Implication:**  
Organizations must provide substance‑related information in a **structured, traceable, and auditable form**.  
The Substance Declaration subschema provides the **technical foundation** for this purpose.

---

## Substance Declaration in the Automotive Industry – IMDS

In the automotive industry, the **International Material Data System (IMDS)** is an established solution for substance and material data exchange between suppliers and OEMs. 

Within this context, the Substance Declaration subschema:
- does not replace or replicate existing domain-specific systems such as IMDS,
- complements existing IMDS‑based processes,
- enables interoperability with other IT systems,
- and supports structured data reuse beyond a single platform.

For **non‑automotive industries**, IMDS serves only as an **illustrative example** of an established substance declaration system.  
The subschema itself is **not tied to IMDS** and can be used independently of automotive‑specific platforms.

---

## Applicability Beyond the Automotive Industry

Although originating from the automotive context, this subschema is **not limited to the automotive industry**.

It is designed as a **generic, industry‑agnostic data model** for the exchange of substance‑related information and can be applied wherever substances, materials, or articles must be declared or documented in a machine‑readable form.

Typical non‑automotive use cases include:
- Chemicals and chemical products
- Electrical and electronic equipment (EEE)
- Consumer goods
- Industrial materials and semi‑finished products
- Construction products
- Regulatory data exchange platforms

By intentionally avoiding assumptions about specific tools, business processes, or regulatory decision logic, the subschema serves as a **neutral interoperability layer** across different industries.

---

## Important Note

> [!IMPORTANT]
> This subschema provides **structured substance‑related data only**.  
> It does **not** perform regulatory evaluation, legal interpretation, classification,
> or compliance decisions.  
> These responsibilities remain with the applicable legal framework and the systems
> or processes in which the data is used.

---

## License 

The VDA 231‑301 JSON schemas, including this subschema, are released under the **MIT License**, allowing free use, modification, and distribution.


## Contributing & VDA Process

Contributions are welcome.

If contributions are intended to become part of the official VDA 231‑301 recommendation, they must follow the formal VDA committee and release process.
This repository hosts a subschema extending the generic VDA 231‑301 JSON schema.

GitHub is used as a platform for collaborative drafting, discussion, and technical refinement.  
Issues and Pull Requests are welcome.

⚠️ Please note:  
Only subschemas that have successfully passed the formal VDA committee and release process may become part of the official VDA 231‑301 recommendation.

Details on contribution rules, governance, and approval processes are described in the organization-wide Contributing Guidelines:  
https://github.com/VDA231-301/.github/blob/main/CONTRIBUTING.md
