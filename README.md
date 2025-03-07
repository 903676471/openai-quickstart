# OpenAI Quickstart

<p align="center">
    <br> English | <a href="README-CN.md">中文</a>
</p>


This project is designed as a one-stop learning resource for anyone interested in large language models and their application in Artificial Intelligence Governance and Control (AIGC) scenarios. By providing theoretical foundations, development basics, and hands-on examples, this project offers comprehensive guidance on these cutting-edge topics.

## Features

- **Theory and Development Basics of Large Language Models**: Deep dive into the inner workings of large language models like GPT-4, including their architecture, training methods, applications, and more.

- **AIGC Application Development with LangChain**: Hands-on examples and tutorials using LangChain to develop AIGC applications, demonstrating the practical application of large language models.

## Getting Started

You can start by cloning this repository to your local machine:

```shell
git clone https://github.com/DjangoPeng/openai-quickstart.git
```

Then navigate to the directory and follow the individual module instructions to get started.

## Schedule

| Date       | Description                                                                                                                                                                                                        | Course Materials                                                                          | Events                                                                    |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Wed Jul 12 **Week 1** | Fundamentals of Large Models: Evolution of Theory and Technology <br/> - An Initial Exploration of Large Models: Origin and Development <br/> - Warm-up: Decoding Attention Mechanism <br/> - Milestone of Transformation: The Rise of Transformer <br/> - Taking Different Paths: The Choices of GPT and Bert | Suggested Readings:<br/>- [Attention Mechanism: Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)<br/>- [An Attentive Survey of Attention Models](https://arxiv.org/abs/1904.02874)<br/>- [Transformer: Attention is All you Need](https://arxiv.org/abs/1706.03762)<br/>- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) | [[Homework](docs/homework_01.md)] |
| Sun Jul 16 | The GPT Model Family: From Start to Present <br/> - From GPT-1 to GPT-3.5: The Evolution <br/> - ChatGPT: Where It Wins <br/> - GPT-4: A New Beginning <br/>Prompt Learning <br/> - Chain-of-Thought (CoT): The Pioneering Work <br/> - Self-Consistency: Multi-path Reasoning <br/> - Tree-of-Thoughts (ToT): Continuing the Story | Suggested Readings:<br/>- [GPT-1: Improving Language Understanding by Generative Pre-training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)<br/>- [GPT-2: Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)<br/>- [GPT-3: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)<br/><br/><br/>Additional Readings:<br/>- [GPT-4: Architecture, Infrastructure, Training Dataset, Costs, Vision, MoE](https://www.semianalysis.com/p/gpt-4-architecture-infrastructure)<br/>- [GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models](https://arxiv.org/abs/2303.10130)<br/>- [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/abs/2303.12712)<br/><br/> | [[Homework](docs/homework_02.md)] |
| Wed Jul 19 **Week 2** | Fundamentals of Large Model Development: OpenAI Embedding <br/> - The Eve of General Artificial Intelligence <br/> - "Three Worlds" and "Turing Test" <br/> - Computer Data Representation <br/> - Representation Learning and Embedding <br/> Embeddings Dev 101 <br/> - Course Project: GitHub openai-quickstart <br/> - Getting Started with OpenAI Embeddings                      | Suggested Readings:<br/>- [Representation Learning: A Review and New Perspectives](https://arxiv.org/abs/1206.5538)<br/>- [Word2Vec: Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)<br/>- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf)<br/><br/>Additional Readings:<br/><br/>- [Improving Distributional Similarity with Lessons Learned from Word Embeddings](http://www.aclweb.org/anthology/Q15-1016)<br/>- [Evaluation methods for unsupervised word embeddings](http://www.aclweb.org/anthology/D15-1036) | [[Homework](docs/homework_03.md)]<br/>Code:<br/>[[embedding](openai_api/embedding.ipynb)] |
| Sun Jul 23 | OpenAI Large Model Development and Application Practice <br/> - OpenAI Large Model Development Guide <br/> - Overview of OpenAI Language Models <br/> - OpenAI GPT-4, GPT-3.5, GPT-3, Moderation <br/> - OpenAI Token Billing and Calculation <br/>OpenAI API Introduction and Practice <br/> - OpenAI Models API <br/> - OpenAI Completions API  <br/> - OpenAI Chat Completions API <br/> - Completions vs Chat Completions <br/>OpenAI Large Model Application Practice <br/> - Initial Exploration of Text Completion <br/> - Initial Exploration of Chatbots | Suggested Readings:<br/><br/>- [OpenAI Models](https://platform.openai.com/docs/models)<br/>- [OpenAI Completions API](https://platform.openai.com/docs/guides/gpt/completions-api)<br/>- [OpenAI Chat Completions API](https://platform.openai.com/docs/guides/gpt/chat-completions-api) | Code:<br/>[[models](openai_api/models.ipynb)] <br/>[[tiktoken](openai_api/count_tokens_with_tiktoken.ipynb)] |
| Wed Jul 26 **Week 3** | Best Practices for Applying Large AI Models <br/> - How to Improve the Efficiency and Quality of GPT Model Use <br/> - Best Practices for Applying Large AI Models <br/>   - Text Creation and Generation<br/>   - Article Abstract and Summary <br/>    - Novel Generation and Content Supervision <br/>    - Executing Complex Tasks Step by Step <br/>    - Evaluating the Quality of Model Output <br/>    - Constructing Training Annotation Data <br/>    - Code Debugging Assistant <br/> - New Features： Function Calling Introduction and Practical Application | Suggested Readings <br/> - [GPT Best Practices](https://platform.openai.com/docs/guides/gpt-best-practices) <br/> - [Function Calling](https://platform.openai.com/docs/guides/gpt/function-calling) | Code： <br/> [Function Calling](openai_api/function_call.ipynb) |
| Sun Jul 30 | Practical: OpenAI-Translator <br/> - Market demand analysis for OpenAI-Translator <br/> - Product definition and feature planning for OpenAI-Translator <br/> - Technical solutions and architecture design for OpenAI-Translator <br/> - OpenAI module design <br/> - OpenAI-Translator practical application <br/> | | Code: <br/> [pdfplumber](openai_translator/jupyter/pdfplumber.ipynb) |
| Wed Aug 2 **Week 4**  | ChatGPT Plugin Development Guide <br/> - Introduction to ChatGPT Plugin <br/> - Sample project: Todo management plugin <br/> - Deployment and testing of practical examples <br/> - ChatGPT developer mode <br/> - Practical: Weather Forecast plugin development <br/> - Weather Forecast Plugin design and definition <br/> - Weather Forecast function service <br/> - Integration with third-party weather query platform <br/> - Practical Weather Forecast Plugin | | Code: <br/> [[todo list](openai_plugins/todo-list)] <br/> [[weather forecast](openai_plugins/weather-forecast)]  |
| Sun Aug 6 | LLM Application Development Framework LangChain (Part 1) <br/> - LangChain 101  <br/> - What is LangChain <br/> - Why LangChain is Needed <br/> - Typical Use Cases of LangChain <br/> - Basic Concepts and Modular Design of LangChain <br/> - Introduction and Practice of LangChain Core Modules <br/> - Standardized Large-Scale Model Abstraction: Mode I/O <br/> -  Template Input: Prompts <br/> -  Language Model: Models <br/> - Standardized Output: Output Parsers  | | Code: <br/> [[model io](langchain/jupyter/model_io)] |
| Wed Aug 9 **Week 5** | LLM Application Development Framework LangChain (Part 2) <br/> - Best Practices for LLM Chains <br/> - Getting Started with Your First Chain: LLM Chain <br/> - Sequential Chain: A Chained Call with Sequential Arrangement <br/> - Transform Chain: A Chain for Processing Long Texts <br/> - Router Chain: A Chain for Implementing Conditional Judgments <br/> - Memory: Endowing Applications with Memory Capabilities <br/> - The Relationship between Memory System and Chain <br/> - BaseMemory and BaseChatMessageMemory: Memory Base Classes <br/> - Memory System for Service Chatting <br/> - ConversationBufferMemory <br/> - ConversationBufferWindowMemory <br/> - ConversationSummaryBufferMemory  |  | Code: <br/> [[chain](langchain/jupyter/chain)] <br/> [[memory](langchain/jupyter/memory)] |
|  Sun Aug 13 | LLM Application Development Framework LangChain (Part 3)  <br/> - Native data processing flow of the framework: Data Connection <br/> - Document Loaders <br/> - Document Transformers <br/> - Text Embedding Models <br/> - Vector Stores <br/> - Retrievers <br/> - Agent Systems for Building Complex Applications: Agents <br/> - Theoretical Foundation of Agents: ReAct <br/> - LLM Reasoning Capabilities: CoT, ToT <br/> - LLM Operation Capabilities: WebGPT, SayCan <br/> - LangChain Agents Module Design and Principle Analysis <br/> - Module: Agent, Tools, Toolkits <br/> - Runtime: AgentExecutor, PlanAndExecute, AutoGPT <br/> - Getting Started with Your First Agent: Google Search + LLM <br/> - Practice with ReAct: SerpAPI + LLM-MATH |  | Code: <br/> [[data connection](langchain/jupyter/data_connection)] <br/> [[agents](langchain/jupyter/agents)] |


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. If you have any suggestions or feature requests, please open an issue first to discuss what you would like to change.

<a href='https://github.com/repo-reviews/repo-reviews.github.io/blob/main/create.md' target="_blank"><img alt='Github' src='https://img.shields.io/badge/review_me-100000?style=flat&logo=Github&logoColor=white&labelColor=888888&color=555555'/></a>

## License

This project is licensed under the terms of the Apache-2.0 License . See the [LICENSE](LICENSE) file for details.

## Contact

Django Peng - pjt73651@email.com

Project Link: https://github.com/DjangoPeng/openai-quickstart
