
# João Moura - CrewAI - 12:45pm - 2:15pm

- https://www.crewai.com/
  + open source & enterprise hosted solution
  + https://github.com/crewAIInc/crewAI
- 50M AI agents runningon crewai in January
- LLMS great at creating content, but also emerging property of "cognition", make a "Decision" between email 1 and email 2 for reasons

- Agents are at the end of the day automation which was not possible/easy before
  + Starting to deliver on the promise of RPA
  
- What are people using them for?
  - Picture of screenshot, they are seeing usage across all types of verticals/use cases, whether back office, sales, coding whatever...
- How technical are people successfully deploying agents?
   - 47.7% pretty technical
   - 27% not that technical
   - 25.3% Very Technical  

https://console.groq.com/playground
https://learn.deeplearning.ai/courses/crewai-314-workshop

- Use cases:
  + "Pricing updates approval"
    + Azure -> Crew AI -> AlphaSense/Slack -> UiPath
    + 60% precision -> 94% precision after a couple weeks of improvements
  + "Agentic OCR"
    + Documenting classification, scanning and processing
    + Paper (letter, Mail, Money orders, checks) -> CrewAI (OCR/Analysys/Comparison/Classification) -> CrewAI (Priority/Queue/Skillset)
    
  + How to think about use cases
     + Y axis complexity
     + X axis precision
     +   |----------------------------------------------------------------------|
         | High Complexity, Low Precision    |  High Complexity, High Precision-|
         -----------------------------------------------------------------------|
         | Low Complexity, Low Precision     |  Low Complexity, High Precision  |
         |----------------------------------------------------------------------|  
   
+ "Crews" and "Flows"
 + Crews - managed team of agents, tools/tasks
 + Flows - High precision workflows where you can write code that hands off to crews
 
+ Prepare for meetings - "Using Crews to help you prepare for meetings"
  + Used a lot internally
+ Dynamically Writing Docs    
  + Write docs for a whole repo automatically
+ Conversational Flows
  + Uses groq service
  
+ Groq
  + Do not make their own models
  + Groq's secret sauce LPU
    + GPUs are bad at inference, good at training
  
