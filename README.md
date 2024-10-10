<h1 align="center">ADHD-Ontology</h1>

## Purpose

The purpose of the ADHD ontology is to provide a structured, formal, and comprehensive representation of the concepts and aspects associated with Attention Deficit Hyperactivity Disorder. It aims to assist healthcare professionals, researchers, and educators in gaining a deeper understanding of the disorder, including topics such as symptoms, potential causes, and prognoses. Through this information, the mentioned professionals are expected to better comprehend the behavioral and diagnostic aspects of the disorder, ensuring more precise and effective interventions.

## Scope

The ontology focuses on the health domain, specifically ADHD. It covers the DSM-5 criteria related to the disorder, including symptoms, diagnosis, risk factors, prognosis, and associated characteristics.

## Language

The ontology was implemented using both the OntoUML language with the Visual Paradigm tool and the OWL language with the Protégé tool.

## Inteded users

User 1. Healthcare professionals such as doctors, psychiatrists, psychologists, neurologists, and therapists who use the ontology to assist in diagnosing patients with ADHD.

User 2. Academic researchers who study the disorder and analyze behavioral patterns related to ADHD.

User 3. Families of patients with ADHD who can use the ontology as a clear source of information about the disorder.

User 4. Developers of health systems who will integrate the ontology into clinical decision support systems.

## Intended uses

Use 1. Provide a structured and accessible graphical representation of the symptoms, diagnoses, and prognoses related to the disorder.

Use 2. Facilitate the identification and categorization of symptoms and diagnoses according to the DSM-5 criteria.

Use 3. Provide medical diagnostic support through systems that use the ontology to correlate symptoms and risk factors to ADHD diagnoses.

Use 4. Assist in clinical research by offering a formal structure for the categorization of ADHD cases in clinical studies.

## Justification for the Use of Design Patterns in the ADHD Ontology

In this ontology, different **Design Patterns** were applied to capture the inherent complexities of Attention Deficit Hyperactivity Disorder (ADHD) and its associated factors. Each pattern was strategically used to properly model the categories and relationships involved. Below, we justify the use of the main patterns adopted:

### Subkind Pattern

The **Subkind Pattern** is used to represent variations of an entity that share common characteristics but have specific subtypes. In the context of ADHD, it was applied to the following entities:
- Dysfunction.
- Potential Cause.
- ADHD Classification.
- DSM-5 ADHD valid symptom criteria.
- DSM-5 ADHD diagnostic criteria.
- Fetal drug exposure.
- ADHD risk factor.
- Child ADHD signal.
- ADHD signal intensifier.
- Teen/Adult ADHD signal.
- Legal Drugs.
- Illegal Drugs.
- DSM-5 ADHD inattention symptom.
- DSM-5 ADHD hyperactivity/impulsivity symptom.

These entities represent subtypes that belong to a general category, such as symptom classifications or risk factors, and exhibit specific variations. The **Subkind Pattern** was chosen to allow these variations to be modeled as subtypes, ensuring a clear distinction between different symptoms and factors affecting ADHD diagnosis.

### Category Pattern

The **Category Pattern** was used to model abstract categories that group different classes or individuals without specifying concrete subtypes. This pattern was applied to the following entities:
- Patient With ADHD
- Patient
- ADHD
- Drugs

These categories represent broad concepts that aggregate various instances or subcategories within the ontology. For example, the category Patient encompasses all patients, while Drugs groups all types of substances, both legal and illegal. The 8*Category Pattern** was used to model these concepts in a more general and abstract way, allowing greater flexibility in representing the elements.

### Relator Pattern / Relational Dependence Pattern

The **Relator Pattern** (or **Relational Dependence Pattern**) is used to model situations where two or more entities are interrelated in a dependent manner. In the ADHD diagram, this pattern was applied to the following entities:
- Self-medication
- DSM-5 ADHD combined symptom

These entities reflect a relational dependence, such as the relationship between ADHD combined symptoms and diagnostic criteria, or between a patient and self-medication. The **Relator Pattern** was used to capture these dependencies between elements, ensuring that complex interactions were properly represented within the ontology.

## Non-functional requirements

NFR1 - The ontology must comply with the DSM-5 standard.

NFR2 - The ontology must be made available as open-source on a GitHub repository.

## Functional requirements

CQ1 - Which patients have a specific type of ADHD?

CQ2 - What symptom characteristics make up the DSM-5 diagnostic criteria for ADHD?

CQ3 - What signs of ADHD does a patient have?

CQ4 - What dysfunctions does a patient with ADHD suffer from?

CQ5 - Which patients have self-medicated?

CQ6 - What symptoms does the patient have?

CQ7 - How many patients were diagnosed in childhood?
