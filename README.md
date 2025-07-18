# UMLS-Ontology-Inconsistency-Detector

This project focuses on detecting logical inconsistencies in the Unified Medical Language System (UMLS) by analyzing its hierarchical relationships. Specifically, the system identifies and reports:

Parent-Child Loops: Cycles in the concept hierarchy that indicate circular relationships.
Broader-Than Conflicts: Cases where two concepts claim to be broader than each other, which violates the ontology's directional structure.

The goal of this analysis is to support cleaner, more reliable biomedical ontologies by identifying errors that could affect research, healthcare systems, and clinical applications.

---

## Dataset Used

- **File**: `MRREL.RRF`
- **Source**: UMLS Metathesaurus
- **How to Get It**:
  1. [Request a UMLS license here](https://uts.nlm.nih.gov/license.html)
  2. After approval, log in and download the full UMLS release (e.g., `umls-2024AB-full.zip`)
  3. Run the MetamorphoSys tool included in the release to extract `.RRF` files
  4. Locate and use the generated `MRREL.RRF` file

> Note: You must agree to the terms of the UMLS license before using this data.
