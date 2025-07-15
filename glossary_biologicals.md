# Glossary — Life Science Data & Lab Informatics

A shared vocabulary covering both my GS-KO in silico project and EPAM/Syngenta lab digitalisation workflows. Wherever possible, terms are linked to artefacts in this portfolio.

---

## A–B

### Assay  
**Definition:** A laboratory test or experiment to measure a specific property (e.g., concentration of a compound) in a sample.  
**See:** [Context Diagram](./system_artifacts/context_diagram.png), [Jira Kanban Board](./business_artifacts/jira_kanban_biolord.png)

### Audit Trail  
**Definition:** A traceable record of data changes showing who did what and when, supporting compliance and debugging.  
**See:** [`cloud_artifacts/`](./cloud_artifacts/), concept in [System Overview](./system_artifacts/system_overview.md)

### Batch  
**Definition:** A defined collection of samples processed together in a run or experiment.  
**See:** [Data Dictionary](./system_artifacts/data_dictionary.md)

---

## C–D

### COBRApy  
**Definition:** An open-source Python package for constraint-based metabolic modeling and Flux Balance Analysis.  
**See:** [Pipeline BPMN](./system_artifacts/pipeline_bpmn.png), [ER Diagram](./system_artifacts/er_diagram.png)

### Data Lake (S3 Bucket)  
**Definition:** A centralized storage for raw or processed data (e.g., Amazon S3) used for large-scale analytics.  
**See:** [`cloud_artifacts/`](./cloud_artifacts/)

### Data Quality (QC)  
**Definition:** Checks and validation rules to ensure lab or assay data are accurate, complete, and reliable.  
**See:** [`qa_artifacts/`](./qa_artifacts/)

---

## E–G

### ETL (Extract, Transform, Load)  
**Definition:** A data pipeline process that extracts data from sources, transforms/cleans it, and loads it into a database or data lake.  
**See:** concept in [System Overview](./system_artifacts/system_overview.md)

### Fermenter  
**Definition:** A bioreactor used for growing cells or microorganisms under controlled conditions.  
**See:** [Stakeholder Matrix](./business_artifacts/stakeholder_matrix.png)

### FieldScan  
**Definition:** A sensor-based imaging system for collecting plant phenotype data (e.g., NDVI) in the field.  
**See:** Syngenta use case (Glossary term)

---

## F–G (cont.)

### FBA (Flux Balance Analysis)  
**Definition:** A computational method for simulating metabolic fluxes in a cell using genome-scale models.  
**See:** [Pipeline BPMN](./system_artifacts/pipeline_bpmn.png)

### gRNA (Guide RNA)  
**Definition:** A short RNA molecule in CRISPR technology that directs the Cas9 protein to a specific DNA sequence.  
**See:** [ER Diagram](./system_artifacts/er_diagram.png)

---

### Glue (AWS Glue)  
**Definition:** A managed ETL (Extract, Transform, Load) service by AWS for automating data preparation and loading.  
**See:** concept in [System Overview](./system_artifacts/system_overview.md)

---

## L–N

### LIMS (Laboratory Information Management System)  
**Definition:** Software to track samples, workflows, and associated data in a laboratory setting.  
**See:** [System Overview](./system_artifacts/system_overview.md)

### NDVI (Normalized Difference Vegetation Index)  
**Definition:** A sensor-derived index measuring plant health, based on red and near-infrared reflectance.  
**See:** Syngenta use case (Glossary term), [Stakeholder Matrix](./business_artifacts/stakeholder_matrix.png)

### OD600  
**Definition:** Optical density measured at 600 nm, commonly used to estimate cell density in culture.  
**See:** Syngenta use case (Glossary term)

---

## P–S

### PiggyBac  
**Definition:** A transposon-based system for integrating DNA sequences into eukaryotic genomes.  
**See:** [System Context](./system_artifacts/system_overview.md), [Product Roadmap](./product_artifacts/roadmap_gs_ko.png)

### Plate Reader  
**Definition:** A laboratory instrument that measures optical signals (e.g., absorbance, fluorescence) in microplates.  
**See:** Syngenta use case (Glossary term)

### QC (Quality Control)  
**Definition:** Procedures and tests that ensure data or lab results meet predefined standards.  
**See:** [`qa_artifacts/`](./qa_artifacts/)

### Sample Accessioning  
**Definition:** Registering and labeling samples upon receipt in a laboratory, often the first step in LIMS.  
**See:** [ER Diagram](./system_artifacts/er_diagram.png)

---

## T–V

### Traceability  
**Definition:** The ability to track data or samples from origin through all processing steps.  
**See:** concept in [System Overview](./system_artifacts/system_overview.md)

### User Story  
**Definition:** A structured description of a feature or requirement from the end-user’s perspective, used in Agile workflows.  
**See:** [Jira Kanban Board](./business_artifacts/jira_kanban_biolord.png)

### Vector (Genetic Vector)  
**Definition:** A DNA molecule (e.g., PiggyBac) used to deliver genetic material into a cell.  
**See:** [ER Diagram](./system_artifacts/er_diagram.png)

---

*This glossary ensures alignment between scientific and technical teams by defining critical terms across artefacts.*  

