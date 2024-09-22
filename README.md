# **Electra - Predict Elections Way Better With LLM Agents**

__TLDR: We built a multi-agent framework from scratch and used it to simulate election results in battleground states__ 

Leaner than CrewAI & meaner than Autogen, we can beat prompting & fine-tuning by using our conversational framework to spawn groupchats of collaborative agents to solve all your problems __(in just 4 lines of code)__.

We adapted this framework to simulate how current events can affect real-time election results: by using census data to replicate voter districts, generating detailed backstories for AI agents, and programming them to think exactly like the voters they are acting out. 
```python
from Network import Network
breaking_news = '''Breaking News! Donald Trump will launch his own cryptocurrency.'''
agent_network = Network(breaking_news, state = "Pennsylvania", num_agents = 15)
agent_network.simulate("round_robin", num_rounds = 1)
```

Electra is an interactive web app that simulates and visualizes the effect of any hypothetical scenario on election results.  for political candidates as the 2024 elections approach. Leveraging advanced language models and dynamic data visualization, the tool enables users to select a state, input specific scenarios, and explore sentiment trends across counties.
With an intuitive interactive map, users can easily comprehend public opinion and monitor shifts in sentiment over time.

Our aim is to provide a powerful, user-friendly platform that captures the diverse perspectives of communities nationwide, facilitating informed discussions around the upcoming elections.


## **Features**
- Custom Scenario: See how voters shift positions on the craziest of hypothetical scenarios (e.g., "Breaking News! Bernie Sanders endorsed Trump")
- Interactive U.S. Map: Real-time visualizations of sample data
- Representativeness: Samples are generalizable to the population using scraped US Census Data

## **Technologies Used**

### AI/ML
- Cerebras: Crucial for any agentic framework, but especially for simulation research
- Llama 3.1 (7B and 80B): Amazing LLM models in general, especially for fine-tuning and open-source tooling
- Pydantic + GPT-4o-mini: Perfect for generating and extracting structured data

### Front-End
- CSS: For styling
- HTML: For markup
- React: For building the user interface
- D3.js: For dynamic data visualizations

### Back-End
- Node.js: For server-side logic
- Python: For data processing and integration

### Data Formats and Libraries
- GeoJSON: For geographic data representation

## **Setup Instructions**

### **Prerequisites**
- Python (version X.X)
- Node.js (if applicable for the front-end)

### **Installation Steps**
1. Clone the repository:
   ```bash git clone
       https://github.com/SahraMohamad/LLM-Net.git
       cd LLM-Net 
2. Install dependencies


