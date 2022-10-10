# pediatric_oncology_EHR

Due to the sensitive nature of patient data, I cannot include my code in public repository. It is maintained in an internal UCSF repository. I'm sharing this abstract to provide some details on the project.

**Identifying social risks from notes in the Electronic Health Record and evaluating associations with emergency department visits**

Benjamin Lacar, Lena E. Winestone, Dmytro S. Lituiev, Sarah F. Ackley, M. Maria Glymour, Jonathan T. Kolstad, Matthew S. Pantell, Laura M. Gottlieb, Emilia De Marchis

**Introduction** Relationships between adverse social determinants of health, or social risks, and pediatric cancer outcomes are complex. While the impact of social risks on adult cancer outcomes is well-documented, the mechanisms for how social risks affect pediatric oncology patients have been less studied. Research on the associations between pediatric cancer and social risks has relied primarily on social risk data from patient/caregiver self-reports, community-level databases, birth records, and electronic health record (EHR) structured fields. The known limitations of these sources have spurred interest in extracting social risk data from clinical notes. Using clinical text to identify patients' social risks will improve understanding of how they contribute to pediatric cancer outcomes.

**Methods** We used natural language processing (NLP) to mine social risk data from social worker notes for several domains, including family structure, financial strain, food, housing, and utilities. We then used the identified social risk factors as predictor variables in generalized linear models (GLMs) to explore their associations with febrile neutropenia or emergency department visits obtained from EHRs.

**Results** The NLP method of textual entailment was applied for all social risk domains, with family structure/social support having the best precision across domains (0.770). Using binomial and Poisson GLMs, we find that social risk factors of non-English language preference, having siblings, or having a proxy for financial strain mentioned (“SSI” or supplemental security income) were significantly associated with emergency department visits. SSI mention was also associated with febrile neutropenia diagnoses in unadjusted models.

**Discussion** Using EHR, we find social risks captured by social worker notes to be associated with a health utilization outcome (ED visit). However, identifying results outside pediatric oncology clinical teams’ awareness was elusive. While family structure was well-documented, the relative infrequency of other social domains, including data on household material hardship (food, housing, energy insecurity), in notes precludes identifying new associations with pediatric oncology outcomes. However, additional research using other entailment hypotheses or natural language processing methods may maximize the family structure information that can be extracted.

**Conclusion** Findings related to family structure and financial strain confirm the challenges that families and clinical teams must overcome with a child’s cancer diagnosis. Future research could help improve the documentation of social risk information by clinical teams and novel analytic approaches to EHR analyses may better surface data on social risks and related care in childhood cancer settings.
