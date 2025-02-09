# UGAHacksX

# - Team Members: 
    1. Het Pathak

# - Purpose
    The core purpose of FinAI is to ease the access to financial insights and empower users to make informed investment decisions through AI-driven analysis. It aims to simplify the complexities of the financial world by providing a user-friendly platform that delivers instant market data, news, and expert opinions. By leveraging GenAI, FinAI helps users quickly analyze vast amounts of financial information, identify trends, and gain a competitive edge in the market, regardless of their prior financial knowledge.

# - Tools Utilized
    Languages
      1. Python: The primary programming language used for the entire project.
    Frameworks and Libraries
      1. Streamlit: For creating the interactive web application interface.
      2. phi-agent: Used to build and manage the multi-agent AI system.
      3. yfinance: For retrieving real-time and historical financial data from Yahoo Finance.
    GenAI 
      1. Ollama: An open-source platform for running large language models locally.
      2. OpenAI API: For accessing advanced language models like GPT-4.
      3. Groq API: For using deepseek r1 using groq.
    Web Services and APIs
      1. DuckDuckGo Search API: For web searching capabilities to gather latest financial news and analysis.
    Version Control
      1. Git: For source code management and version control.
    Development Tools
      1. Visual Studio Code: As the primary integrated development environment (IDE).
    Deployment
      1. GitHub: For hosting the project repository and facilitating collaboration.
      2. Streamlit Cloud: For deploying and hosting the web application.
  This tech stack was chosen to balance performance, ease of use, and the ability to handle complex financial data analysis tasks efficiently.

# - Challenges Faced
    1. API Key Management: Securely handling and managing API keys for different LLMs (OpenAI, Groq) was a key concern.
    2. Error Handling: Implementing robust error handling to gracefully manage issues such as invalid API keys, network errors, and unexpected responses from the LLMs.
    3. LLM Integration: Dealing with the nuances of integrating different LLMs, each with its own API and response format.
    4. Stream Processing: Implementing streaming of the LLM responses to provide a more interactive and responsive user experience.
    5. Rate Limiting: Avoiding rate limits with the different APIs being used (yfinance, DuckDuckGo, LLM APIs).

# - Public APIs
  1. OpenAI
  2. Groq
  3. DuckDuckGo
  4. YFinance
