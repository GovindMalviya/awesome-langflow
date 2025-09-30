# Awesome Langflow

## Core Langflow Resources
These are the essential, official links that every Langflow developer and contributor should bookmark. They are the most authoritative sources for information, downloads, and updates.

* **Official Website**: [https://www.langflow.org/](https://www.langflow.org/)
* **Documentation**: Comprehensive guide covering installation, quickstarts, tutorials, and release notes for the framework. [https://docs.langflow.org/](https://docs.langflow.org/)
* **Core GitHub Repository**: The main source code repository (MIT license) for the Langflow framework. [https://github.com/langflow-ai/langflow](https://github.com/langflow-ai/langflow)
* **PyPI Package**: The official Python package for installing Langflow via `pip` or `uv`. [https://pypi.org/project/langflow/](https://pypi.org/project/langflow/)
* **Desktop Application**: A downloadable desktop version of Langflow for quick and easy local setup. [https://www.langflow.org/desktop](https://www.langflow.org/desktop)
* **Official Blog**: The main blog featuring news, release announcements, and how-to guides. [https://www.langflow.org/blog/](https://www.langflow.org/blog/)
* **Security Advisories**: A dedicated page listing published security vulnerabilities and advisories for the project. [https://github.com/langflow-ai/langflow/security/advisories](https://github.com/langflow-ai/langflow/security/advisories)

## Community & Social Channels
Engage with the Langflow community for support, to share your projects, and to stay up-to-date. The community is most active on Discord and GitHub.

* **Discord**: The official community hub for real-time support, discussions, and showcasing projects. [https://discord.gg/EqksyE2EX9](https://discord.gg/EqksyE2EX9)
* **GitHub Discussions**: A forum for general questions, ideas, polls, and showing off projects. [https://github.com/langflow-ai/langflow/discussions](https://github.com/langflow-ai/langflow/discussions)
* **GitHub Issues**: The primary place for reporting bugs, tracking tasks, and requesting features. [https://github.com/langflow-ai/langflow/issues](https://github.com/langflow-ai/langflow/issues)
* **X/Twitter**: Official channel for the latest news, updates, and release announcements. [https://x.com/langflow_ai](https://x.com/langflow_ai)
* **YouTube**: Official channel providing video tutorials, workshops, and feature demonstrations. [https://www.youtube.com/@Langflow](https://www.youtube.com/@Langflow)

## Installation & Deployment
Langflow offers multiple installation and deployment paths, from a simple desktop app to scalable Kubernetes deployments.

| Method | Description | Key Details & Command |
| :--- | :--- | :--- |
| **Desktop** | Standalone, easy-to-upgrade application for getting started quickly.  | For macOS (13+) and Windows. Download from [https://www.langflow.org/desktop](https://www.langflow.org/desktop). |
| **Python Package (uv/pip)** | Install the open-source package for command-line use and environment management. | Requires Python 3.10-3.13 and uv. `uv pip install langflow` |
| **Docker** | Run Langflow in an isolated container for consistent, reproducible deployments. | `docker run -p 7860:7860 langflowai/langflow:latest` |
| **Kubernetes (Helm)** | Official Helm charts for scalable and robust deployments on a Kubernetes cluster. | `helm repo add langflow https://langflow-ai.github.io/langflow-helm-charts` |
| **Google Cloud Platform** | A specific, official guide for deploying Langflow on Google Cloud Platform. | Official step-by-step guide for deploying on GCP infrastructure. [https://docs.langflow.org/deployment-gcp](https://docs.langflow.org/deployment-gcp) |
| **Render** | A deployment guide for deploying Langflow on the Render cloud platform. | Official guide for one-click deployment and hosting on Render. [https://docs.langflow.org/deployment-render](https://docs.langflow.org/deployment-render) |

## Learning Pathways
Whether you're a beginner or an advanced user, these resources provide structured paths to master Langflow.

### New? Start Here (Beginner Resources)
This curated list is the best starting point for developers new to Langflow.

* **Langflow Quickstart**: The official guide for beginners to load, run, and serve template flows. [https://docs.langflow.org/get-started-quickstart](https://docs.langflow.org/get-started-quickstart)
* **LangFlow Full Course For Beginners (Video)**: A complete video course by Tech With Tim on how to build AI applications. [https://www.youtube.com/watch?v=kBG5dQe394s](https://www.youtube.com/watch?v=kBG5dQe394s)
* **Build a RAG Based LLM App in 20 Minutes! (Video)**: A popular YouTube tutorial on building Retrieval-Augmented Generation apps with Langflow. [https://www.youtube.com/watch?v=qaEVUhoKS8M](https://www.youtube.com/watch?v=qaEVUhoKS8M)
* **Getting Started with Langflow AI (Article)**: A tutorial focused on effortlessly building an AI chatbot without writing any code. [https://sms.com/blog/getting-started-with-langflow-ai](https://sms.com/blog/getting-started-with-langflow-ai)
* **Building Your First AI Application with LangFlow (Article)**: A tutorial on creating AI applications with Langflow without writing any code. [https://medium.com/@techlatest.net/building-your-first-ai-application-with-langflow-5a3ccb40f05d](https://medium.com/@techlatest.net/building-your-first-ai-application-with-langflow-5a3ccb40f05d)

### Courses and Deeper Dives

* **Langflow Learning Journey**: A dedicated platform from the Langflow team for mastering AI flow development. [https://langflow.academy/](https://langflow.academy/)

* **Langflow: A Guide With Demo Project (Article)**: A DataCamp tutorial explaining how to install Langflow and build AI agent workflows. [https://www.datacamp.com/tutorial/langflow](https://www.datacamp.com/tutorial/langflow)
* **A Beginner's Guide to Building Agents in Langflow (Article)**: Focuses on setting up the canvas, adding memory, and incorporating tools for agents. [https://www.datastax.com/blog/guide-to-building-agents-in-langflow](https://www.datastax.com/blog/guide-to-building-agents-in-langflow)
* **Workshop: Building Your First AI Agent with Langflow (Video)**: A hands-on workshop video on the practical steps of building an AI agent. [https://www.youtube.com/watch?v=mn1ZnlqnQlg](https://www.youtube.com/watch?v=mn1ZnlqnQlg)

## Advanced Guides
Explore complex topics like multi-agent systems, function calling, and local LLMs.

* **Building Multi-Agents Systems with Langflow**: A guide on creating complex, collaborative multi-agent systems using various architectural patterns. [https://valentinaalto.medium.com/building-multi-agents-systems-with-langflow-bbff3dd25591](https://valentinaalto.medium.com/building-multi-agents-systems-with-langflow-bbff3dd25591)
* **Building Deep Research Agents with Langflow**: Learn to build multi-agent systems for deep research using frameworks like JigsawStack. [https://www.langflow.org/blog/web-search-in-your-ai-agents-a-langflow-tutorial](https://www.langflow.org/blog/web-search-in-your-ai-agents-a-langflow-tutorial)
* **MCP Server Documentation**: Official documentation for setting up and using the Model Context Protocol (MCP) client. [https://docs.langflow.org/mcp-client](https://docs.langflow.org/mcp-client)
* **How to Host Your AI Agents and MCP Servers on Langflow**: A guide on deploying Langflow projects, including agents and MCP servers for interoperability. [https://www.langflow.org/blog/how-to-host-langflow](https://www.langflow.org/blog/how-to-host-langflow)
* **Introducing Custom Components**: A blog post on creating and configuring custom components to extend Langflow's functionality. [https://www.langflow.org/blog/introducing-custom-components](https://www.langflow.org/blog/introducing-custom-components)
* **Web Search in Your AI Agents: A Langflow Tutorial**: Official tutorial on integrating real-time web search capabilities into your AI agents. [https://www.langflow.org/blog/web-search-in-your-ai-agents-a-langflow-tutorial](https://www.langflow.org/blog/web-search-in-your-ai-agents-a-langflow-tutorial)
* **Unlocking Local AI: Using Ollama with Agents**: A guide on setting up and using local models with Ollama as agents. [https://www.langflow.org/blog/local-ai-using-ollama-with-agents](https://www.langflow.org/blog/local-ai-using-ollama-with-agents)
* **GitHub Issue: Organizational Management**: A discussion on adding organizational management and multi-tenancy features to Langflow. [https://github.com/langflow-ai/langflow/issues/1716](https://github.com/langflow-ai/langflow/issues/1716)

## RAG-Specific Resources
Guides and articles focused on building and optimizing Retrieval-Augmented Generation (RAG) pipelines.

* **Build a Multi-Query RAG pipeline in Langflow**: A step-by-step guide on implementing a multi-query RAG workflow to enhance retrieval. [https://medium.com/profull-stack/build-a-multi-query-rag-pipeline-in-langflow-9f77953c754a](https://medium.com/profull-stack/build-a-multi-query-rag-pipeline-in-langflow-9f77953c754a)
* **Introducing Astra DB Hybrid Search**: Highlights using Langflow to experiment with hybrid search for improved relevance. [https://www.datastax.com/blog/introducing-astra-db-hybrid-search](https://www.datastax.com/blog/introducing-astra-db-hybrid-search)
* **Launch Week Day 5 - Graph RAG**: Introduces the Graph RAG component, designed to improve accuracy using data relationships. [https://www.langflow.org/blog/launch-week-day-5-graph-rag](https://www.langflow.org/blog/launch-week-day-5-graph-rag)
* **Beyond Basic RAG: Retrieval Weighting**: Discusses strategies to prioritize more relevant information from different retrieved sources. [https://www.langflow.org/blog/beyond-basic-rag-retrieval-weighting](https://www.langflow.org/blog/beyond-basic-rag-retrieval-weighting)
* **Building RAG Systems with Langflow: a step-by-step Guide**: Details components for data loading, chunking, embedding, and retrieval flows. [https://medium.com/@alexrodriguesj/building-rag-systems-with-langflow-a-step-by-step-guide-e35ee537b9cc](https://medium.com/@alexrodriguesj/building-rag-systems-with-langflow-a-step-by-step-guide-e35ee537b9cc)
* **Langfuse Integration Guide**: Official guidance on integrating Langfuse for deep tracing, monitoring, and evaluation. [https://docs.langflow.org/integrations-langfuse](https://docs.langflow.org/integrations-langfuse)

* **LangSmith Integration Guide**: Instructions for setting up LangSmith to monitor, observe, and evaluate LLM applications. [https://docs.langflow.org/integrations-langsmith](https://docs.langflow.org/integrations-langsmith)
* **Case Study: Building an AI Resume Assistant App with RAG**: A practical RAG application for parsing resumes and comparing them against job descriptions. [https://www.langflow.org/blog/building-resumai-langflow-astra-db-openai](https://www.langflow.org/blog/building-resumai-langflow-astra-db-openai)
* **Case Study: Aparavi Financial Services Chatbot**: A case study on building a secure financial services RAG chatbot with Langflow. [https://medium.com/@mansi.more943/how-aparavi-and-langflow-created-a-financial-services-chatbot-without-data-risks-adf3390cc9f3](https://medium.com/@mansi.more943/how-aparavi-and-langflow-created-a-financial-services-chatbot-without-data-risks-adf3390cc9f3)

## Integrations
Langflow connects to a wide array of LLMs, vector databases, and data sources.

### LLM Providers

-   **OpenAI**: Official bundle for OpenAI models, supporting text generation, embeddings, and agentic functions. Requires an OpenAI API key. Supports models like GPT-4. [https://docs.langflow.org/bundles-openai](https://docs.langflow.org/bundles-openai)
-   **Azure OpenAI**: Seamless integration for using Azure-hosted OpenAI models in RAG and agent applications. Requires Azure endpoint URL, deployment name, and an API key. [https://www.youtube.com/watch?v=gAYZP-LUbwc](https://www.youtube.com/watch?v=gAYZP-LUbwc)
-   **Anthropic**: Dedicated bundle for using Anthropic's Claude models, including Claude 3.5 Haiku. Requires an Anthropic API key. Also supports MCP. [https://docs.langflow.org/bundles-anthropic](https://docs.langflow.org/bundles-anthropic)
-   **AWS Bedrock**: Official bundle for accessing various foundation models hosted on Amazon Bedrock. Requires specifying AWS region and using standard AWS authentication. [https://docs.langflow.org/bundles-amazon](https://docs.langflow.org/bundles-amazon)
-   **Google Vertex AI**: Integration for using Google's models like text-bison for generation and embeddings. Auth via service account JSON or GOOGLE_APPLICATION_CREDENTIALS env var. [https://docs.langflow.org/bundles-google](https://docs.langflow.org/bundles-google)
-   **MistralAI**: Dedicated bundle for accessing MistralAI models like open-mixtral-8x7b. Requires a MistralAI API key. The base URL is configurable. [https://docs.langflow.org/bundles-mistralai](https://docs.langflow.org/bundles-mistralai)
-   **Groq**: Build blazing-fast LLM applications using Groq's high-speed LPU Inference Engine. Integration is built-in and requires a Groq API key. [https://docs.langflow.org/bundles-groq](https://docs.langflow.org/bundles-groq)
-   **Ollama (Local)**: Run local LLMs like Llama 3 and other open-source models directly with Langflow. No API key needed. Set the local host URL of the Ollama instance. [https://docs.langflow.org/bundles-ollama](https://docs.langflow.org/bundles-ollama)
-   **NVIDIA**: Official bundle for NVIDIA NIMs, G-Assist, and leveraging local RTX GPU acceleration. Requires an NVIDIA API key. Includes components for generation, embeddings, and reranking. [https://docs.langflow.org/bundles-nvidia](https://docs.langflow.org/bundles-nvidia)
-   **Meta (Llama)**: Use Meta's Llama models within Langflow by running them locally via Ollama. Integration is handled through the Ollama component by specifying the local Llama model. [https://docs.langflow.org/bundles-meta](https://docs.langflow.org/bundles-meta)

### Vector Databases

-   **DataStax Astra DB**: Native integration for vector and hybrid search, central to the DataStax Langflow ecosystem. [https://docs.langflow.org/bundles-datastax](https://docs.langflow.org/bundles-datastax)
-   **Pinecone**: Official bundle for connecting to Pinecone to index, store, and retrieve vector embeddings. [https://docs.langflow.org/bundles-pinecone](https://docs.langflow.org/bundles-pinecone)
-   **Qdrant**: Component for using Qdrant as a vector store for similarity search in RAG pipelines. [https://docs.langflow.org/bundles-qdrant](https://docs.langflow.org/bundles-qdrant)
-   **Weaviate**: Connect to a Weaviate instance for scalable vector search and data storage. [https://docs.langflow.org/bundles-weaviate](https://docs.langflow.org/bundles-weaviate)
-   **Milvus**: Integration for using Milvus, a popular open-source vector database, in your flows. [https://docs.langflow.org/bundles-milvus](https://docs.langflow.org/bundles-milvus)
-   **Redis**: Use Redis as a vector store for low-latency retrieval and caching within Langflow. [https://docs.langflow.org/bundles-redis](https://docs.langflow.org/bundles-redis)
-   **MongoDB**: Connect to MongoDB Atlas to leverage its integrated vector search capabilities. [https://docs.langflow.org/bundles-mongodb](https://docs.langflow.org/bundles-mongodb)
-   **Chroma DB**: Use the open-source Chroma DB for in-memory or persistent vector storage and retrieval. [https://docs.langflow.org/bundles-chroma](https://docs.langflow.org/bundles-chroma)
-   **Vectara**: Integration with Vectara's end-to-end platform for building powerful RAG applications. [https://docs.langflow.org/bundles-vectara](https://docs.langflow.org/bundles-vectara)

### Data Sources & Tools

-   **Notion**: Connect to Notion to use pages and databases as a data source for agents. [https://docs.langflow.org/bundles-notion](https://docs.langflow.org/bundles-notion)
-   **Wikipedia**: A tool for agents to query and retrieve information directly from Wikipedia articles. [https://docs.langflow.org/bundles-wikipedia](https://docs.langflow.org/bundles-wikipedia)
-   **Bing Search**: Provide agents with real-time web search capabilities using the Bing Search API. [https://docs.langflow.org/bundles-bing](https://docs.langflow.org/bundles-bing)

## Observability & Evaluation
Integrate these tools to trace, monitor, and evaluate your Langflow applications.

-   **LangSmith**: A platform by LangChain for debugging, testing, evaluating, and monitoring LLM applications. [https://docs.langflow.org/integrations-langsmith](https://docs.langflow.org/integrations-langsmith)
-   **Langfuse**: Open-source observability and analytics for LLM apps, supporting both cloud and self-hosted instances. [https://docs.langflow.org/integrations-langfuse](https://docs.langflow.org/integrations-langfuse)
-   **LangWatch**: An all-in-one LLMOps platform providing monitoring, analytics, evaluations, and alerting for flows. [https://docs.langflow.org/integrations-langwatch](https://docs.langflow.org/integrations-langwatch)
-   **Arize Phoenix**: Open-source LLM evaluation and observability platform for tracing and measurement. [https://docs.langflow.org/integrations-arize](https://docs.langflow.org/integrations-arize)
-   **Opik**: An open-source platform from Comet for evaluating, testing, and monitoring LLM applications. [https://docs.langflow.org/integrations-opik](https://docs.langflow.org/integrations-opik)

## ⚠️ Security Resources & Advisories
Langflow is under active development, and security is critical. Use these resources to stay informed about vulnerabilities and best practices.

-   **CVE-2025-3248**: Critical RCE vulnerability affecting versions before 1.3.0. Upgrade immediately. [https://github.com/langflow-ai/langflow/security/advisories/GHSA-rvqx-wpfh-mfx7](https://github.com/langflow-ai/langflow/security/advisories/GHSA-rvqx-wpfh-mfx7)
-   **CVE-2025-57760**: High-severity privilege escalation affecting container versions before 1.5.1. Upgrade required. [https://github.com/langflow-ai/langflow/security/advisories/GHSA-4gv9-mp8m-592r](https://github.com/langflow-ai/langflow/security/advisories/GHSA-4gv9-mp8m-592r)
-   **Security Policy**: Official policy detailing security practices and how to report vulnerabilities. [https://github.com/langflow-ai/langflow/blob/main/SECURITY.md](https://github.com/langflow-ai/langflow/blob/main/SECURITY.md)
-   **Advisories Index**: A complete list of published security advisories for the Langflow project. [https://github.com/langflow-ai/langflow/security/advisories](https://github.com/langflow-ai/langflow/security/advisories)
-   **Hardening Guide**: Recommendations include disabling auto-login, using a secret key, and an external database. [https://docs.langflow.org/deployment-prod-best-practices](https://docs.langflow.org/deployment-prod-best-practices)

## Performance & Scalability
Resources for deploying Langflow in production and ensuring it can handle enterprise-level loads.

-   **Kubernetes Scaling**: Official Helm charts for deploying scalable and highly available Langflow instances on Kubernetes. [https://github.com/langflow-ai/langflow-helm-charts](https://github.com/langflow-ai/langflow-helm-charts)
-   **GPU Acceleration (NVIDIA RTX)**: Guide on enabling local AI agents on RTX PCs for high-performance inference. [https://blogs.nvidia.com/blog/rtx-ai-garage-langflow-agents-remix/](https://blogs.nvidia.com/blog/rtx-ai-garage-langflow-agents-remix/)
-   **Concurrency & Load Balancing**: General guidance on handling concurrent connections and scaling for production loads. [https://docs.langflow.org/deployment-prod-best-practices](https://docs.langflow.org/deployment-prod-best-practices)
-   **Cloud Deployment (Render)**: Official guide for deploying and scaling Langflow on the Render cloud platform. [https://docs.langflow.org/deployment-render](https://docs.langflow.org/deployment-render)

## Comparisons & Ecosystem
Understand how Langflow fits into the broader ecosystem of LLM application development tools.

-   **Langflow vs Flowise vs n8n vs Make (Reddit Discussion)**: A community discussion on Reddit comparing Langflow with other popular workflow automation tools. [https://www.reddit.com/r/langflow/comments/1ij66dl/langflow_vs_flowise_vs_n8n_vs_make/](https://www.reddit.com/r/langflow/comments/1ij66dl/langflow_vs_flowise_vs_n8n_vs_make/)

## Case Studies & Announcements
See how Langflow is being used in the real world and keep up with major project milestones.

-   **DataStax Acquires Langflow (April 4, 2024)**: DataStax acquired Langflow to enhance GenAI development with a visual, one-click deployment framework. [https://www.datastax.com/press-release/datastax-acquires-langflow-to-make-building-genai-apps-100x-easier-faster-more-fun](https://www.datastax.com/press-release/datastax-acquires-langflow-to-make-building-genai-apps-100x-easier-faster-more-fun)
-   **Langflow Enables Local AI Agents on RTX PCs (July 31, 2025)**: NVIDIA's blog highlights how Langflow can be used to create local AI agents on RTX PCs. [https://blogs.nvidia.com/blog/rtx-ai-garage-langflow-agents-remix/](https://blogs.nvidia.com/blog/rtx-ai-garage-langflow-agents-remix/)
-   **Case Study: ResumAI - AI Resume Assistant**: An application using Langflow, Astra DB, and OpenAI to parse and compare resumes. [https://www.langflow.org/blog/building-resumai-langflow-astra-db-openai](https://www.langflow.org/blog/building-resumai-langflow-astra-db-openai)
-   **Case Study: Aparavi Financial Services Chatbot**: Aparavi built a secure financial chatbot with Langflow, reducing data prep time by 90%. [https://medium.com/@mansi.more943/how-aparavi-and-langflow-created-a-financial-services-chatbot-without-data-risks-adf3390cc9f3](https://medium.com/@mansi.more943/how-aparavi-and-langflow-created-a-financial-services-chatbot-without-data-risks-adf3390cc9f3)
-   **Showcase: AI-Powered Email Assistant**: A guide and showcase on building an email assistant using Langflow and SendGrid. [https://www.langflow.org/blog/from-no-reply-to-please-reply-how-to-build-an-ai-powered-email-assistant-with-langflow-and-sendgrid](https://www.langflow.org/blog/from-no-reply-to-please-reply-how-to-build-an-ai-powered-email-assistant-with-langflow-and-sendgrid)
-   **Langflow Reaches 100,000 GitHub Stars (August 14, 2025)**: Langflow celebrated reaching the 100k GitHub stars milestone, reflecting massive community adoption. [https://github.com/langflow-ai/langflow](https://github.com/langflow-ai/langflow)
