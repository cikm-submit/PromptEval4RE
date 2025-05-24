# PromptEval4RE: CIKM 2025 Submission

This is the official repository for our CIKM 2025 paper submission.

## 📄 Summary

In this work, we:

- Design controlled experiments to evaluate four key aspects of prompt design for relation extraction (RE):  
  1. Semantic relevance of candidate relation types  
  2. Size of the candidate relation set  
  3. Semantic similarity of in-context examples  
  4. Number of in-context examples in few-shot prompts

- Introduce **PromptEval4RE**, a modular evaluation pipeline that dynamically constructs prompts based on configurable settings and systematically evaluates LLMs on RE tasks.  
  

- Conduct 144 experiments across 12 prompt configurations, three RE benchmarks, and four instruction-tuned LLMs (from small to very large).  


## 📁 Repository Structure
├── Dataset/ # Contains three RE benchmarks

│ ├── DBpedia-WebNLG/

│ ├── WebNLG/ 

│ └── Wikidata-TekGen/ 

├── src/ # Codebase for PromptEval4RE components

├── LLM-Output/ # Raw LLM responses and evaluation results

├── performance-measurement.csv # Precision, Recall, F1 scores for all configurations


## 📬 Contact

For questions, please reach out via GitHub issues.

---

*This repository is part of a blind submission to CIKM 2025. Certain details may be anonymized.*
