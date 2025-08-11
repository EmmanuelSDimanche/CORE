# Diagnostic Instruction Set (v1.0)

#### **1. Layer Coverage & Classification**

1.1 Classify every term into **exactly one** category: **Foundational**, **Core**, **Domain**, **Cross-Layer**, or **Trans-Layer**.\
1.2 Mark **Trans-Layer** terms explicitly and justify why they span layers.\
1.3 Confirm no term is unclassified or multiply classified.\
1.4 Check **distribution balance**: no layer overpopulated with redundant terms; no layer sparse on essentials.\
1.5 Verify **misclassification** errors: ensure each term’s function matches its assigned layer.

#### **2. Dependency Mapping**

2.1 Map **upstream dependencies** (what constrains this term).\
2.2 Map **downstream dependencies** (what this term constrains).\
2.3 Detect **orphan terms** (no references either way) and resolve: remove or integrate.\
2.4 Detect **cyclical dependencies** and resolve by introducing an independent anchor term or clarifying scope.\
2.5 Verify **directionality**: no upstream term depends on a downstream term in violation of **Foundational → Core → Domain** flow.

#### **3. Semantic Precision & Style**

3.1 Ensure definitions are **clear, concise, non-overlapping**.\
3.2 Resolve synonym conflicts and merge duplicates.\
3.3 Review **granularity**: split overly broad terms; merge overly narrow ones.\
3.4 Enforce **style compliance**: present tense, authoritative tone, no em dashes in body text, consistent formatting.

#### **4. Reference Model Completeness**

4.1 Cross-check against **all whitepaper sections** for unique terms.\
4.2 Cross-check **diagrams, tables, visuals** for visual-only terms.\
4.3 Cross-check against **COHERE Book** terminology to maintain alignment.\
4.4 Confirm coverage of: **Commitments**, **7-Field Architecture**, **OAO**, **Versioning Logic**, **Readiness Criteria**, **Epistemic Governance**.

#### **5. Temporal Integrity Terms**

5.1 Confirm presence of Field 6 (**Rhythm**) terms.\
5.2 Define **inter-field temporal dependencies** (e.g., Rhythm ↔ Structure/Bridge/Essence).\
5.3 Ensure temporal concepts are expressed at Foundational (principle), Core (grammar), and Domain (metrics) levels where applicable.

#### **6. Propagation, Audits & Validation**

6.1 Define all audit types: **Foundational Audit**, **Core Audit**, **Domain Audit**.\
6.2 Align audit terminology with **Versioning Logic** vocabulary.\
6.3 Define **inheritance**, **activation**, **lock criteria**, **propagation fidelity**, and **failure containment**.

#### **7. Governance & Stewardship**

7.1 Define **epistemic stewardship**, **steward councils**, **change management**, **version control**.\
7.2 Specify roles/responsibilities and decision thresholds for updates.

#### **8. Change History & Evolution**

8.1 Maintain a **versioned change log**: term, date, author, reason, impacted sections.\
8.2 Require **review & approval** before glossary publication for each release.

#### **9. Term Retirement & Deprecation**

9.1 Define **retirement criteria** (obsolete, superseded, inconsistent with Foundational commitments).\
9.2 Mark deprecated terms with a **deprecation note** and a pointer to the replacement term.\
9.3 Retain deprecated terms in a **separate section** for one full major version to preserve backward compatibility.\
9.4 Update alignment files and references to avoid lingering use.

### **Iteration 3 – Gap Test Results**

* **Coverage & Classification:** Complete.
* **Dependencies & Directionality:** Complete.
* **Semantic Precision & Style:** Complete.
* **Reference Model Completeness:** Complete.
* **Temporal Integrity:** Complete.
* **Propagation & Audits:** Complete.
* **Governance & Stewardship:** Complete.
* **Change History:** Complete.
* **Retirement & Deprecation:** Complete.
