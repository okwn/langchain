

## Quickstart

```bash
pip install langchain
# or


## Quick Start

Install with:
```bash
pip install langchain
```

Or clone and run:
```bash
git clone https://github.com/langchain-ai/langchain.git
cd langchain
python setup.py install
```

uv add langchain
```

```python
from langchain.chat_models import init_chat_model

model = init_chat_model("openai:gpt-5.4")
result = model.invoke("Hello, world!")
```

If you're looking for more advanced customization or agent orchestration, check out [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview), our framework for building controllable agent workflows.

For an equivalent JS/TS library, check out [LangChain.js](https://github.com/langchain-ai/langchainjs).

> [!TIP]
> For developing, debugging, and deploying AI agents and LLM applications, see [LangSmith](https://docs.langchain.com/langsmith/home).

## LangChain ecosystem

While the LangChain framework can be used standalone, it also integrates seamlessly with any LangChain product, giving developers a full suite of tools when building LLM applications.

- **[Deep Agents](http://docs.langchain.com/oss/python/deepagents/)** — Build agents that can plan, use subagents, and leverage file systems for complex tasks
- **[LangGraph](https://docs.langchain.com/oss/python/langgraph/overview)** — Build agents that can reliably handle complex tasks with our low-level agent orchestration framework
- **[Integrations](https://docs.langchain.com/oss/python/integrations/providers/overview)** — Chat & embedding models, tools & toolkits, and more
- **[LangSmith](https://www.langchain.com/langsmith)** — Agent evals, observability, and debugging for LLM apps
- **[LangSmith Deployment](https://docs.langchain.com/langsmith/deployments)** — Deploy and scale agents with a purpose-built platform for long-running, stateful workflows

## Why use LangChain?

LangChain helps developers build applications powered by LLMs through a standard interface for models, embeddings, vector stores, and more.

- **Real-time data augmentation** — Easily connect LLMs to diverse data sources and external/internal systems, drawing from LangChain's vast library of integrations with model providers, tools, vector stores, retrievers, and more
- **Model interoperability** — Swap models in and out as your engineering team experiments to find the best choice for your application's needs. As the industry frontier evolves, adapt quickly — LangChain's abstractions keep you moving without losing momentum
- **Rapid prototyping** — Quickly build and iterate on LLM applications with LangChain's modular, component-based architecture. Test different approaches and workflows without rebuilding from scratch, accelerating your development cycle
- **Production-ready features** — Deploy reliable applications with built-in support for monitoring, evaluation, and debugging through integrations like LangSmith. Scale with confidence using battle-tested patterns and best practices
- **Vibrant community and ecosystem** — Leverage a rich ecosystem of integrations, templates, and community-contributed components. Benefit from continuous improvements and stay up-to-date with the latest AI developments through an active open-source community
- **Flexible abstraction layers** — Work at the level of abstraction that suits your needs — from high-level chains for quick starts to low-level components for fine-grained control. LangChain grows with your application's complexity

---

## Documentation

- [docs.langchain.com](https://docs.langchain.com/oss/python/langchain/overview) – Comprehensive documentation, including conceptual overviews and guides
- [reference.langchain.com/python](https://reference.langchain.com/python) – API reference docs for LangChain packages
- [Chat LangChain](https://chat.langchain.com/) – Chat with the LangChain documentation and get answers to your questions

**Discussions**: Visit the [LangChain Forum](https://forum.langchain.com) to connect with the community and share all of your technical questions, ideas, and feedback.

## Additional resources

- [Contributing Guide](https://docs.langchain.com/oss/python/contributing/overview) – Learn how to contribute to LangChain projects and find good first issues.
- [Code of Conduct](https://github.com/langchain-ai/langchain/?tab=coc-ov-file) – Our community guidelines and standards for participation.
- [LangChain Academy](https://academy.langchain.com/) – Comprehensive, free courses on LangChain libraries and products, made by the LangChain team.
