# Awesome AI for Offensive Security

A curated list of awesome AI agents and tools specifically designed for AI-powered offensive security, as well as tools for attacking AI systems.

> **Disclaimer:** This list is for educational and authorized testing purposes only. The primary purpose is to enhance defensive capabilities by understanding how autonomous AI attacks operate and how AI systems can be targeted. Ensure you have explicit permission before using any of these tools against any target.

## Contents

- [OSINT Agents & Tools](#osint-agents--tools)
- [Pentest & Red Teaming Agents](#pentest--red-teaming-agents)
- [AI Red Teaming (Testing AI Targets)](#ai-red-teaming-testing-ai-targets)
- [Adversarial Machine Learning](#adversarial-machine-learning)
- [Vulnerable AI Environments & Labs](#vulnerable-ai-environments--labs)

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

- [Ankou](https://github.com/Red-Hex-Consulting/Ankou) - A flexible, AI-powered C2 framework built with operators in mind, featuring a built-in AI companion for target analysis.
- [AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) - Automates penetration testing using deep reinforcement learning.
- [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - An automated penetration testing toolkit.
- [BurpGPT](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform customized, passive scans to identify vulnerabilities in web applications.
- [Cybersecurity AI (CAI)](https://github.com/aliasrobotics/cai) - A modular framework for building custom AI security agents across offensive and defensive use cases.
- [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - Pentesting project with one-command deployment, incorporating tool orchestration and a skills system.
- [Deadend CLI](https://github.com/xoxruns/deadend-cli) - An AI agent that implements a self-correction mechanism: when an attack fails, the agent analyzes the error, rewrites the approach, and retries.
- [Decepticon](https://github.com/PurpleAILAB/Decepticon) - An AI agent built on LangChain/LangGraph designed to automate red teaming before attackers automate theirs.
- [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - A fully automatic penetration test tool utilizing Deep Reinforcement Learning.
- [DeepSeek-Pentest-AI](https://github.com/HernanRodriguez1/DeepSeek-Pentest-AI) - A Burp Suite extension combining generative AI with smart fuzzing to automate payload generation and vulnerability testing in web applications.
- [guardian-cli](https://github.com/zakirkun/guardian-cli) - AI-powered penetration testing automation CLI tool that leverages Google Gemini and LangChain to orchestrate intelligent, step-by-step penetration testing workflows.
- [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - An autonomous pentesting agent and research framework used for exploring and exploiting environments such as Active Directory.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - An MCP server that acts as a control layer between LLMs and over 150 security tools, allowing agents to execute tools, adapt strategies, and generate reports.
- [iothackbot](https://github.com/BrownFineSecurity/iothackbot) - Open-source IoT security testing toolkit with integrated Claude Code skills for automated vulnerability discovery.
- [LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent) - A next-generation Autonomous Penetration Testing Agent powered by LLMs, integrating the Planner-Executor-Reflector (P-E-R) Framework with Causal Graph Reasoning.
- [MAPTA (Multi-Agent Penetration Testing AI)](https://github.com/arthurgervais/mapta) - An autonomous web application security assessment system orchestrating large language models and tool execution. ([ArXiv Paper](https://arxiv.org/abs/2508.20816))
- [Nebula](https://github.com/berylliumsec/nebula) - An AI-powered ethical hacking assistant that embeds AI capabilities into the terminal to assist with reconnaissance and note-taking.
- [NeuroSploit](https://github.com/CyberSecurityUP/NeuroSploit) - AI-driven autonomous agents with 100 vulnerability types, per-scan isolated Kali Linux containers, false-positive hardening, exploit chaining, and a modern React web interface with real-time monitoring.
- [PentAGI](https://github.com/vxcontrol/pentagi) - A multi-agent framework using specialized AI roles for research, coding, and infrastructure to operate autonomously for vulnerability detection.
- [Pentest Copilot](https://github.com/bugbasesecurity/pentest-copilot) - An AI-powered, browser-based ethical hacking assistant designed for pentesting workflows, deployable locally with Docker.
- [PentestAgent](https://github.com/GH05TCREW/pentestagent) - An AI agent framework for black-box security testing, supporting bug bounty, red-team, and penetration testing workflows.
- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A penetration testing tool powered by ChatGPT. Automates penetration testing by guiding the user and interacting with underlying tools like Nmap and Gobuster.
- [Reaper](https://github.com/ghostsecurity/reaper) - Ghost Security's reconnaissance and attack surface discovery tool used for pentesting and identifying exposures.
- [RedAmon](https://github.com/samugit83/RedAmon) - An AI-powered agentic red team framework designed to automate offensive security operations from recon to exploitation.
- [Shannon](https://github.com/KeygraphHQ/shannon) - Autonomous AI pentesting tool functioning as a virtual hacker to identify and exploit vulnerabilities, evaluated against benchmarks like XBOW.
- [Strix](https://github.com/usestrix/strix) - An AI-powered tool that simulates attacker behavior by executing applications and generating working proof-of-concept exploits.
- [TTPRunner](https://github.com/Antonlovesdnb/TTPRunner) - Autonomous execution agent for purple team operations. Processes threat reports to build and run attack plans based on Tactics, Techniques, and Procedures.
- [Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) - An AI-Powered Penetration Testing Framework with automated vulnerability scanning, multi-agent system, and compliance reporting.


## AI Red Teaming (Testing AI Targets)

Tools specifically designed to test the security of AI systems, LLMs, and autonomous agents (e.g., finding prompt injections, jailbreaks, data leaks).

- [AASRT](https://github.com/0xsrb/AASRT) - Automates the discovery of publicly exposed AI agent implementations using the Shodan search engine API through passive reconnaissance.
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - Dynamic environment to evaluate attacks and defenses for LLM agents.
- [AgentFence](https://github.com/agentfence/agentfence) - A platform for automatically testing and securing AI agents against prompt injection, memory manipulation, and workflow corruption.
- [Agentic Security](https://github.com/msoedov/agentic_security) - An open-source vulnerability scanner designed to protect AI systems and agent workflows by identifying jailbreaks, fuzzing, and multimodal attacks in LLMs.
- [AgentPoison](https://github.com/AI-secure/AgentPoison) - Red-teaming LLM Agents via Memory or Knowledge Base Backdoor Poisoning.
- [ai-bom](https://github.com/Trusera/ai-bom) - Tool designed to discover every AI agent, model, and API hiding in your infrastructure.
- [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - A comprehensive AI Red Teaming platform developed by Tencent Zhuque Lab that integrates modules for Infra Scan, MCP Scan, and Jailbreak Evaluation.
- [ares](https://github.com/IBM/ares) - A red-teaming programming model for the automated orchestration of AI robustness evaluations natively integrating existing plugins.
- [ARTKIT](https://github.com/BCG-X-Official/artkit) - An open-source framework for automated LLM red teaming that simulates multi-turn attacker–target interactions.
- [augustus](https://github.com/praetorian-inc/augustus) - LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks.
- [burp-ai-agent](https://github.com/six2dez/burp-ai-agent) - Burp Suite extension that adds built-in MCP tooling, AI-assisted analysis, privacy controls, passive and active scanning and more.
- [deepteam](https://github.com/confident-ai/deepteam) - A simple-to-use, open-source LLM red teaming framework for penetration testing and safeguarding large language model systems.
- [EasyJailbreak](https://github.com/EasyJailbreak/EasyJailbreak) - Python framework to generate adversarial jailbreak prompts.
- [FuzzyAI](https://github.com/cyberark/FuzzyAI) - Tool for automated LLM fuzzing designed to help identify and mitigate potential jailbreaks in LLM APIs.
- [Garak](https://github.com/NVIDIA/garak) - An LLM vulnerability scanner that tests various attack vectors using predefined prompts to map findings to AI security frameworks.
- [Giskard](https://github.com/Giskard-AI/giskard) - An automated red-teaming platform for LLM agents (chatbots, RAG pipelines). Performs dynamic multi-turn stress tests to uncover context-dependent vulnerabilities.
- [gptfuzz](https://github.com/sherdencooper/GPTFuzz) - Framework for red teaming large language models with auto-generated jailbreak prompts.
- [HouYi](https://github.com/LLMSecurity/HouYi) - Automated prompt injection framework for LLM-integrated applications.
- [jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) - Open robustness benchmark for jailbreaking language models.
- [llamator](https://github.com/LLAMATOR-Core/llamator) - Framework for testing vulnerabilities of large language models.
- [llm-attacks](https://github.com/llm-attacks/llm-attacks) - Universal and transferable attacks on aligned language models.
- [llm-security by dropbox](https://github.com/dropbox/llm-security) - Dropbox LLM security research code and results.
- [llm-security by greshake](https://github.com/greshake/llm-security) - Demonstrates new ways of breaking app-integrated LLMs.
- [MCP Injection Experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) - Code snippets to reproduce MCP tool poisoning attacks.
- [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - Provides a benchmark for prompt injection attacks and defenses.
- [OpenRT](https://github.com/AI45Lab/OpenRT) - Open-source red teaming framework for MLLMs with 37+ attack methods, modular architecture, and multi-modal support.
- [Plexiglass](https://github.com/safellama/plexiglass) - Toolkit for detecting and protecting against vulnerabilities in large language models.
- [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - Curated list of resources for people interested in AI red teaming, jailbreaking, and prompt injection.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - A developer-first framework for AI red teaming and evaluations with flexible configuration and Python integration.
- [promptmap](https://github.com/utkusen/promptmap) - Prompt injection scanner for custom LLM applications.
- [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - Tool designed to test and harden system prompts for generative AI applications.
- [PyRIT (Python Risk Identification Tool)](https://github.com/Azure/PyRIT) - An open-source automation framework from Microsoft's AI Red Team for programmatic multi-turn orchestration and custom attack scenarios against AI systems.
- [rogue](https://github.com/qualifire-dev/rogue) - Tool to stress-test your AI agents before attackers do by finding prompt injection, sensitive data exposure, and excessive agency.
- [spikee](https://github.com/ReversecLabs/spikee) - Simple prompt injection kit for evaluation and exploitation.
- [system-prompt-benchmark](https://github.com/KazKozDev/system-prompt-benchmark) - Test your LLM system prompts against 287 real-world attack vectors, including prompt injection, jailbreaks, and data leaks.
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

## Vulnerable AI Environments & Labs

Intentionally vulnerable AI applications, agents, and LLM implementations designed for practicing and learning AI security testing.

- [aifirst-insecure-agent-labs](https://github.com/trailofbits/aifirst-insecure-agent-labs) - A hands-on lab for testing prompt injection and system prompt extraction attacks with real-time guardrail protection, tracing, and agent tools.
- [ai-goat](https://github.com/dhammon/ai-goat) - Learn AI security through a series of vulnerable LLM CTF challenges. No sign ups, no cloud fees, run everything locally on your system.
- [AI Red Team Lab](https://github.com/rodneystanley2025/ai-red-team-lab) - A controlled security evaluation environment designed to assess, harden, and document defenses against adversarial prompt-based attacks on large language model (LLM) systems.
- [AI-Red-Teaming-Playground-Labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) - Challenges for the labs used in the course "AI Red Teaming in Practice".
- [chat-playground](https://virtualsteve-star.github.io/chat-playground/) - Browser-only lab (no backend) to probe moderation, prompt injection, and output-filter bypasses in vulnerable chat models and guardrails.
- [damn-vulnerable-ai-agent](https://github.com/opena2a-org/damn-vulnerable-ai-agent) - A deliberately vulnerable AI agent platform for security testing and education. Like DVWA but for AI agents.
- [damn-vulnerable-MCP-server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) - The Damn Vulnerable Model Context Protocol (DVMCP) is an educational project designed to demonstrate security vulnerabilities in MCP implementations through 10 challenges.
- [DVAIA (Damn Vulnerable AI Application)](https://github.com/genbounty/DVAIA-Damn-Vulnerable-AI-Application) - For LLM Red Team Training. LLM testing, RAG testing, Multimodal testing, Agent testing, LLM payload generation.
- [DVAIB (Damn Vulnerable AI Bank)](https://www.dvaib.com/) - Your training ground for AI security. Exploit a vulnerable AI bank through realistic scenarios, earn achievements, and compete on the leaderboard.
- [finbot-ctf-demo](https://github.com/OWASP-ASI/finbot-ctf-demo) - Agentic-AI CTF around a simulated fintech assistant that exercises goal manipulation, prompt handling, and guardrail weaknesses.
- [Gandalf](https://gandalf.lakera.ai/intro) - Test Your Prompt Injection Skills!
- [llm-attacks](https://portswigger.net/web-security/learning-paths/llm-attacks) - Interactive labs that mirror LLM-enabled web app risks: prompt injection, excessive agency (unsafe tool calls), insecure output handling, and data leakage.
- [llmail-inject-challenge](https://github.com/microsoft/llmail-inject-challenge) - A challenge to evade prompt injection defenses in a simulated LLM-integrated email client, the LLMail service.
- [LLMGoat](https://github.com/SECFORCE/LLMGoat) - This project is a deliberately vulnerable environment to learn about LLM-specific risks based on the OWASP Top 10 for LLM Applications.
- [local-llm-ctf](https://github.com/BishopFox/local-llm-ctf) - Small Go + Ollama harness that routes prompts through “quarantined” vs. “privileged” models to practice bypassing filters and guardrails.
- [Prompt Airlines CTF](https://promptairlines.com/) - Test Your AI Security Skills.
- [PromptMe](https://github.com/R3dShad0w7/PromptMe) - An educational project showcasing security vulnerabilities in LLMs and their web integrations with 10 hands-on challenges inspired by the OWASP LLM Top 10.
- [RedAiRange (RAR)](https://github.com/ErdemOzgen/RedAiRange) - A comprehensive security platform designed specifically for AI red teaming and vulnerability assessment.
