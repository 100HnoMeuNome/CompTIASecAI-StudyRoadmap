# 🛡️ CompTIA SecAI+ CY0-001 — Trilha de Estudos

> Trilha de estudos completa baseada nos objetivos oficiais do exame **CompTIA SecAI+ CY0-001 V1** (Exam Objectives Document Version 2.0 · 2025).  
---

## 📋 Sobre o Exame

| Campo | Detalhe |
|---|---|
| Exame | SecAI+ CY0-001 V1 |
| Tipo de questões | Múltipla escolha e performance-based |
| Experiência recomendada | 3–4 anos de TI + ~2 anos de cibersegurança |
| Série | CompTIA Expansion Series |

---

## 🗺️ Domínios e Pesos

| # | Domínio | % do Exame |
|---|---|---|
| 1.0 | Basic AI Concepts Related to Cybersecurity | 17% |
| 2.0 | Securing AI Systems | **40%** |
| 3.0 | AI-assisted Security | 24% |
| 4.0 | AI Governance, Risk, and Compliance | 19% |

---

## 📘 Domínio 1 — Basic AI Concepts Related to Cybersecurity (17%)

### 1.1 Compare and contrast AI types and techniques

**Tópicos:**
- Types of AI: Generative AI, Machine Learning, Statistical Learning, Transformers, Deep Learning, NLP
  - Large Language Models (LLMs), Small Language Models (SLMs), GANs
- Model training techniques: Supervised, Unsupervised, Reinforcement Learning, Fine-tuning (Epoch, Pruning, Quantization)
- Prompt engineering: System prompts, User prompts, Zero-shot, One-shot, Multi-shot, Templates

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| 3Blue1Brown — Neural Networks series | 📺 YouTube | [youtube.com/playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) |
| Andrej Karpathy — Intro to Large Language Models | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| AI/ML Fundamentals for Cybersecurity — Google Cloud | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=PeCQTExnQ5s) |
| GANs para Threat Detection | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=GNBRW3VaHBc) |
| Attention Is All You Need (paper Transformers) | 📄 Paper | [arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762) |
| LLM vs SLM Security Tradeoffs (arXiv) | 📄 Paper | [arxiv.org/abs/2509.20411](https://arxiv.org/abs/2509.20411) |
| Prompt Engineering Guide | 🆓 Gratuito | [promptingguide.ai/pt](https://www.promptingguide.ai/pt) |
| Zero/Few-Shot Prompting Hands-On — Promptfoo | 🧪 Lab | [promptfoo.dev/docs/guides/prompt-engineering](https://www.promptfoo.dev/docs/guides/prompt-engineering/) |
| Google Machine Learning Crash Course | 🆓 Gratuito | [developers.google.com](https://developers.google.com/machine-learning/crash-course) |
| **APIsec U — Working with APIs** *(base de como LLMs e AI consomem e expõem APIs; cobre REST, requests/responses e autenticação)* | 🎓 APIsec University | [apisecuniversity.com/courses/working-with-apis](https://www.apisecuniversity.com/courses/working-with-apis) |
| **APIsec U — API Security Fundamentals** *(introdução aos princípios de segurança de API e autenticação — base para entender como AI systems são expostos)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-security-fundamentals](https://www.apisecuniversity.com/courses/api-security-fundamentals) |

---

### 1.2 Data security in relation to AI

**Tópicos:**
- Data processing: cleansing, verification, lineage, integrity, provenance, augmentation, balancing
- Data types: structured, semi-structured, unstructured
- Watermarking
- Retrieval-Augmented Generation (RAG): vector storage, embeddings

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| IBM Technology — RAG Explained | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=T-D1OfcDW1M) |
| AI Watermarking Explained — DataCamp | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=v05RmTnyfUg) |
| LangChain — RAG from Scratch | 🔗 GitHub | [github.com/langchain-ai/rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch) |
| Securing Vector Databases — PromptGuardrails | 🆓 Gratuito | [promptguardrails.com → RAG Security](https://promptguardrails.com/blog/rag-security-complete-guide-vector-databases) |
| Data Lineage/Provenance in ML Pipelines — Netskope | 🆓 Gratuito | [netskope.com → Data Lineage](https://www.netskope.com/security-defined/what-is-data-lineage) |
| NIST SP 800-188 — De-Identifying Datasets | 📄 Paper | [csrc.nist.gov](https://csrc.nist.gov/publications/detail/sp/800-188/final) |
| **APIsec U — Securing LLM & NLP APIs** *(data privacy, HTTPS/TLS para dados em trânsito e em repouso, proteção de inputs/outputs de LLMs)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |

---

### 1.3 Security throughout the AI life cycle

**Tópicos:**
- Business use case (alignment with corporate objectives)
- Data collection (trustworthiness, authenticity)
- Data preparation → Model development → Model evaluation → Deployment → Validation → Monitoring → Feedback
- Human-centric AI: Human-in-the-loop, Human oversight, Human validation

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| NIST AI Lifecycle Security — YouTube | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=t51TtlRRapU) |
| Human Oversight Best Practices — SafeShield | 🆓 Gratuito | [safeshield.cloud → Free Training](https://www.safeshield.cloud/free-training-safety-security-and-resilience-in-ai-systems) |
| Microsoft — AI for Beginners | 🔗 GitHub | [github.com/microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) |
| DeepLearning.AI — Machine Learning in Production | 🆓 Gratuito (audit) | [coursera.org](https://www.coursera.org/learn/introduction-to-machine-learning-in-production) |
| **APIsec U — Securing AI Applications** *(ameaças ao longo de todo o ciclo de vida de AI: da concepção ao deployment e monitoramento)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-ai-applications](https://www.apisecuniversity.com/courses/securing-ai-applications) |
| **APIsec U — Start Left: API SecDevOps** *(embed security early — SSDLC, IaC, key rotation, monitored production access, lifecycle com deployment e feedback)* | 🎓 APIsec University | [apisecuniversity.com/courses/start-left-api-secdevops](https://www.apisecuniversity.com/courses/start-left-api-secdevops) |

---

## 🔐 Domínio 2 — Securing AI Systems (40%) ⭐ Mais pesado

### 2.1 AI threat-modeling resources

**Tópicos:**
- OWASP Top 10 for LLMs
- OWASP ML Security Top 10
- MIT AI Risk Repository
- MITRE ATLAS (Adversarial Threat Landscape for AI Systems)
- CVE AI Working Group

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| OWASP GenAI 2025 (LLM Top 10 atualizado) | 🆓 Gratuito | [genai.owasp.org](https://genai.owasp.org/) |
| OWASP LLM Top 10 — Cheat Sheet + Labs | 🧪 Lab | [blog.alexewerlof.com](https://blog.alexewerlof.com/p/owasp-top-10-ai-llm-agents) |
| MITRE ATLAS Navigator | 🆓 Gratuito | [atlas.mitre.org](https://atlas.mitre.org/) |
| Como usar MITRE ATLAS para Threat Modeling | 🆓 Guia | [cloudsecurityguy.substack.com](https://cloudsecurityguy.substack.com/p/how-to-use-mitre-atlas-to-threat) |
| MIT AI Risk Repository | 🆓 Gratuito | [airisk.mit.edu](https://airisk.mit.edu/) |
| MIT AI Risk Repository — Governance Mapping | 🆓 Artigo | [iapp.org → MIT AI Risk](https://iapp.org/news/a/naming-the-unseen-how-the-mit-ai-risk-repository-helps-map-the-uncertain-terrain-of-ai-governance) |
| CVE AI Working Group — Charter | 📄 PDF | [cve.org → CVEAIWG Charter](https://www.cve.org/Resources/Roles/WorkingGroups/CVEAIWG/CVEAIWG-Charter.pdf) |
| **APIsec U — OWASP API Security Top 10 and Beyond** *(deep-dive no OWASP API Security Top 10 2023 — framework de threat modeling; cobre injeções, auth, misconfiguração e supply chain)* | 🎓 APIsec University | [apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond](https://www.apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond) |
| **APIsec U — MCP Security Fundamentals** *(threat landscape de AI agents — tool poisoning, prompt injection via MCP, supply chain attacks — alinha com MITRE ATLAS)* | 🎓 APIsec University | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |

---

### 2.2 Security controls for AI systems

**Tópicos:**
- Model controls: model evaluation, model guardrails, prompt templates
- Gateway controls: prompt firewalls, rate limits, token limits, input quotas (data size, quantity), modality limits, endpoint access controls
- Guardrail testing and validation

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| F5 NGINX — LLM01 Prompt Injection Defense Lab | 🧪 Lab | [clouddocs.f5.com → LLM Injection](https://clouddocs.f5.com/training/community/nginx/html/class15/module4/module4.html) |
| LLM Guardrails Best Practices — Datadog | 🆓 Artigo | [datadoghq.com → LLM Guardrails](https://www.datadoghq.com/blog/llm-guardrails-best-practices/) |
| NVIDIA NeMo Guardrails | 🔗 GitHub | [github.com/NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) |
| SANS — AI Security Controls (webcasts) | 🆓 Gratuito | [sans.org/webcasts](https://www.sans.org/webcasts/ai-security/) |
| **APIsec U — API Gateway Best Practices** *(tipos de gateways, design e enforcement de controles — prompt firewalls, rate/token limits e modality limits)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-gateway-best-practices](https://www.apisecuniversity.com/courses/api-gateway-best-practices) |
| **APIsec U — Securing API Servers** *(rate limiting, CORS, error handling, prevenção de DDoS, proteção de dados sensíveis — gateway controls e endpoint access controls)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-api-servers](https://www.apisecuniversity.com/courses/securing-api-servers) |
| **APIsec U — Securing LLM & NLP APIs** *(guardrails de input/output, controles para prevenção de injection e data leakage em APIs de AI)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |

---

### 2.3 Access controls for AI systems

**Tópicos:**
- Model access, Data access, Agent access, Network/API access
- IAM aplicado a sistemas de IA

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| API RBAC for AI Gateways — TrueFoundry | 🆓 Artigo | [truefoundry.com → API Auth RBAC](https://www.truefoundry.com/blog/api-auth-rbac-in-gateway) |
| AWS — Security for AI/ML (Skill Builder) | 🆓 Gratuito | [skillbuilder.aws](https://explore.skillbuilder.aws/learn/course/external/view/elearning/19790/security-and-privacy-for-ai-and-machine-learning) |
| **APIsec U — API Security Fundamentals** *(autenticação, autorização e controle de acesso a APIs — fundação para model access, agent access e API access controls)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-security-fundamentals](https://www.apisecuniversity.com/courses/api-security-fundamentals) |
| **APIsec U — MCP Security Fundamentals** *(risk-based permissioning para AI agents, least privilege em LLMs, controles de acesso para MCP servers)* | 🎓 APIsec University | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |

---

### 2.4 Data security controls for AI systems

**Tópicos:**
- Encryption: in transit, at rest, in use
- Data safety: anonymization, classification labels, redaction, masking, minimization

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| Microsoft Presidio — Data anonymization | 🔗 GitHub | [github.com/microsoft/presidio](https://github.com/microsoft/presidio) |
| NIST SP 800-188 — De-Identifying Datasets | 📄 Paper | [csrc.nist.gov](https://csrc.nist.gov/publications/detail/sp/800-188/final) |
| **APIsec U — Securing LLM & NLP APIs** *(HTTPS/TLS para dados em trânsito e em repouso, prevenção de data leakage em APIs de AI)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |
| **APIsec U — Securing API Servers** *(proteção de dados sensíveis, cookie security, prevenção de information disclosure — data masking e data minimization)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-api-servers](https://www.apisecuniversity.com/courses/securing-api-servers) |

---

### 2.5 Monitoring and auditing for AI systems

**Tópicos:**
- Prompt monitoring (query, response)
- Log monitoring, sanitization, protection
- Response confidence level, rate monitoring
- AI cost monitoring (prompts, storage, response, processing)
- Auditing: hallucinations, accuracy, bias and fairness, access

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| LangSmith — LLM Monitoring & Tracing | 🆓 Gratuito | [docs.smith.langchain.com](https://docs.smith.langchain.com/) |
| Microsoft Responsible AI Toolbox | 🔗 GitHub | [github.com/microsoft/responsible-ai-toolbox](https://github.com/microsoft/responsible-ai-toolbox) |
| **APIsec U — API Security in DevSecOps** *(continuous monitoring, logging e auditoria de segurança de API em ambientes de produção — prompt/rate monitoring e auditing for compliance)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-security-in-the-world-of-devsecops](https://www.apisecuniversity.com/courses/api-security-in-the-world-of-devsecops) |

---

### 2.6 Analyze attacks and suggest compensating controls

**Ataques cobertos:**
- Prompt injection, Poisoning (model / data), Jailbreaking, Hallucinations
- Input manipulation, Introducing biases, Circumventing guardrails
- Model inversion, Model theft, AI supply chain attacks
- Transfer learning attacks, Model skewing, Output integrity attacks
- Membership inference, Insecure output handling, Model DoS
- Sensitive information disclosure, Insecure plug-in design, Excessive agency, Overreliance

**Compensating controls:**
- Prompt firewalls, Model guardrails, Access controls, Data integrity controls, Encryption, Prompt templates, Rate limiting, Least privilege

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| Computerphile — Prompt Injection Attacks | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=Sv5OLj2nVAQ) |
| F5 — Prompt Injection Hands-On Lab | 🧪 Lab | [clouddocs.f5.com → LLM Injection](https://clouddocs.f5.com/training/community/nginx/html/class15/module4/module4.html) |
| Data Poisoning — Detection Tutorial (Lakera) | 🆓 Artigo | [lakera.ai → Data Poisoning](https://www.lakera.ai/blog/training-data-poisoning) |
| Model Inversion — Attacks + Defenses (Witness AI) | 🆓 Artigo | [witness.ai → Model Inversion](https://witness.ai/blog/model-inversion-attacks/) |
| LLM Guardrails Best Practices — Datadog | 🆓 Artigo | [datadoghq.com → LLM Guardrails](https://www.datadoghq.com/blog/llm-guardrails-best-practices/) |
| IBM — Adversarial Robustness Toolbox | 🔗 GitHub | [github.com/Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) |
| Taxonomy of Attacks on ML Systems | 📄 Paper | [arxiv.org/abs/1810.01997](https://arxiv.org/abs/1810.01997) |
| **APIsec U — OWASP API Security Top 10 and Beyond** *(BOLA/BOPLA, broken auth, injection attacks, insecure output handling — lista de ataques quase idêntica ao domínio 2.6)* | 🎓 APIsec University | [apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond](https://www.apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond) |
| **APIsec U — MCP Security Fundamentals** *(tool poisoning, prompt injection via agents, supply chain attacks em MCP, excessive agency)* | 🎓 APIsec University | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |
| **APIsec U — API Penetration Testing** *(hands-on: testa BOLA, broken auth, mass assignment, SSRF, injection — mesmos ataques do domínio 2.6 em prática real)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-penetration-testing](https://www.apisecuniversity.com/courses/api-penetration-testing) |
| **APIsec U — Securing LLM & NLP APIs** *(injection attacks, insecure output handling, data leakage via LLM APIs — compensating controls aplicados a AI systems)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |

---

## 🤖 Domínio 3 — AI-assisted Security (24%)

### 3.1 AI-enabled tools for security tasks

**Ferramentas/aplicações:**
- IDE plug-ins, Browser plug-ins, CLI plug-ins, Chatbots, Personal assistants, MCP server

**Casos de uso:**
- Signature matching, Code quality and linting, Vulnerability analysis, Automated penetration testing
- Anomaly detection, Pattern recognition, Incident management, Threat modeling, Fraud detection, Translation, Summarization

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| MCP Server Security — Complete Guide (Stainless) | 🆓 Guia | [stainless.com → MCP Security](https://www.stainless.com/mcp/mcp-server-security) |
| GitHub Copilot Security Best Practices | 🆓 Artigo | [github.blog → Copilot Security](https://github.blog/ai-and-ml/github-copilot/github-for-beginners-security-best-practices-with-github-copilot/) |
| Top AI Pentesting Tools — Aikido | 🆓 Artigo | [aikido.dev → AI Pentest Tools](https://www.aikido.dev/blog/top-automated-penetration-testing-tools) |
| Anomaly Detection — Practical Demo (Vectra + MITRE ATLAS) | 🆓 Demo | [vectra.ai → MITRE ATLAS](https://www.vectra.ai/topics/mitre-atlas) |
| Awesome AI Security (lista curada) | 🔗 GitHub | [github.com/ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) |
| IBM Technology — AI for Cybersecurity | 📺 YouTube | [youtube.com/c/IBMTechnology](https://www.youtube.com/c/IBMTechnology) |
| Model Context Protocol (MCP) — Anthropic | 🆓 Docs | [modelcontextprotocol.io](https://modelcontextprotocol.io/introduction) |
| **APIsec U — MCP Security Fundamentals** *(MCP server listado explicitamente no objetivo 3.1 como ferramenta de AI — leitura obrigatória para este objetivo)* | 🎓 APIsec University | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |
| **APIsec U — APIsec Power User** *(uso de AI para automated penetration testing de APIs — vulnerability analysis e automated penetration testing dos use cases)* | 🎓 APIsec University | [apisecuniversity.com/courses/apisec-power-user](https://www.apisecuniversity.com/courses/apisec-power-user) |

---

### 3.2 How AI enables or enhances attack vectors

**Tópicos:**
- AI-generated content (deepfake): impersonation, misinformation, disinformation
- Adversarial networks, Reconnaissance, Social engineering, Obfuscation
- Automated data correlation
- Automated attack generation: attack vector discovery, payloads, malware, honeypot, DDoS

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| Deepfakes/Social Engineering — Threats + Defenses | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=ptZZeeb2oLk) |
| SANS — How AI is Changing Cyberattacks | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=LFsoz3CNPOE) |
| Adversarial ML — Interactive Tutorial (AAAI) | 🧪 Lab interativo | [adversarial-ml-tutorial.org](http://adversarial-ml-tutorial.org/introduction/) |
| AI-Powered Cyber Threats Report | 📄 Paper | [arxiv.org/abs/2404.06248](https://arxiv.org/abs/2404.06248) |
| **APIsec U — Securing LLM & NLP APIs** *(como LLMs podem ser explorados e criar vulnerabilidades — AI potencializando attack vectors via NLP e automação)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |
| **APIsec U — MCP Security Fundamentals** *(como AI agents com MCP amplificam attack vectors — tool poisoning automatizado, reconnaissance via LLMs)* | 🎓 APIsec University | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |

---

### 3.3 Use AI to automate security tasks

**Tópicos:**
- Scripting tools: low-code, no-code
- Document synthesis and summarization
- Incident response ticket management
- Change management: AI-assisted approvals, automated deployment/rollback
- AI agents
- CI/CD: code scanning, software composition analysis, unit/regression/model testing, automated deployment

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| LangChain Orchestration with IBM Granite — IBM | 🆓 Tutorial | [ibm.com → LLM Agent Orchestration](https://www.ibm.com/think/tutorials/llm-agent-orchestration-with-langchain-and-granite) |
| DevSecOps with Agentic AI — TestingXperts | 🆓 Artigo | [testingxperts.com → Agentic AI DevSecOps](https://www.testingxperts.com/blog/devsecops-with-agentic-ai/) |
| Semgrep — Static Analysis / Code Scanning | 🔗 GitHub | [github.com/semgrep/semgrep](https://github.com/semgrep/semgrep) |
| DeepLearning.AI — AI Agents in LangGraph | 🆓 Gratuito | [learn.deeplearning.ai](https://learn.deeplearning.ai/courses/ai-agents-in-langgraph) |
| **APIsec U — API Security in DevSecOps** *(automação de segurança em CI/CD, code scanning, software composition analysis — mapeia diretamente para os tópicos de CI/CD)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-security-in-the-world-of-devsecops](https://www.apisecuniversity.com/courses/api-security-in-the-world-of-devsecops) |
| **APIsec U — Start Left: API SecDevOps** *(BDD, SSDLC, automated testing — automated deployment/rollback, model testing e change management)* | 🎓 APIsec University | [apisecuniversity.com/courses/start-left-api-secdevops](https://www.apisecuniversity.com/courses/start-left-api-secdevops) |
| **APIsec U — APIsec Power User** *(automatização de testes de segurança de API com AI em escala — automated penetration testing e CI/CD integration)* | 🎓 APIsec University | [apisecuniversity.com/courses/apisec-power-user](https://www.apisecuniversity.com/courses/apisec-power-user) |

---

## 📜 Domínio 4 — AI Governance, Risk, and Compliance (19%)

### 4.1 Organizational governance structures for AI

**Tópicos:**
- Organizational structures: AI Center of Excellence, AI policies and procedures
- AI-related roles: Data scientist, AI architect, ML engineer, Platform engineer, MLOps engineer, AI security architect, AI governance engineer, AI risk analyst, AI auditor, Data engineer

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| Microsoft — AI Center of Excellence Framework | 🆓 Guia | [learn.microsoft.com → AI CoE](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/center-of-excellence) |
| Google — People + AI Guidebook | 🆓 Gratuito | [pair.withgoogle.com/guidebook](https://pair.withgoogle.com/guidebook/) |
| World Economic Forum — AI Governance | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=qRIBTgNcgBw) |
| **APIsec U — API Security in DevSecOps** *(estrutura organizacional de DevSecOps: papéis, responsabilidades e integração de segurança — alinha com os AI-related roles)* | 🎓 APIsec University | [apisecuniversity.com/courses/api-security-in-the-world-of-devsecops](https://www.apisecuniversity.com/courses/api-security-in-the-world-of-devsecops) |

---

### 4.2 Risks associated with AI

**Responsible AI:**
- Fairness, Reliability and safety, Transparency, Privacy and security, Explainability, Inclusiveness, Accountability, Consistency, Awareness training

**Risks:**
- Introduction of bias, Accidental data leakage, Reputational loss, Accuracy and performance, IP-related risks, Autonomous systems, Shadow AI

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| Microsoft — Responsible AI Fundamentals | 🆓 Gratuito | [learn.microsoft.com → Responsible AI](https://learn.microsoft.com/en-us/training/paths/responsible-ai-business-principles/) |
| Shadow AI — Detection Tools (Zenity) | 🆓 Artigo | [zenity.io → Shadow AI](https://zenity.io/use-cases/risk-type/shadow-ai) |
| IBM — AI Fairness 360 | 🔗 GitHub | [github.com/Trusted-AI/AIF360](https://github.com/Trusted-AI/AIF360) |
| **APIsec U — 2024 API Security Market Report** *(dados reais de breaches, data leakage e reputational loss — riscos concretos de AI e API security para GRC)* | 🎓 APIsec University | [apisecuniversity.com/2024marketreport](https://www.apisecuniversity.com/2024marketreport) |
| **APIsec U — Securing AI Applications** *(threat modeling para AI, privacy, accidental data leakage, shadow AI e riscos de autonomous systems)* | 🎓 APIsec University | [apisecuniversity.com/courses/securing-ai-applications](https://www.apisecuniversity.com/courses/securing-ai-applications) |

---

### 4.3 Compliance impact on AI business use

**Tópicos:**
- EU AI Act
- OECD AI Principles
- ISO AI standards
- NIST AI Risk Management Framework (AIRMF)
- Corporate policies: sanctioned vs. unsanctioned, private vs. public models, sensitive data governance
- Third-party compliance evaluations, Data sovereignty

**Recursos:**

| Recurso | Tipo | Link |
|---|---|---|
| NIST AI RMF — Free Masterclass | 📺 YouTube | [youtube.com/watch](https://www.youtube.com/watch?v=t51TtlRRapU) |
| NIST AI Risk Management Framework (AIRMF) | 🆓 Gratuito | [airc.nist.gov/RMF/Overview](https://airc.nist.gov/RMF/Overview) |
| EU AI Act — Free Course (BABL AI) | 🆓 Gratuito | [babl.ai → EU AI Act Course](https://babl.ai/babl-ai-launches-new-eu-ai-act-course-free-for-a-limited-time/) |
| EU AI Act — Texto completo | 🆓 Gratuito | [artificialintelligenceact.eu](https://artificialintelligenceact.eu/) |
| OECD AI Principles | 🆓 Gratuito | [oecd.ai/en/ai-principles](https://oecd.ai/en/ai-principles) |
| **APIsec U — PCI DSS 4.0 and APIs** *(requisitos de compliance PCI DSS 4.0 para APIs — third-party compliance evaluations e sensitive data governance)* | 🎓 APIsec University | [apisecuniversity.com/courses/pci-dss-and-apis](https://www.apisecuniversity.com/courses/pci-dss-and-apis) |
| **APIsec U — Start Left: API SecDevOps** *(compliance com OWASP Top 10, SSDLC, políticas de segurança — corporate policies e sensitive data governance)* | 🎓 APIsec University | [apisecuniversity.com/courses/start-left-api-secdevops](https://www.apisecuniversity.com/courses/start-left-api-secdevops) |

---

## 🎓 APIsec University — Mapa Completo de Cursos

Todos os cursos utilizados nesta trilha, com os domínios onde se encaixam:

| Curso | Domínios | Link |
|---|---|---|
| API Security Fundamentals | 1.1 · 2.3 | [apisecuniversity.com/courses/api-security-fundamentals](https://www.apisecuniversity.com/courses/api-security-fundamentals) |
| Working with APIs | 1.1 | [apisecuniversity.com/courses/working-with-apis](https://www.apisecuniversity.com/courses/working-with-apis) |
| Securing LLM & NLP APIs | 1.2 · 2.2 · 2.4 · 2.6 · 3.2 | [apisecuniversity.com/courses/securing-llm-nlp-apis](https://www.apisecuniversity.com/courses/securing-llm-nlp-apis) |
| Securing AI Applications | 1.3 · 4.2 | [apisecuniversity.com/courses/securing-ai-applications](https://www.apisecuniversity.com/courses/securing-ai-applications) |
| MCP Security Fundamentals | 2.1 · 2.3 · 2.6 · 3.1 · 3.2 | [apisecuniversity.com/courses/mcp-security-fundamentals](https://www.apisecuniversity.com/courses/mcp-security-fundamentals) |
| OWASP API Security Top 10 and Beyond | 2.1 · 2.6 | [apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond](https://www.apisecuniversity.com/courses/owasp-api-security-top-10-and-beyond) |
| API Gateway Best Practices | 2.2 | [apisecuniversity.com/courses/api-gateway-best-practices](https://www.apisecuniversity.com/courses/api-gateway-best-practices) |
| Securing API Servers | 2.2 · 2.4 | [apisecuniversity.com/courses/securing-api-servers](https://www.apisecuniversity.com/courses/securing-api-servers) |
| API Security in DevSecOps | 2.5 · 3.3 · 4.1 | [apisecuniversity.com/courses/api-security-in-the-world-of-devsecops](https://www.apisecuniversity.com/courses/api-security-in-the-world-of-devsecops) |
| API Penetration Testing | 2.6 | [apisecuniversity.com/courses/api-penetration-testing](https://www.apisecuniversity.com/courses/api-penetration-testing) |
| APIsec Power User | 3.1 · 3.3 | [apisecuniversity.com/courses/apisec-power-user](https://www.apisecuniversity.com/courses/apisec-power-user) |
| Start Left: API SecDevOps | 1.3 · 3.3 · 4.3 | [apisecuniversity.com/courses/start-left-api-secdevops](https://www.apisecuniversity.com/courses/start-left-api-secdevops) |
| PCI DSS 4.0 and APIs | 4.3 | [apisecuniversity.com/courses/pci-dss-and-apis](https://www.apisecuniversity.com/courses/pci-dss-and-apis) |
| 2024 API Security Market Report | 4.2 | [apisecuniversity.com/2024marketreport](https://www.apisecuniversity.com/2024marketreport) |

> 💡 **Todos os cursos da APIsec University são gratuitos.** Oferecem CPE credits e badges para LinkedIn após conclusão.

---

## 🎯 Simulados e Preparação para o Exame

| Recurso | Detalhes | Link |
|---|---|---|
| **CrucialExams — 253 questões CY0-001** | Questões ponderadas por domínio, formato real do exame | [crucialexams.com → CY0-001](https://crucialexams.com/study/tests/comptia/cy0-001/auto) |
| **LinkedIn Learning — SecAI+ Cert Prep** | Curso de 4+ horas cobrindo todos os domínios | [linkedin.com/learning → SecAI+](https://www.linkedin.com/learning/comptia-secai-plus-cy0-001-cert-prep) |
| **Anki Flashcards (Beta Practice Qs)** | Flashcards baseados nos objetivos oficiais | [youtube.com/watch](https://www.youtube.com/watch?v=PeCQTExnQ5s) |
| **CompTIA SecAI+ — Site Oficial** | Objetivos, informações de beta e registro | [comptia.org → SecAI+](https://www.comptia.org/en-us/certifications/secai/) |

---

## 📅 Plano de Estudos — 8 Semanas

```
Semana 1-2: Domínio 1 — AI Concepts + prática de prompts (17%)
Semana 3-5: Domínio 2 — Securing AI Systems + labs OWASP/MITRE (40%)  ⭐ FOCO PRINCIPAL
Semana 6:   Domínio 3 — AI-assisted Security + MCP deep dive (24%)
Semana 7:   Domínio 4 — Governance, Risk, Compliance (19%)
Semana 8:   3x Simulados completos + revisão das áreas fracas
```

> **Dica:** Labs práticos > teoria. Priorize os exercícios hands-on do F5, Promptfoo, Adversarial ML Tutorial e APIsec Power User.

---

## 📚 Recursos Gerais Complementares

| Recurso | Tipo | Link |
|---|---|---|
| Hugging Face — Courses (NLP, ML, Agents) | 🆓 Gratuito | [huggingface.co/learn](https://huggingface.co/learn) |
| fast.ai — Practical Deep Learning | 🆓 Gratuito | [fast.ai](https://www.fast.ai/) |
| DeepLearning.AI — Short Courses | 🆓 Gratuito | [learn.deeplearning.ai](https://learn.deeplearning.ai/) |
| SANS AI Security Reading Room | 🆓 Gratuito | [sans.org/reading-room](https://www.sans.org/reading-room/) |
| Arxiv — cs.CR (Cryptography & Security) | 📄 Papers | [arxiv.org/list/cs.CR/recent](https://arxiv.org/list/cs.CR/recent) |

---

## 🔑 Siglas Essenciais

| Sigla | Definição |
|---|---|
| AI | Artificial Intelligence |
| ATLAS | Adversarial Threat Landscape for AI Systems |
| CI/CD | Continuous Integration and Continuous Deployment |
| CVE | Common Vulnerabilities and Exposures |
| GAN | Generative Adversarial Network |
| GRC | Governance, Risk, and Compliance |
| IAM | Identity and Access Management |
| LLM | Large Language Model |
| MCP | Model Context Protocol |
| MDLC | Model Development Life Cycle |
| MLOps | Machine Learning Operations |
| NIST | National Institute of Standards and Technology |
| NLP | Natural Language Processing |
| OECD | Organisation for Economic Co-operation and Development |
| OWASP | Open Worldwide Application Security Project |
| PII | Personally Identifiable Information |
| RAG | Retrieval-Augmented Generation |
| SDLC | Software Development Life Cycle |
| SIEM | Security Information and Event Management |
| SLM | Small Language Model |
| SOAR | Security Orchestration, Automation, and Response |
| SOC | Security Operations Center |

---

## 💡 Dicas de Estudo

1. **Priorize o Domínio 2** — representa 40% do exame; foque em prompt injection, model poisoning e OWASP LLM Top 10.
2. **OWASP API Security Top 10 and Beyond** (APIsec U) é leitura obrigatória — mapeia para múltiplos objetivos do Domínio 2.
3. **MCP Security Fundamentals** (APIsec U) é o curso mais transversal — cobre objetivos de 4 domínios diferentes.
4. **MITRE ATLAS** e **OWASP GenAI 2025** — decore as táticas e vulnerabilidades, aparecem muito em questões de cenário.
5. **NIST AIRMF e EU AI Act** são leitura obrigatória para o Domínio 4.
6. **Domine os acrônimos** — o exame usa siglas extensivamente sem explicação.
7. **Faça os simulados do CrucialExams** na última semana — 253 questões ponderadas por domínio.

---

*Baseado no CompTIA SecAI+ CY0-001 V1 Exam Objectives — Document Version 2.0 · Copyright © 2025 CompTIA, Inc.*  
*Cursos APIsec University: [apisecuniversity.com/courses](https://www.apisecuniversity.com/courses) — gratuitos para todos os profissionais.*
