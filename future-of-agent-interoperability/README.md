## Kate Blair, Ismael Faro \- IBM \- 4:30pm \- 5:00pm {#kate-blair,-ismael-faro---ibm---4:30pm---5:00pm}

| The future of agent interoperability |  |
| ----- | :---: |
| 4:30pm \- 5:00pm | Kate Blair, Ismael Faro |
| Developers are building AI agents at an incredible pace, tackling complex tasks in research, planning, and software engineering. Yet, the landscape remains fragmented across different frameworks, interfaces, and runtimes—making it difficult for agents to work together.   In this talk, we propose open protocols that allow AI agents to communicate and work together, regardless of their implementation. These protocols enable agents to exchange messages, share relevant information, and collaborate effectively. By standardizing how agents interact, we can unlock a truly open agent ecosystem where interoperability drives innovation.   The session will feature **live demos** showcasing how these protocols enable agent discovery and composition, followed by an open discussion where participants can provide feedback and help shape the future of this standard.   Join us to help build the future of open agent development\!   |  |
| Workshop Links:  Deeplearning.ai Courses: Coming Soon\!  |  |


- AI agent land scape, rapidly growing and becoming more fragmented, not compatible
- How can we get value from atomic parts?
  + What if we could discover and try agents from different frameworks?
  + What if we could compose existing specialized agents?
  + What if we could swap new agents into existing systems when better ones arrived?
- The "unlock" is to standard agent to agent communication
- They've been thinking alot about this, inspired by MCP (Model context protocol)
  + "ACP will follow MCP"
- How to build ACP
  + Standing on the shoulders of giants
    - JSON-RPC
    - Language Server Protocol
  + Leverage ecosystem
    - MCP
    - Natural Language Interaction Protocol
    - Agent Connect Protocol (from AGNTCY) 
  + Feature driven approach
  
- "BeeAI" is the platform they have been implementing for this
  + ACP Pre-Alpha, MCP is extended for Agents
  
- https://github.com/i-am-bee/beeai
  + https://github.com/i-am-bee/beeai/pull/282
  
- DEMO showing iambee - agent registering, agent communication