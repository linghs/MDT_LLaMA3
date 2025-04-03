# MDT_LLaMA3
## Extracting Diagnose and Treatment Decision Tree from Medical Text Using Large Language Model
## Abstract ##
- :deciduous_tree: The clinical decision tree is a pivotal tool in medical decision-making, aiding clinicians in navigating complex clinical scenarios. 
- :brain: Current methods for extracting decision trees predominantly utilize large language models (LLMs) for their contextual understanding and generative capabilities derived from clinical guidelines. However, these generalized LLMs face significant challenges in medical decision tree extraction, particularly in: 1) Interpreting complex semantic relationships within medical decision nodes, and 2) Extracting intricate interrelationships among these nodes.
- :bulb: To address these challenges, we propose a novel **Medical Chain-of-Thought Transfer Learning (MedCoT-TL)** paradigm. This approach simplifies cognitive processing by decomposing tasks into granular subtasks and applying domain-specific transfer learning.
- :gear: Our methodology involves: 1) Transfer training across foundational medical NLP taxonomies, 2) Decomposing the decision tree extraction task into subtasks such as triplet node extraction, decision tree node identification, and tree reconstruction, and 3) Enhancing instruction diversity for decision tree generation.

---

## :fire: News ##
- [03-14-2025] GitHub repository released! Stay tuned for updates and code availability.

---
### Model Architecture ###
![model](https://github.com/linghs/MDT_LLaMA3/blob/main/framework.png)
---
