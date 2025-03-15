## Aman Khan \- Arize \- 5:00pm \- 5:30pm {#aman-khan---arize---5:00pm---5:30pm}

| Beyond Vibe Checks: Rethinking How We Evaluate AI Agent Performance |  |
| ----- | :---: |
| 5:00pm \- 5:30pm | Aman Khan |
| Building an AI agent that works in demos is just the beginning \- the real challenge lies in creating systems that consistently deliver value in production. Drawing from his experience shipping agents across diverse use cases, Aman will share how the Arize team evolved from basic accuracy checks to sophisticated evaluation frameworks that caught subtle failures before they impacted users. You'll learn practical techniques for using LLMs as judges, building automated evaluation pipelines, and establishing development workflows that accelerate iteration while maintaining quality. Whether you're building your first agent or scaling existing ones, you'll leave with concrete strategies for measuring what matters and systematically improving agent performance through thoughtful experimentation. |  |
| Workshop Links: [Google Colab](https://colab.research.google.com/drive/1QxkU0S_cTgJikWK9mAYnHuB8hoe0yAGl) Deeplearning.ai Courses: [Evaluating AI Agents \- DeepLearning.AI](https://www.deeplearning.ai/short-courses/evaluating-ai-agents)  |  |

- "Thrive coding" instead of "Evaling with vibes"

- Three main components of agent system need evaluating
  + "Router"
  + "Skills/Tools"
  + "The path" - loops/steps
  
- Router eval, fairly straight forward
  + Was the right skill picked?
- Skill eval
  + Did the tool/skill yield the desired output from the input?
- The path eval
  + "Convergence"

- bit.ly/arizeaidev
  + https://colab.research.google.com/drive/1OR4qNfhiaFBUWFXsE5sutGOli0JMgjVN#scrollTo=GdDmE6IqWrrS
- phoenix.arize.com

### 1st section, the basics of Arize, evaling the three pieces

See [./arize-dl_ai_devday.ipynb](./arize-dl_ai_devday.ipynb)
  
### 2nd: Optimizing the Eval Prompt

- Gradient descent optimization
- Few shot prompting 
- Meta prompting