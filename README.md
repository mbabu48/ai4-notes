# ai4-notes
Here is what I learnt at 10000 foot from Ai4 conference

## Key takeaways
#### 🌐 1. Rise of Autonomous AI Agents
🧠 From RAG to AI Agents → Perceive, Plan, Execute. Across industries effort is going on to build efective agents. Very few agentic use cases are in Production.
🔗 Evoluation of RAG: Naiive RAG, Advanced RAG, Hybrid RAG, Graph RAG, Agentic RAG. 
🚧 Challenges: Latency | Security | Governance | Scalability  
#### ⚡ 2. Model Efficiency & Deployment 
🧮 Quantized Models → 99% accuracy w/ low compute  
📦 SLMs > LLMs for: Speed | Cost | Targeted Use  
🧰 Toolkits: VLLM, LLM Compressor, Knowledge Distillation  
🎨 Multimodal Models: Flamingo, CLIP, Vespa for advanced RAG  
🖥️ NVIDIA: 50x compute per megawatt, CUDA X updates  
#### 🛡️ 3. Safety, Alignment & Governance 
🤱 “AI needs maternal instincts” for human safety  
🔍 Governance: Urban Fabric, Telemetry, Explainability  
📜 Compliance: GDPR, AI Act → Traceability is key  
⚖️ AI must align w/ human values, not just rules  
#### 💰 4. Enterprise Strategy & ROI
🚀 $14B invested in AI (2024) → 85% never made it to prod  
💡 4 Pillars for AI ROI:
   1️⃣ Engineering Resources  
   2️⃣ Business Experts  
   3️⃣ Workforce Transformation  
   4️⃣ Competitive Edge  
#### ❤️ 5. Human-AI Interaction & Social Impact
🤖 ElliQ AI Robot → 93% reduced loneliness  
🎬 Creative Industry: Hybrid (AI + human) future  
⚕️ QML in Healthcare → 95%+ accuracy in early cancer detection  
🔗 Trust-building: Transparency + Continuous Feedback  

---

Here are the summaries of the few sessions I attended. 

### AI Safety & Creative Disruption - Keynote
- AI must develop maternal instincts to ensure human safety.
- Regulation alone cannot control existential AI risks.
- AI labs differ in their commitment to safety; Anthropic and Google are highlighted as most safety-focused.
- AI is transforming entertainment: rapid, low-cost content creation, but ethical and job concerns persist.
- Hybrid models combining AI and traditional methods are seen as the future of creative industries.

### AI Alignment & Enterprise Impact - Keynote
- AI alignment is compared to biological and social systems, emphasizing the need for mutual care and shared success.
- Human and AI collaboration is likened to a symphony, where each participant (data, AI, humans) plays a unique role.
- The evolution of AI agents is discussed, highlighting the shift from passive tools to active, agentic systems.
- Three main categories of AI adoption in enterprises: infrastructure providers, off-the-shelf agents, and IT stack integration.
- Key challenges include governance, scalability, explainability, and keeping humans in the loop.
- Success in AI transformation requires clear strategy, scalable technology, governance frameworks, and continuous learning.

### Multimodal modal training insights
- Focus on training and evaluation of multimodal AI models
- Discussion of benchmarks for coding and image/text understanding
- Explanation of model architectures (e.g., Flamingo, CLIP) and scaling laws
- Emphasis on data requirements, training pipelines, and inference efficiency
- Highlights challenges in distributed training and model optimization

### Quantized Models for Agentic AI
- Quantized models enable efficient, cost-effective agentic AI systems.
- Bigger models are not always better—trade-offs exist between size, cost, latency, and accuracy.
- Quantization preserves high accuracy while reducing memory and compute requirements.
- Tools and frameworks like LLM Compressor and VLLM support quantization and inference.
- Benchmarks show up to 99% accuracy retention with quantized models.
- Agentic AI introduces new challenges in latency, cost, and scalability.

### SLMs vs LLMs: Practical Insights
- Explains the challenges of deploying large language models (LLMs) in production: latency, cost, privacy, and energy use.
- Highlights the limitations of using generalist LLMs for specific tasks and introduces Small Language Models (SLMs) as a solution.
- Compares SLMs and LLMs in terms of speed, cost, and suitability for targeted applications.
- Describes practical methods for building and fine-tuning SLMs, including knowledge distillation and parameter-efficient fine-tuning.
- Emphasizes the importance of high-quality, nuanced data for training SLMs, especially for edge cases.
- Stresses that fine-tuning is a continuous process due to evolving user behavior and adversarial tactics.

### From RAG to Autonomous AI Agents
- AI is evolving from information retrieval (RAG) to autonomous agents capable of dynamic action.
- Traditional RAG excels at extracting and grounding information but lacks the ability to act or handle multi-step tasks.
- AI agents can perceive, reason, plan, and execute actions, bridging the gap between knowledge and action.
- Agents orchestrate tools, APIs, and memory to solve complex, real-world problems autonomously.
- Strategic adoption of AI agents requires careful planning, pilot projects, and a focus on security, transparency, and responsible AI.

### Knowledge Graphs Overview
The discussion focused on the benefits of knowledge graphs for enhancing AI models like LLMs. Knowledge graphs, which model entities and relationships, are particularly useful for semantically rich applications and are highly explainable. They complement LLMs by providing detailed information on less-represented topics, reducing hallucinations and improving accuracy. A case study involving a legal research AI assistant highlighted the identification of knowledge gaps, sourcing data from the Hong Kong Standard Industrial Classification manual, and creating a knowledge graph to fill these gaps. The graph was evaluated by experts, showing improved answers compared to the baseline LLM.

### AI and Automation Strategy
The meeting discussed IBM's significant progress in AI and automation, achieving a $3.5 billion productivity run rate, surpassing the $2 billion goal by 2024. Key metrics include $2 billion from AI and automation, and $1.5 billion from process simplification. IBM's financial performance management system unlocked $200 million in business value. The company emphasized a multi-tiered approach, including external benchmarking, cross-functional teams, and quick sprint cycles. IBM's Watson Orchestrate product integrates AI and automation across various workflows. Partnerships with Oracle were highlighted, showcasing successful AI agent implementations in diverse industries, such as construction and media, leading to significant productivity gains.

### AI Agent Architecture Overview
The discussion focused on AI agents and multi-agent AI frameworks. An AI agent is likened to an operating system with multiple LLMs, capable of using tools, APIs, and databases, and communicating with other agents. Architectures vary by use case, such as sequential for marketing content creation and parallel for research. Effective AI agent development involves combining multiple frameworks and ensuring stateful loops for observability. The importance of traceable observability, especially in security applications, was emphasized. Practical applications include benchmarking AI agent quality against human interactions, such as therapy sessions, to ensure effective problem-solving and reflection.

### NVIDIA Platform Performance Update
The discussion focused on NVIDIA's HPC segment, highlighting the Pareto curves that balance performance and responsiveness. The gV 300 MVL 72 offers up to 50x more capacity per megawatt, enhancing cost-effectiveness. NVIDIA's containerized software updates monthly improve performance, reducing TCO. The CUDA X libraries support diverse applications, available on GitHub. HPE's platforms, including b2, GP 200, and future p3 GPUs, leverage these advancements. Dynamo software optimizes inference, achieving up to 40% performance gains. NVIDIA's annual architecture updates include GPUs, CPUs, networking, and rack designs, accelerating innovation and market readiness.

### AI-Powered Search Solutions
The discussion focused on the evolution of AI and RAG (Retrieval and Generation) systems, emphasizing the shift from information retrieval to decision-making and actionable insights. Key points included the need for accurate, timely information retrieval, especially in complex systems like healthcare and finance. Vespa, a platform for building AI applications, was highlighted for its advanced capabilities in handling multimodal data, precision retrieval, and relevancy tuning. A demo illustrated Vespa's effectiveness in processing clinical trial documents, showcasing its ability to handle complex queries and provide detailed, contextual results, underscoring its potential in scaling RAG systems.

### Google AI Agent Overview
Dave Elliott from Google Cloud discussed the evolution and challenges of AI agents, emphasizing the importance of governance and standard protocols. He highlighted Google's agentic AI stack, including the Agent Development Kit (ADK), Model Contact Protocol (MCP), Vertex AI Agent Engine, and Agent-to-Agent (A2A) protocol. ADK is open-source, modular, and deployment-agnostic, supporting various models and infrastructure. MCP enables seamless integration of AI apps with data sources. Vertex AI Agent Engine offers managed runtime services. A2A facilitates agent collaboration. Elliott encouraged developers to use these tools and visit the Google Cloud booth for further engagement.

### Power of MCP
The meeting discussed the evolution and challenges of MCP (Model Calling Protocol), emphasizing its importance for autonomous AI agents. The speaker highlighted the inaugural MCP Dev Summit, which included technical leaders and steering committees. They noted the rise of MCP servers, with over 10,000 currently, and the need for better quality and security. Key issues include discovering safe MCP servers, ensuring secure usage, and implementing policies for enterprise adoption. The speaker introduced the OBOT MCP Gateway, an open-source software solution, and encouraged engagement with the MCP community for further development and collaboration.

### AI Agents Innovation Overview
The discussion focused on Salesforce's advancements in AI agents, highlighting three key innovations: small action models, multimodal action models, and enterprise-grade agent evaluation frameworks. Small action models, like the 1 billion parameter "Tiny Giant," are more efficient, consuming less compute and offering low latency. Multimodal action models, such as "Taco," can handle multimodal data and use tools for better performance. The Model Context Protocol (MCP) and its evaluation framework (MCP eval) enable agents to interact with various tools and services, ensuring enterprise readiness. These open-source tools aim to enhance AI agent capabilities and reliability.

### AI ROI
The discussion focused on the challenges of achieving a positive return on investment (ROI) in AI, highlighting that despite significant investments, many organizations struggle with minimal returns. The speaker emphasized three critical factors for AI ROI: speed advantage, market response, and innovation velocity. In 2024, $14 billion was spent on AI, but 85% failed to reach production, wasting over $11 billion. A collaborative platform approach can reduce engineering costs by 70-80% and increase AI initiatives per resource by 5-10x. The speaker outlined four pillars for successful AI transformation: engineering resources, business experts, workforce transformation, and competitive edge.

### AI Governance and Compliance
Rajesh Mudramal from Intellect Design Arena discussed the evolution of AI governance, emphasizing the need for proactive risk management and intelligent compliance. He highlighted the challenges of legacy systems, regulatory overload, and the necessity for seamless, embedded governance. Mudramal introduced Urban Fabric, a zero-code platform with built-in governance, which has enabled a large UK wealth manager to reduce complaint handling from 50 days to 20 minutes, saving 50% in costs. Additionally, a European sovereign fund integrated granular ESG data, enabling analysts to analyze 1000 times more companies. The platform's rapid deployment time of under eight weeks was also noted.

### AI in Banking Challenges
The discussion emphasized the critical role of trust and traceability in banking and financial services, highlighting the need for human oversight and robust AI frameworks. Key challenges include managing short-term and long-term memory in AI models, ensuring alignment between agents and humans, and mitigating hallucination and data poisoning. Telemetry at every AI life cycle stage is crucial for monitoring accuracy and detecting drift. The conversation also covered the importance of independent validation, fairness in models, and compliance with regulations like GDPR and the upcoming AI Act. Examples included Zillow's $50 million loss due to drift and HSBC's $1 billion penalty for AML violations.

### Quantum Machine Learning in Healthcare
The discussion focused on applying quantum machine learning (QML) to early cancer detection. Speaker 1 highlighted the challenges of current deep learning models in detecting cancer at early stages, citing a 2025 American Cancer Society report showing 35.7% five-year survival rates for brain and breast cancer. QML leverages quantum computing's properties like superposition and entanglement to enhance AI models. A study published in IEEE used ResNet 50 for binary classification, achieving 96% accuracy, and multi-classification with 89% accuracy. Another study in IEEE Valley achieved 95% accuracy using a dataset of 10,000 samples. Future challenges include error correction and optimizing quantum circuits.

### AI Model Limitations Analysis
The discussion focused on the limitations of current AI models, particularly ChatGPT, in handling large contexts and complex tasks. Key issues include the transformer architecture's inefficiency in processing large datasets and the models' reliance on guessing the next token. Solutions like agentic approaches, memory mosaics, and graph-based methods were proposed to improve context handling and accuracy. The need for AI models to reason and understand higher-level concepts was emphasized, along with the importance of 100% accuracy in enterprise applications, such as in critical industries like windmill maintenance. The transformer architecture's future was questioned, suggesting a shift towards more dynamic and intelligent information processing.

### Generative AI Implementation at Boeing
The Boeing Company, with its 170,000 employees in 65 countries, has been leveraging AI and ML for decades. In recent years, Boeing has focused on generative AI, implementing a zero-trust architecture to secure data and limit hallucinations. They have created Gen AI guidelines, launched a Gen AI Academy, and developed Boeing Conversational AI, which scaled to 170,000 employees in January 2024. The application has 38,000 active users across 53 countries, saving teammates an average of 1-2 hours per day. Boeing has also developed 70+ custom Gen AI apps, enhancing productivity in various departments, including finance, HR, and supply chain.

### Building Trust in AI Relationships
The discussion focused on building trust and relationships between humans and AI robots, using ElliQ, an AI companion robot for older adults, as a case study. ElliQ has been deployed in thousands of homes for three years, showing significant engagement with 45 daily interactions post the initial two weeks and 445 days of usage per customer. Sentiment analysis revealed 2% foundational trust, 58% relational trust, and 48% deep connection. Leq's impact includes reducing loneliness by 93%, improving health and wellness by 96%, and maintaining 76% retention on wellness goals. The key to success is proactive engagement, multi-modal interaction, and maintaining transparency.

Thanks to [Otter.ai](https://otter.ai/home) and [Summary AI](https://apps.apple.com/us/app/summary-ai-meeting-note-taker/id6670175056) helping me in taking quick notes  and creating summary to revise the topics easily.

More information and videoes can be found at [Ai4 2025](https://www.youtube.com/channel/UCYAEogbdum3qbHqayXzU6gw/videos) once they are posted.
