## Jeff Huber \- Chroma \- 4:00pm \- 4:30pm {#jeff-huber---chroma---4:00pm---4:30pm}

| Teach Chroma how to play Doom |  |
| ----- | :---: |
| 4:00pm \- 4:30pm | Jeff Huber |
| Can retrieval play Doom? Come learn about instruction retrieval as an example of agentic memory. Code will be provided.   |  |
| Workshop Links: Deeplearing.ai Courses: [Advanced Retrieval for AI with Chroma \- DeepLearning.AI](https://www.deeplearning.ai/short-courses/advanced-retrieval-for-ai)  |

- Can we do code golf (using only memory, no reasoning models) to create a system that can learn how to play doom?
 
  
- What is memory
  + Ability to remember and recall
  + Makes context window dynamic to the context
  + Real-time updatable
  + Interpretable
  
- Poor man RLHF
  + Memory
    - Observe state
    - Decide on actions
    - Execute on actions
    - Observe actions
    
    
- Step 1: play the game and record frame-action pairs (training)
  + Played doom level 8 times
  + Frame -> Action
  + Embedded frame, stored with keyboard input
  
- Step 2: Use recorded frame-action pairs to play the game
  + For every few frames, try to find a similar one, do related action
  
- Step 3: (Not implemented here) - iterate instruction set towards a goal/reward
   
   
Code will be open sourced tomorrow: https://github.com/jeffchuber/chroma-doom

< Watching cool demo video of it trying to play Doom with this simple system >
