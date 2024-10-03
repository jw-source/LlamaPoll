<p align="center">
  <img src="https://github.com/user-attachments/assets/99dbbe95-a2df-48ff-bd48-124cc1e51c6a" width="300">
</p>

<p align="center">
  <em>Simulate the world with LLM agents</em>
</p>
<p align="center">
<a href="https://reworkd.ai/">🔗 Website</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://x.com/CerebrasSystems/status/1838684550282559545">🐦 Twitter</a>
  
# LlamaPoll: 

__TLDR: We built a multi-agent framework from scratch and used it to simulate focus groups__ 
Use our conversational framework to spawn groupchats of collaborative agents to solve all your problems __(in just 4 lines of code)__.

We adapted this framework to simulate focus groups in real-time: by using data to replicate diversity, generating detailed backstories for AI agents, and programming them to think exactly like the people they are acting out. 

## Usage
```python
from Network import Network
prompt = '''Kamala Harris is showing up to the Purnell Center today!'''
population = '''Students at Carnegie Mellon University'''
num_agents = 10
agent_network = Network(prompt, population, num_agents)
agent_network.group_chat("random", 1)
