# Large Language Models (LLMs) Ontology

## Introduction
The LLM Ontology offers a structured framework for understanding key aspects of large language models, supporting researchers, students, and newcomers. Covering architecture, performance metrics, and applications, this ontology provides a foundational understanding of LLMs and serves as a basis for future developments.

## Development Process
The ontology was developed by referencing existing ontologies, including the BioPortal AI Ontology, and guided by competency questions. These questions helped clarify essential classes and relationships.

### Key Competency Questions
1. What optimization algorithms can be used to train LLMs?
2. How can computational resources be mitigated in training?
3. What is the environmental impact of LLMs?
4. How many parameters are used in LLMs?
5. In which domains can LLMs be applied?
6. What architectures are used in LLMs?
7. Which evaluation metrics assess LLM performance?
8. What challenges are associated with LLMs?

## Ontology Structure

### Key Classes
- **LLM Tasks**: Question answering, summarization, etc.
- **Architecture**: Types like transformer-based models.
- **Training**: Methods, e.g., supervised learning.
- **Challenges**: Ethical issues, environmental impact.
- **Evaluation Metrics**: Human and performance metrics.

### Key Properties and Individuals
- **Properties**: `hasArchitecture`, `hasTrainingData`, `hasChallenge`.
- **Individuals**: Models (e.g., BERT, GPT-4), Training Data (e.g., BookCorpus, Common Crawl), Resources (e.g., GPU).

## Usage Examples
Using Protégé, users can query:
- **Architecture of GPT-4**: Returns *Transformer-based -> Decoder only*
- **Training data for BERT**: Returns *BookCorpus* and *Wikipedia*

## Visualization & Challenges
The ontology is visualized in Protégé and available in `index-all.html`. Challenges faced included disjoint errors and language tags, which were resolved. SHACL validation confirmed conformity.

---

This ontology provides a concise foundation for understanding LLMs, their applications, and their challenges.
