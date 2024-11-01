# Competency Questions for Evaluating Information Ontologies

This document outlines the purpose and scope of competency questions used to evaluate existing information ontologies. These questions may be used for building new ontologies but are primarily for assessing the effectiveness, coverage, and structure of current ones.

## Background

Competency questions serve as a tool for testing and validating the knowledge captured by an ontology. They help determine whether an ontology is fit for purpose by asking targeted questions about its ability to answer relevant queries. This approach ensures that the ontology covers the necessary concepts and relationships within a given domain.

At the start of this evaluation process, several key questions were identified:

- **What is the purpose of the evaluation?**  
  The goal is to evaluate the strengths and limitations of existing information ontologies. These competency questions help assess whether the ontology can answer important domain-specific queries and identify gaps or inconsistencies in its structure. 

- **What is the end goal?**  
  The competency questions aim to provide insights into how well the existing ontologies meet their intended purposes. They help highlight areas for improvement, providing feedback that can inform future iterations or guide the selection of ontologies for specific applications.

## Contribution to the Community

This evaluation process, grounded in competency questions, serves as a contribution to the broader ontology community. By carefully documenting how well existing information ontologies address key questions, we can:

1. **Enhance Understanding of Information Ontologies**:  
   These questions help clarify the scope and accuracy of existing information models. They test whether the ontologies align with best practices and capture the necessary relationships and concepts. They can also reveal how some information ontologies might be better suited to modelling for certain use cases than other information ontologies. 

2. **Provide Documentation for Design Patterns**:  
   Beyond the evaluation, the results can be used to document successful design patterns within the ontologies. This documentation can serve as a reference for other ontology developers, ensuring consistent and high-quality design practices.

   By positioning this work as a contribution to the broader ontology community, it helps not only to understand existing models but also to promote better practices in evaluating and improving ontologies. The process is analogous to well-known case studies in ontology evaluation, where competency questions provide a structured method for assessing top-level ontologies.

## Theories and Evaluation Approaches

The evaluation is informed by existing theories and approaches within ontology evaluation. By comparing how various methods address these competency questions, we can develop a clearer understanding of the strengths and weaknesses of different ontologies.

This comparative analysis allows us to contribute a more nuanced perspective to the evaluation of information ontologies, ensuring that the assessment is robust and comprehensive.




IEO The Information Entity Ontology, part of the Common Core Ontologies, emphasizes information bearers that carry Content Entities (ICEs) with specific text values, facilitating structured descriptions and unique identifications of entities.

The Ontology for Biomedical Investigations (OBI) is an OBO foundry ontology designed to provide a shared terminology for scientific investigations in the biomedica domain. OBI includes more than 2500 terms, imports and adapts many terms from already existing OBO Foundry ontologies, and mutuates part of its information model from IAO. Nevertheless, OBI also substantially extends from IAO and introduces new classes of information entities, thus warranting a separate discussion of its information model.

QUDT The QUDT Ontology, developed by NASA and TopQuadrant, standardizes quantity kinds, units, and dimensions to ensure consistent and interoperable measurement data across scientific and engineering domains.


The competency questions exhibit varying levels of granularity, from high-level inquiries about general processes and entities to detailed questions about specific data attributes and operational contexts. Here’s an outline of how different levels of granularity are represented:

1. **High-Level Granularity**:
   - Some questions are broad, asking for general types of entities and their relationships. For example, CQ1 ("what entities are involved in the spread of information from one information bearer to another?") and CQ2 ("what entities are involved in the spread of information from multi-modal information bearers to a target?") provide a big-picture view of information transfer processes without specifying the types of technologies, formats, or detailed protocols involved.

2. **Intermediate-Level Granularity**:
   - At this level, questions focus on specific interactions or roles within a context. CQs such as CQ6 ("what entities distinguish between statements that direct actions and descriptions that describe existing states?") and CQ11 ("what entities are involved in abstract directives that guide behavior without specific instructions?") introduce more specific distinctions about the types of information or directives involved, moving beyond generic descriptions to include functional or intentional categories.

3. **Fine-Level Granularity**:
   - The most detailed questions examine specific attributes, timestamps, locations, or technological components associated with data or operational processes. For example, CQ18 and CQ19 inquire about "the time, location, and quality requirements for the data" and "details of the data," respectively, demanding precise information such as exact timestamps, specific quality standards, and geographic information. Similarly, CQ20 and CQ21 ask about the timing and delivery locations of data, involving granular tracking of data’s physical or digital movements.

4. **Domain-Specific and Task-Specific Granularity**:
   - Some questions address specialized domains (e.g., CQ13 and CQ17 about data requests under specific authorities or missions) or ask about data’s role in generating and using derived products (CQs 25 and 26). These CQs require both domain knowledge and detailed tracking of data’s lifecycle from collection to utilization, indicating a need for granularity tailored to both procedural and organizational contexts.

This varied granularity enables the ontology to support a wide range of inquiries, from overarching processes to minute, domain-specific details, providing flexibility to meet both high-level and operational data needs.



### Guidelines for Providing Ontology Diagrams

When proposing theories or models in ontology development, providing visual representations is essential for clarity and effective communication. Diagrams are valuable for illustrating relationships, hierarchies, and interactions within complex ontological structures.

#### Recommended Tools and Resources for Diagram Creation

- **[OntoMermaid](https://github.com/floresbakker/OntoMermaid)**: This tool integrates ontology concepts with Mermaid.js, allowing you to create structured diagrams that clearly represent entities and relationships using a syntax specifically tailored for ontology components.

- **[SemanticSketch](https://skreen5hot.github.io/SemanticSketch/)**: An intuitive tool for quickly designing and customizing semantic diagrams. It’s ideal for presentations or documentation, enabling clear and visually appealing representations of ontology structures.

Using these tools helps ensure that ontology proposals are communicated effectively, making the underlying structure and logic of the theory more accessible to stakeholders.
