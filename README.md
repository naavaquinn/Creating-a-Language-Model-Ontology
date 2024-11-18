# Large Language Model (LLM) Ontology

## Introduction to the LLM Ontology
The Large Language Model Ontology provides a structured framework for understanding key aspects of large language models (LLMs). It is designed to support researchers, students, and enthusiasts by offering a clear and accessible view of LLMs. This ontology covers critical elements such as architecture, performance metrics, and applications, providing a foundational understanding of LLM functionality. It serves as an overview of the LLM domain and can act as a starting point for future ontologies on this topic.

## Development Process
The ontology was constructed through an iterative process that involved reviewing existing ontologies, notably the BioPortal Artificial Intelligence Ontology. Competency questions guided our development, helping us identify essential concepts and relationships in the LLM domain.

### Competency Questions
To ensure comprehensive coverage, we formulated the following competency questions:
1. What optimization algorithms can be used to train LLMs?
2. What are strategies for mitigating computational resources when training LLMs?
3. What is the environmental impact of LLMs?
4. How many parameters are used in LLM training?
5. In which domains can LLMs be applied?
6. What architectures are commonly used in LLMs?
7. Which evaluation metrics assess LLM performance?
8. What challenges are associated with developing LLMs?

These questions clarified key attributes, classes, and relationships needed for the ontology.

## Ontology Structure

### Key Classes
- **LLM Tasks**: Represents functions such as question answering, summarization, and code generation.
- **Architecture**: Design types like transformer-based models.
- **Training**: Covers training methods, including supervised learning and optimization techniques.
- **Training Data**: Types of data used for training, such as text and multimodal data.
- **Challenges**: Ethical issues, bias, and environmental concerns.
- **Evaluation Metric**: Human and performance metrics for evaluating LLMs.

### Key Properties
The ontology includes essential properties to define relationships between classes:
- **hasArchitecture**: Links an LLM to its architecture.
- **hasTrainingData**: Associates an LLM with its training data.
- **hasParameters**: Specifies the number of parameters in the LLM.
- **hasChallenge**: Links to challenges like bias or environmental impact.

### Key Individuals
Notable individuals represented in the ontology include:
- **LLMs**: BERT, GPT-4, T5
- **Training Data**: Common Crawl, BookCorpus
- **Computational Resources**: GPU, TPU

## Addressing Competency Questions
The ontology effectively addresses the competency questions by defining relevant classes, properties, and relationships. It captures essential characteristics of LLMs, the role of transformer architectures, the significance of training phases, and factors like training duration, corpus size, and environmental impact.

### Example Competency Questions Answered Using Protégé
Using Protégé, the ontology can answer the following competency questions:
- **What is the architecture used by GPT-4?**  
   Querying `hasArchitecture` for GPT-4 returns: *Transformer-based -> Decoder only*
- **What training data was used for BERT?**  
   Querying `hasTrainingData` for BERT returns: *BookCorpus* and *Wikipedia*
- **What challenges are associated with LLMs?**  
   Querying `hasChallenge` returns challenges like *Bias* and *Environmental Impact*

These examples show how the ontology can directly answer key competency questions using Protégé’s query capabilities.

## Ontology Visualization
The ontology was saved as an OWL document and visualized in Protégé. A comprehensive view of the ontology structure is available in the file `index-all.html`, which details the relationships among various components. An expanded version with additional insights is also included.

## Challenges
During development, we encountered several challenges, including disjoint errors within our classes and a recurring 'OWL nothing' error. Upon investigation, we determined that these issues were related to language tags. Validation was conducted using SHACL (Shapes Constraint Language), and we are pleased to report that our ontology conforms to all SHACL validation requirements, as confirmed by the HermiT reasoner.

---

This project provides a robust foundation for understanding and extending ontologies in the LLM field. We hope it supports both educational and research purposes in exploring the capabilities and implications of large language models.
