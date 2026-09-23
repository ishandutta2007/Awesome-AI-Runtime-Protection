# Awesome-AI-Runtime-Protection

## Top AI Runtime Protection Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Firewalls, Prompt Injection Defense, Model & Agent Runtime Security, Guardrails, Adversarial ML Protection & AI Detection and Response*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Runtime Protection**. These systems sit in front of or around models and agents to detect and block prompt injection, jailbreaks, data leakage, unsafe tool use, model abuse, and other runtime threats—functioning as LLM firewalls, guardrails, or AI detection-and-response layers.



**Examples** include Protect AI, HiddenLayer, Lakera, Aporia, Fiddler AI, Arthur AI, CalypsoAI, NVIDIA AI Enterprise (NeMo Guardrails ecosystem), Zenity, and Noma Security (the category leaders and adjacent platforms).



**Open-source emphasis**: Runtime AI security has a strong open ecosystem. **NeMo Guardrails**, **LlamaFirewall**, **Guardrails AI**, **LLM Guard**, agent firewalls, and red-teaming tools provide practical building blocks. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HiddenLayer](https://www.hiddenlayer.com/)**  

  AI security platform covering model scanning, adversarial discovery, attack simulation, and runtime protection (AIDR-style) for models, agents, and workflows.



- **[Protect AI](https://protectai.com/)**  

  AI security focused on model supply-chain scanning, MLOps policy gates, and related runtime/model security capabilities (now part of broader platform ecosystems in some deployments).



- **[Lakera](https://www.lakera.ai/)**  

  Runtime guard focused on prompt injection and LLM application security, known for practical defenses and evaluation (e.g. Gandalf-style challenges).



- **[Aporia, Fiddler AI, Arthur AI](https://www.aporia.com/)**  

  ML observability and production monitoring platforms with guardrails, drift, and runtime control features for models and LLM applications.



- **[CalypsoAI, Zenity, Noma Security](https://calypsoai.com/)**  

  Platforms for AI application security, agent governance, and runtime controls across enterprise AI usage.



- **[NVIDIA AI Enterprise / NeMo ecosystem](https://www.nvidia.com/en-us/ai-data-science/products/ai-enterprise/)**  

  Enterprise AI stack with strong open and commercial guardrail tooling (NeMo Guardrails) for policy-controlled LLM applications.



- **[Other commercial AI runtime security platforms](https://www.hiddenlayer.com/)**  

  Additional solutions for LLM firewalls, agent security, and AI detection and response.



## Open-Source GitHub Projects



- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Leading open-source framework for adding programmable input, dialog, retrieval, execution, and output rails around LLMs and agents—policy control against jailbreaks, off-topic behavior, and unsafe actions.



- **[LlamaFirewall (Meta)](https://ai.meta.com/research/publications/llamafirewall-an-open-source-guardrail-system-for-building-secure-ai-agents/)**  

  Open-source guardrail system for AI agents: PromptGuard-style jailbreak detection, agent alignment checks, and CodeShield for insecure code generation—designed as a final defense layer.



- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  

  Open framework for adding structured validation, safety checks, and corrective actions around LLM outputs (and inputs) with declarative rails.



- **[LLM Guard](https://github.com/protectai/llm-guard)**  

  Open-source toolkit for scanning and sanitizing LLM inputs and outputs—prompt injection, PII, toxicity, secrets, and related filters (associated with Protect AI’s open efforts).



- **[AISafeGuard & similar safety proxies](https://github.com/akshaymagapu/aisafeguard)**  

  Open LLM safety guardrails: prompt injection protection, PII redaction, toxicity filtering, and OpenAI-compatible proxy modes.



- **[Agent / MCP runtime firewalls](https://github.com/search?q=AI+agent+firewall+OR+MCP+security+open+source)**  

  Projects such as Pipelock-style agent egress firewalls and HOL Guard–style local runtime controls for tool calls, secrets, and agent actions.



- **[Promptfoo, garak & red-teaming tools](https://github.com/promptfoo/promptfoo)**  

  Open tools for automated LLM security testing, red teaming, and vulnerability scanning in CI/CD—complementary to runtime enforcement.



- **[Rebuff, ReAct-style & community injection detectors](https://github.com/search?q=prompt+injection+detection+OR+LLM+firewall)**  

  Additional open detectors and proxy libraries for prompt injection, jailbreaks, and policy enforcement at the API boundary.



### Additional Strong Open-Source Options



- **Programmable rails**: NeMo Guardrails for dialog and policy control.

- **Agent-focused defense**: LlamaFirewall and agent/MCP firewalls for tool-use and alignment risks.

- **Input/output scanning**: LLM Guard, AISafeGuard, and Guardrails AI for filters and structured checks.

- **Red team first**: Promptfoo and garak to find weaknesses before production.

- **Composable stacks**: Open proxy/guard library + policy YAML + logging/SIEM for self-hosted LLM firewalls.

- Enterprise multi-model coverage, managed threat intel, and SOC integration remain commercial strengths.



**Frameworks for building custom systems**:  

**NeMo Guardrails**, **LlamaFirewall**, **Guardrails AI**, and **LLM Guard** form the strongest open runtime protection stack.  

Agent firewalls and red-teaming tools (Promptfoo, garak) complete the picture.  

Commercial platforms (HiddenLayer, Protect AI, Lakera, Aporia, Fiddler, Arthur, CalypsoAI, Zenity, Noma, etc.) add model scanning, scale, managed updates, and enterprise policy administration.  

Many teams deploy open guardrails in front of self-hosted or API models and use commercial AI security platforms for broader discovery, supply-chain scanning, and SOC workflows. Fully open stacks are viable for application-level LLM and agent protection when you can maintain policies and detectors.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI runtime protection reduces risk but does not eliminate it. Prompt injection and agent misuse are active research areas; no guardrail is complete. Combine with least-privilege tool access, human approval for high-impact actions, and monitoring.

- Open-source tools offer transparency and control but require ongoing policy tuning, model updates, and operational ownership. Commercial platforms shift threat-intel and support burden to the vendor. Test thoroughly against your threat model before production use.



---



**Made for AI security engineers, ML platform teams, and builders of safe LLM and agent applications.**  

Let's expand open runtime defenses for AI systems while recognizing the coverage, intelligence, and operational maturity that leading commercial AI runtime protection platforms deliver.
