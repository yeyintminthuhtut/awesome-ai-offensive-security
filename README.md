# Awesome AI for Offensive Security

A curated list of awesome AI agents, Model Context Protocol (MCP) servers, LLMs, and tools specifically designed for or adapted to offensive security tasks like penetration testing, red teaming, and OSINT.

> **Disclaimer:** This list is for educational and authorized testing purposes only. Ensure you have explicit permission before using any of these tools against any target.

## Contents

- [Pentest & Red Teaming Agents](#pentest--red-teaming-agents)
- [AI Red Teaming (Testing AI Targets)](#ai-red-teaming-testing-ai-targets)

## Contributing

Contributions are very welcome! Please read the [Contribution Guidelines](contributing.md) before submitting a pull request.

> **Note on Accuracy:** The information in this list is provided on a best-effort basis. The AI security landscape evolves rapidly. If you notice any inaccuracies, outdated links, or have suggestions for improvements, please feel free to contribute!

---

## Pentest & Red Teaming Agents

AI-driven autonomous or semi-autonomous agents designed to perform active penetration testing, vulnerability exploitation, and red team engagements.

- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A penetration testing tool powered by ChatGPT. Automates penetration testing by guiding the user and interacting with underlying tools like Nmap and Gobuster.
- [PentAGI](https://github.com/vxcontrol/pentagi) - A multi-agent framework using specialized AI roles for research, coding, and infrastructure to operate autonomously for vulnerability detection.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - An MCP server that acts as a control layer between LLMs and over 150 security tools, allowing agents to execute tools, adapt strategies, and generate reports.
- [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - An autonomous pentesting agent and research framework used for exploring and exploiting environments such as Active Directory.
- [Strix](https://github.com/usestrix/strix) - An AI-powered tool that simulates attacker behavior by executing applications and generating working proof-of-concept exploits.
- [Cybersecurity AI (CAI)](https://github.com/aliasrobotics/cai) - A modular framework for building custom AI security agents across offensive and defensive use cases.
- [Nebula](https://github.com/berylliumsec/nebula) - An AI-powered ethical hacking assistant that embeds AI capabilities into the terminal to assist with reconnaissance and note-taking.
- [NeuroSploit](https://github.com/CyberSecurityUP/NeuroSploit) - AI-driven autonomous agents with 100 vulnerability types, per-scan isolated Kali Linux containers, false-positive hardening, exploit chaining, and a modern React web interface with real-time monitoring.
- [Deadend CLI](https://github.com/xoxruns/deadend-cli) - An AI agent that implements a self-correction mechanism: when an attack fails, the agent analyzes the error, rewrites the approach, and retries.
- [Pentest Copilot](https://github.com/bugbasesecurity/pentest-copilot) - An AI-powered, browser-based ethical hacking assistant designed for pentesting workflows, deployable locally with Docker.
- [BurpGPT](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform customized, passive scans to identify vulnerabilities in web applications.
- [AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) - Automates penetration testing using deep reinforcement learning.
- [Reaper](https://github.com/ghostsecurity/reaper) - Ghost Security's reconnaissance and attack surface discovery tool used for pentesting and identifying exposures.
- [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - A fully automatic penetration test tool utilizing Deep Reinforcement Learning.
- [guardian-cli](https://github.com/zakirkun/guardian-cli) - AI-powered penetration testing automation CLI tool that leverages Google Gemini and LangChain to orchestrate intelligent, step-by-step penetration testing workflows.
- [RedAmon](https://github.com/samugit83/RedAmon) - An AI-powered agentic red team framework designed to automate offensive security operations from recon to exploitation.
- [Shannon](https://github.com/KeygraphHQ/shannon) - Autonomous AI pentesting tool functioning as a virtual hacker to identify and exploit vulnerabilities, evaluated against benchmarks like XBOW.
- [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - An automated penetration testing toolkit.
- [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - Pentesting project with one-command deployment, incorporating tool orchestration and a skills system.
- [MAPTA (Multi-Agent Penetration Testing AI)](https://github.com/arthurgervais/mapta) - An autonomous web application security assessment system orchestrating large language models and tool execution. ([ArXiv Paper](https://arxiv.org/abs/2508.20816))
- [Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) - An AI-powered security tooling framework tailored for penetration testing workflows.
- [TTPRunner](https://github.com/Antonlovesdnb/TTPRunner) - Autonomous execution agent for purple team operations. Processes threat reports to build and run attack plans based on Tactics, Techniques, and Procedures.

## AI Red Teaming (Testing AI Targets)

Tools specifically designed to test the security of AI systems, LLMs, and autonomous agents (e.g., finding prompt injections, jailbreaks, data leaks).

- [PyRIT (Python Risk Identification Tool)](https://github.com/Azure/PyRIT) - An open-source automation framework from Microsoft's AI Red Team for programmatic multi-turn orchestration and custom attack scenarios against AI systems.
- [Giskard](https://github.com/Giskard-AI/giskard) - An automated red-teaming platform for LLM agents (chatbots, RAG pipelines). Performs dynamic multi-turn stress tests to uncover context-dependent vulnerabilities.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - A developer-first framework for AI red teaming and evaluations with flexible configuration and Python integration.
- [Garak](https://github.com/NVIDIA/garak) - An LLM vulnerability scanner that tests various attack vectors using predefined prompts to map findings to AI security frameworks.
- [ARTKIT](https://github.com/BCG-X-Official/artkit) - An open-source framework for automated LLM red teaming that simulates multi-turn attacker–target interactions.
- [Agentic Security](https://github.com/msoedov/agentic_security) - An open-source vulnerability scanner designed to protect AI systems and agent workflows by identifying jailbreaks, fuzzing, and multimodal attacks in LLMs.
- [AgentFence](https://github.com/agentfence/agentfence) - A platform for automatically testing and securing AI agents against prompt injection, memory manipulation, and workflow corruption.
- [llamator](https://github.com/LLAMATOR-Core/llamator) - Framework for testing vulnerabilities of large language models.
- [whistleblower](https://github.com/Repello-AI/whistleblower) - Offensive security tool for testing against system prompt leakage and capability discovery of an AI application exposed through API.
- [LLMFuzzer](https://github.com/mnns/LLMFuzzer) - Open-source fuzzing framework specifically designed for large language models and their integrations in applications via LLM APIs.
- [vigil-llm](https://github.com/deadbits/vigil-llm) - Detects prompt injections, jailbreaks, and other potentially risky large language model inputs.
- [FuzzyAI](https://github.com/cyberark/FuzzyAI) - Tool for automated LLM fuzzing designed to help identify and mitigate potential jailbreaks in LLM APIs.
- [EasyJailbreak](https://github.com/EasyJailbreak/EasyJailbreak) - Python framework to generate adversarial jailbreak prompts.
- [promptmap](https://github.com/utkusen/promptmap) - Prompt injection scanner for custom LLM applications.
- [HouYi](https://github.com/LLMSecurity/HouYi) - Automated prompt injection framework for LLM-integrated applications.
- [llm-attacks](https://github.com/llm-attacks/llm-attacks) - Universal and transferable attacks on aligned language models.
- [Dropbox llm-security](https://github.com/dropbox/llm-security) - Dropbox LLM security research code and results.
- [Greshake llm-security](https://github.com/greshake/llm-security) - Demonstrates new ways of breaking app-integrated LLMs.
- [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - Provides a benchmark for prompt injection attacks and defenses.
- [Plexiglass](https://github.com/safellama/plexiglass) - Toolkit for detecting and protecting against vulnerabilities in large language models.
- [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - Tool designed to test and harden system prompts for generative AI applications.

- [spikee](https://github.com/ReversecLabs/spikee) - Simple prompt injection kit for evaluation and exploitation.
- [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - Curated list of resources for people interested in AI red teaming, jailbreaking, and prompt injection.
- [MCP Tool Poisoning Experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) - Code snippets to reproduce MCP tool poisoning attacks.
- [gptfuzz](https://github.com/sherdencooper/GPTFuzz) - Framework for red teaming large language models with auto-generated jailbreak prompts.
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - Dynamic environment to evaluate attacks and defenses for LLM agents.
- [jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) - Open robustness benchmark for jailbreaking language models.
- [augustus](https://github.com/praetorian-inc/augustus) - LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks.
- [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - A comprehensive AI Red Teaming platform developed by Tencent Zhuque Lab that integrates modules for Infra Scan, MCP Scan, and Jailbreak Evaluation.

