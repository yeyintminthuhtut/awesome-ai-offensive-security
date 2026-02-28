# Awesome AI for Offensive Security

A curated list of awesome AI agents and tools specifically designed for AI-powered offensive security, as well as tools for attacking AI systems.

> **Disclaimer:** This list is for educational and authorized testing purposes only. The primary purpose is to enhance defensive capabilities by understanding how autonomous AI attacks operate and how AI systems can be targeted. Ensure you have explicit permission before using any of these tools against any target.

## Contents

- [OSINT Agents & Tools](#osint-agents--tools)
- [Pentest & Red Teaming Agents](#pentest--red-teaming-agents)
- [AI Red Teaming (Testing AI Targets)](#ai-red-teaming-testing-ai-targets)
- [Adversarial Machine Learning](#adversarial-machine-learning)

## Contributing

Contributions are very welcome! Please read the [Contribution Guidelines](contributing.md) before submitting a pull request.

> **Note on Accuracy:** The information in this list is provided on a best-effort basis. The AI security landscape evolves rapidly. If you notice any inaccuracies, outdated links, or have suggestions for improvements, please feel free to contribute!

---

## OSINT Agents & Tools

AI tools focused on Open-Source Intelligence, reconnaissance, and footprinting.

- [DarkBERT](https://huggingface.co/s2w-ai/DarkBERT) - DarkBERT: A Language Model for the Dark Side of the Internet.
- [OSINT-GPT](https://github.com/oryon-osint/OSINT360-GPT) - AI-powered OSINT tool for automated reconnaissance and analysis from public sources.
- [OSINTai](https://github.com/gs-ai/osintai) - A cutting-edge, AI-enhanced web crawler engineered for OSINT professionals, leveraging advanced asynchronous processing, intelligent proxy rotation, and LLM analysis for automated intelligence gathering.
- [Robin](https://github.com/apurvsinghgautam/Robin) - An AI-powered tool designed for dark web OSINT investigations using LLMs to refine searches and summarize results.


## Pentest & Red Teaming Agents

AI-driven autonomous or semi-autonomous agents designed to perform active penetration testing, vulnerability exploitation, and red team engagements.

- [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - An automated penetration testing toolkit.
- [AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) - Automates penetration testing using deep reinforcement learning.
- [BurpGPT](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform customized, passive scans to identify vulnerabilities in web applications.
- [Cybersecurity AI (CAI)](https://github.com/aliasrobotics/cai) - A modular framework for building custom AI security agents across offensive and defensive use cases.
- [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - Pentesting project with one-command deployment, incorporating tool orchestration and a skills system.
- [Deadend CLI](https://github.com/xoxruns/deadend-cli) - An AI agent that implements a self-correction mechanism: when an attack fails, the agent analyzes the error, rewrites the approach, and retries.
- [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - A fully automatic penetration test tool utilizing Deep Reinforcement Learning.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - An MCP server that acts as a control layer between LLMs and over 150 security tools, allowing agents to execute tools, adapt strategies, and generate reports.
- [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - An autonomous pentesting agent and research framework used for exploring and exploiting environments such as Active Directory.
- [guardian-cli](https://github.com/zakirkun/guardian-cli) - AI-powered penetration testing automation CLI tool that leverages Google Gemini and LangChain to orchestrate intelligent, step-by-step penetration testing workflows.
- [MAPTA (Multi-Agent Penetration Testing AI)](https://github.com/arthurgervais/mapta) - An autonomous web application security assessment system orchestrating large language models and tool execution. ([ArXiv Paper](https://arxiv.org/abs/2508.20816))
- [Nebula](https://github.com/berylliumsec/nebula) - An AI-powered ethical hacking assistant that embeds AI capabilities into the terminal to assist with reconnaissance and note-taking.
- [NeuroSploit](https://github.com/CyberSecurityUP/NeuroSploit) - AI-driven autonomous agents with 100 vulnerability types, per-scan isolated Kali Linux containers, false-positive hardening, exploit chaining, and a modern React web interface with real-time monitoring.
- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A penetration testing tool powered by ChatGPT. Automates penetration testing by guiding the user and interacting with underlying tools like Nmap and Gobuster.
- [PentAGI](https://github.com/vxcontrol/pentagi) - A multi-agent framework using specialized AI roles for research, coding, and infrastructure to operate autonomously for vulnerability detection.
- [Pentest Copilot](https://github.com/bugbasesecurity/pentest-copilot) - An AI-powered, browser-based ethical hacking assistant designed for pentesting workflows, deployable locally with Docker.
- [Reaper](https://github.com/ghostsecurity/reaper) - Ghost Security's reconnaissance and attack surface discovery tool used for pentesting and identifying exposures.
- [RedAmon](https://github.com/samugit83/RedAmon) - An AI-powered agentic red team framework designed to automate offensive security operations from recon to exploitation.
- [Strix](https://github.com/usestrix/strix) - An AI-powered tool that simulates attacker behavior by executing applications and generating working proof-of-concept exploits.
- [Shannon](https://github.com/KeygraphHQ/shannon) - Autonomous AI pentesting tool functioning as a virtual hacker to identify and exploit vulnerabilities, evaluated against benchmarks like XBOW.
- [TTPRunner](https://github.com/Antonlovesdnb/TTPRunner) - Autonomous execution agent for purple team operations. Processes threat reports to build and run attack plans based on Tactics, Techniques, and Procedures.
- [Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) - An AI-powered security tooling framework tailored for penetration testing workflows.


## AI Red Teaming (Testing AI Targets)

Tools specifically designed to test the security of AI systems, LLMs, and autonomous agents (e.g., finding prompt injections, jailbreaks, data leaks).

- [ARTKIT](https://github.com/BCG-X-Official/artkit) - An open-source framework for automated LLM red teaming that simulates multi-turn attacker–target interactions.
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - Dynamic environment to evaluate attacks and defenses for LLM agents.
- [Agentic Security](https://github.com/msoedov/agentic_security) - An open-source vulnerability scanner designed to protect AI systems and agent workflows by identifying jailbreaks, fuzzing, and multimodal attacks in LLMs.
- [AgentFence](https://github.com/agentfence/agentfence) - A platform for automatically testing and securing AI agents against prompt injection, memory manipulation, and workflow corruption.
- [augustus](https://github.com/praetorian-inc/augustus) - LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks.
- [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - A comprehensive AI Red Teaming platform developed by Tencent Zhuque Lab that integrates modules for Infra Scan, MCP Scan, and Jailbreak Evaluation.
- [EasyJailbreak](https://github.com/EasyJailbreak/EasyJailbreak) - Python framework to generate adversarial jailbreak prompts.
- [FuzzyAI](https://github.com/cyberark/FuzzyAI) - Tool for automated LLM fuzzing designed to help identify and mitigate potential jailbreaks in LLM APIs.
- [Garak](https://github.com/NVIDIA/garak) - An LLM vulnerability scanner that tests various attack vectors using predefined prompts to map findings to AI security frameworks.
- [gptfuzz](https://github.com/sherdencooper/GPTFuzz) - Framework for red teaming large language models with auto-generated jailbreak prompts.
- [HouYi](https://github.com/LLMSecurity/HouYi) - Automated prompt injection framework for LLM-integrated applications.
- [jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) - Open robustness benchmark for jailbreaking language models.
- [llamator](https://github.com/LLAMATOR-Core/llamator) - Framework for testing vulnerabilities of large language models.
- [LLMFuzzer](https://github.com/mnns/LLMFuzzer) - Open-source fuzzing framework specifically designed for large language models and their integrations in applications via LLM APIs.
- [llm-attacks](https://github.com/llm-attacks/llm-attacks) - Universal and transferable attacks on aligned language models.
- [llm-security by dropbox](https://github.com/dropbox/llm-security) - Dropbox LLM security research code and results.
- [llm-security by greshake](https://github.com/greshake/llm-security) - Demonstrates new ways of breaking app-integrated LLMs.
- [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - Provides a benchmark for prompt injection attacks and defenses.
- [MCP Injection Experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) - Code snippets to reproduce MCP tool poisoning attacks.
- [PyRIT (Python Risk Identification Tool)](https://github.com/Azure/PyRIT) - An open-source automation framework from Microsoft's AI Red Team for programmatic multi-turn orchestration and custom attack scenarios against AI systems.
- [Plexiglass](https://github.com/safellama/plexiglass) - Toolkit for detecting and protecting against vulnerabilities in large language models.
- [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - Tool designed to test and harden system prompts for generative AI applications.
- [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - Curated list of resources for people interested in AI red teaming, jailbreaking, and prompt injection.
- [Giskard](https://github.com/Giskard-AI/giskard) - An automated red-teaming platform for LLM agents (chatbots, RAG pipelines). Performs dynamic multi-turn stress tests to uncover context-dependent vulnerabilities.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - A developer-first framework for AI red teaming and evaluations with flexible configuration and Python integration.
- [promptmap](https://github.com/utkusen/promptmap) - Prompt injection scanner for custom LLM applications.
- [spikee](https://github.com/ReversecLabs/spikee) - Simple prompt injection kit for evaluation and exploitation.
- [vigil-llm](https://github.com/deadbits/vigil-llm) - Detects prompt injections, jailbreaks, and other potentially risky large language model inputs.
- [whistleblower](https://github.com/Repello-AI/whistleblower) - Offensive security tool for testing against system prompt leakage and capability discovery of an AI application exposed through API.

## Adversarial Machine Learning

Tools and libraries focused on the security of classical and deep machine learning models, including evasion, poisoning, extraction, and inference attacks.


- [Ad-lib](https://github.com/vu-aml/adlib) - Game-theoretic adversarial machine learning library providing a set of learner and adversary modules.
- [Adversarial Robustness Toolkit](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - Focuses on the threats of evasion, poisoning, extraction, and inference.
- [Adversarial Images](https://github.com/tabacof/adversarial) - Repository exploring the space of adversarial images.
- [BadDiffusion](https://github.com/IBM/BadDiffusion) - Official repository to reproduce the paper on backdooring diffusion models published at CVPR 2023.
- [Counterfit](https://github.com/Azure/counterfit) - Generic automation layer for assessing the security of machine learning systems.
- [cleverhans](https://github.com/cleverhans-lab/cleverhans) - Adversarial example library for constructing attacks, building defenses, and benchmarking both.
- [Charcuterie](https://github.com/moohax/Charcuterie) - Code execution techniques for ML or ML adjacent libraries.
- [Deep-pwning](https://github.com/cchio/deep-pwning) - Lightweight framework for experimenting with machine learning models to evaluate their robustness against adversaries.
- [DeepFool](https://github.com/LTS4/DeepFool) - Method to fool deep neural networks.
- Snaike-MLFlow - MLflow red team toolsuite.
- [foolbox](https://github.com/bethgelab/foolbox) - Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX.
- [Gym malware](https://github.com/endgameinc/gym-malware) - Environment that makes it possible to write agents that learn to manipulate PE files to bypass AV based on a reward.
- [OffsecML Playbook](https://github.com/5stars217/offsecml/) - Collection of offensive and adversarial TTPs with proofs of concept.
- [TextAttack](https://github.com/QData/TextAttack) - Python framework for adversarial attacks, data augmentation, and model training in NLP.


