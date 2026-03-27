LLM -
  - Memory
  - Reasoning
  - Tool USe
  - Loop

Agent -
  - 


Context engineering-
- LLM outputs are entirely driven bu inputs , so getting the right inputs so LLM can achieve the goals in the most optimum way is called context engieering
- Difference between prompt engineering and context engineering
- Context engineering
  - Complex inputs
  - Guides LLM by setting
     - System prompt (role,contraints,rules,tone)
     - Tools - description of capabilities
     - memory :resources that persist
     - converstation history
     - agents.md(coding agents)
   -Agents.md
    - markdown file hat is easy for LLM to read
    - it generally inside projects root directly and acts as a context for llm to read instruction
    - but it can be in each sub directory
    - it follows hierarchy by overridding agents md from inner most sub directory
   
Workflows for coding agents -
  - SDD - specs driven development ->add a detailed specs to gude llm
  - Plan - execute - review - test -> Run each activity with agent with manual touchpoints using feedbacks
  - Yolo - give it one task and ket the agent completet it will full autonomy
  - Ralph loops - describe the outcome and let agent run recursively to find out if its achieved
    

