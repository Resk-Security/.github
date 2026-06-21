# Resk Security

**Securing the Future of AI Applications**

Resk Security is a French-based organization dedicated to advancing **AI security** through open-source tools and research. We focus on protecting Large Language Model (LLM) integrations from common vulnerabilities such as **prompt injections**, data leaks, PII exposure, and malicious content generation.

Our mission is to provide developers with robust, easy-to-integrate security layers that ensure safe, compliant, and performant AI applications -- without compromising on usability or speed.

**Location:** France
**Website:** [resk.fr](http://resk.fr)
**Email:** contact@resk.fr
**LinkedIn:** [Resk on LinkedIn](https://www.linkedin.com/company/resk)

## Our Objectives

- **Enhance LLM Security:** Build comprehensive toolkits to defend against emerging threats in AI systems.
- **Promote Open-Source Collaboration:** Share high-quality, well-documented libraries to help the community secure AI deployments.
- **Support Multi-Language and Multi-Provider Ecosystems:** Provide solutions for Python, TypeScript/JavaScript, and more, compatible with major LLM providers (OpenAI, Anthropic, Cohere, etc.).
- **Optimize Performance and Cost:** Integrate intelligent caching, monitoring, and efficient algorithms to reduce API costs and latency.
- **Foster Research and Innovation:** Develop proof-of-concepts, logits processors, and advanced security features grounded in the latest AI security research.

## Featured Projects

### LLM Security Libraries

#### [Resk-LLM](https://github.com/Resk-Security/Resk-LLM) (Python)
A robust Python library for securing LLM API interactions. Adds a protective layer against prompt injections, PII leaks, malicious URLs, and more. Supports multiple providers including OpenAI, Anthropic, and Cohere.
```bash
pip install resk-llm
```

#### [resk-logits](https://github.com/Resk-Security/resk-logits) (Python)
GPU-accelerated logits processor implementing a shadow ban system to filter dangerous content during LLM generation. Uses vectorized Aho-Corasick automaton for O(1) token filtering with zero inference overhead. Compatible with HuggingFace transformers and vLLM.
```bash
pip install resklogits
```

#### [reskSecure](https://github.com/Resk-Security/reskSecure) (Python)
Bitmask-based LLM security firewall. A policy-driven LogitsProcessor that restricts model output based on capability bitmasks. Built on resk-logits with YAML policy configuration, hot-reload, tool call prevention at the token level, and GPU-accelerated pattern matching.
```bash
pip install resksecure
```

#### [resk-llm-ts](https://github.com/Resk-Security/resk-llm-ts) (TypeScript)
Comprehensive TypeScript/JavaScript security toolkit for LLM integrations. Wraps OpenAI-compatible APIs with built-in defenses against prompt injections, data leakage, and content moderation.
```bash
npm install resk-llm-ts
```

### Infrastructure and Protocol Security

#### [resk-mcp](https://github.com/Resk-Security/resk-mcp) (Python)
Enhanced security and management layer for the Model Context Protocol (MCP) Python SDK. Adds monitoring, context handling, and robust protections for advanced LLM workflows.
```bash
pip install mcp-resk
```

#### [resk-caching](https://github.com/Resk-Security/resk-caching) (Bun/TypeScript)
High-performance backend for secure caching of LLM responses using vector databases. Reduces API costs through semantic similarity matching, with built-in security, observability, and real-time distribution.

### Monitoring and Observability

#### [ReskPoints](https://github.com/Resk-Security/ReskPoints) (Python)
The AI Agent Logger. Track every action your agents take with full context: function name, parameters, token probabilities, execution time, and results. Ship logs to Datadog, Prometheus, OpenTelemetry, webhooks, or local files.
```bash
pip install reskpoints
```

### Research

- [backdoor-poc](https://github.com/Resk-Security/backdoor-poc): Proof-of-concept explorations in LLM security.
- [resk-android](https://github.com/Resk-Security/resk-android): Emerging security tools for Android AI applications (Kotlin).

## Get Involved

We welcome contributions, feedback, and stars. If you are building with LLMs and care about security, try our tools today.

```bash
pip install resk-llm resklogits resksecure reskpoints
```
or
```bash
npm install resk-llm-ts
```

Follow us for updates on new releases, security research, and AI best practices.

**Together, let's make AI safer for everyone.**

#AISecurity #LLM #PromptInjection #OpenSource #Python #TypeScript
