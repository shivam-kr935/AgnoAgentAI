# AgnoAgentAI

Overview:
AgnoAgentAI is a multi-agent system designed for knowledge retrieval and analysis. It leverages advanced language models and hybrid search techniques to provide accurate and context-aware responses to complex queries.

Features:
- Multi-agent architecture for task delegation and collaboration.
- Integration of OpenAI's GPT-4o and Groq's Qwen-2.5-32B models.
- Hybrid search using LanceDB and OpenAI embeddings.
- Real-time data retrieval via DuckDuckGo API.
- PDF knowledge base integration for domain-specific information.
- Streamlit-based user interface for seamless interaction.

Tech Stack:
- Python
- Streamlit
- OpenAI GPT-4o
- Groq Qwen-2.5-32B
- LanceDB
- OpenAIEmbedder
- DuckDuckGo API

Project Structure:
AgnoAgentAI/
├── agent_memory.py          - Agent with memory capabilities
├── multiagents.py           - Multi-agent system implementation
├── simpleagent.py           - Basic agent setup
├── README.md                - Project documentation

Installation Instructions:
1. Clone the repository:
   git clone https://github.com/shivam-kr935/AgnoAgentAI.git
   cd AgnoAgentAI

2. Create and activate a virtual environment:
   python -m venv venv
   On Windows: venv\Scripts\activate
   On Mac/Linux: source venv/bin/activate

3. Install dependencies:
   pip install -r requirements.txt

4. Configure environment variables:
   - Set up API keys and other necessary configurations.

5. Run the application:
   python multiagents.py

Usage:
- Interact with the Streamlit interface to input queries.
- The system retrieves and processes information using integrated agents and tools.
- Results are displayed with contextual relevance and supporting data.

License:
This project is licensed under the MIT License.

Contributing:
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

Contact:
For any inquiries or support, please contact Shivam Kumar at https://github.com/shivam-kr935.
