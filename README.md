# Efficient (Agentic) Models: Preliminary Literature Search  

## Overview  
This project explores **small-scale, efficient SLMs** (1B-3B parameters, ideally ~1B) with a strong focus on **tool-calling capabilities**. The goal is to **keep all domain knowledge out of the LLM**, ensuring it acts as an intelligent agent rather than a static knowledge store.  

## Scope & Objectives  
- **Model Size:** Prioritizing models as small as possible (~1B parameters preferred), up to 3B.  
- **Input Format:** Natural language.  
- **Functionality Focus:** Strong emphasis on **tool-calling efficiency** over raw knowledge storage.  
- **Evaluation Criteria:**  
  - **Size & Hardware Constraints:** Filtering models based on customer requirements.  
  - **Open Access (OA) & Licensing:** Identifying models suitable for enterprise use.  
  - **Specialization:** Highlighting models optimized for specific tasks.  
  - **Performance:** Assessing tool-calling efficiency and adaptability.  

## Research Approach  
1. **Literature Review:** Survey existing models with an emphasis on **small, efficient architectures**.  
2. **Model Evaluation:** Analyze available benchmarks, focusing on tool-usage effectiveness.  
3. **Feature Comparison:** Build a comparative table of small LLMs based on:  
   - Size  
   - Licensing  
   - Specialization  
   - Tool-calling efficiency
   - TBC 
4. **Customer-Oriented Curation:** Compile a **filtered list** of models suited for enterprise needs.    

## Deliverables  
- A structured **summary of SLMs** with key features (WIP).  
- Recommendations on **which models fit specific customer constraints**.  
- Insights on **tool-calling optimization** in small-scale LLMs.  

## Model Comparison 
🔗 [View models.csv](https://docs.google.com/spreadsheets/d/1OMOy-4koOl3Hf6ztonMSDUYjFZi7TF85eZQdu7N6GqQ/edit?usp=sharing) this 

tool_calling_table - Sheet2.csv are copied from Berkeley Function-Calling Leaderboard [url](https://gorilla.cs.berkeley.edu/leaderboard.html) 
manual add one column with model size.

## Future Work  
- Evaluate selected models with real-world tool-calling tasks.  
- Conduct benchmarks on performance vs. hardware constraints.  
- Identify gaps and opportunities for further research in **agentic SLMs**.  

## Contributing  
If you're interested in contributing, feel free to open an issue or submit a pull request with relevant research findings!  

## License  
TBD (subject to model licensing constraints).  

## Reference
1. SMALL LANGUAGE MODELS: SURVEY, MEASUREMENTS, AND INSIGHTS (Sep 2024). Focusing on transformer-based, decoder-only language models with 100M–5B parameters, they survey 59 state-of-the-art open-source (as for open weights) SLMs. [url](https://ubiquitouslearning.github.io/TinyLLMLeaderBoard/#/slm)
2. Berkeley Function-Calling Leaderboard [url](https://gorilla.cs.berkeley.edu/leaderboard.html)
3. tbc
