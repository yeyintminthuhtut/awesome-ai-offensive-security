# Awesome AI for Offensive Security

A curated list of awesome AI agents and tools specifically designed for AI-powered offensive security, as well as tools for attacking AI systems.

> **Disclaimer:** This list is for educational and authorized testing purposes only. The primary purpose is to enhance defensive capabilities by understanding how autonomous AI attacks operate and how AI systems can be targeted. Ensure you have explicit permission before using any of these tools against any target.
>
## Contributing

Contributions are very welcome! Please read the [Contribution Guidelines](contributing.md) before submitting a pull request.

> **Note on Accuracy:** The information in this list is provided on a best-effort basis. The AI security landscape evolves rapidly. If you notice any inaccuracies, outdated links, or have suggestions for improvements, please feel free to contribute!

---

## Contents

- [Contributing](#contributing)
- [Offensive AI Agent Skills (3)](#offensive-ai-agent-skills-3)
- [Agent Capability Benchmarks (6)](#agent-capability-benchmarks-6)
- [Offensive AI MCP Servers (7)](#offensive-ai-mcp-servers-7)
- [OSINT Agents & Tools (4)](#osint-agents-tools-4)
- [Pentest & Red Teaming Agents (77)](#pentest-red-teaming-agents-77)
- [AI Cyber Challenge (AIxCC) Systems (3)](#ai-cyber-challenge-aixcc-systems-3)
- [AI Red Teaming (Testing AI Targets) (41)](#ai-red-teaming-testing-ai-targets-41)
- [Security-Focused Models (12)](#security-focused-models-12)
- [Adversarial Machine Learning (13)](#adversarial-machine-learning-13)
- [Vulnerable AI Environments & Labs (18)](#vulnerable-ai-environments-labs-18)

## Offensive AI MCP Servers (7)

MCP (Model Context Protocol) servers that let AI agents invoke real security tools via a standardized protocol.

- [BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) - BloodHound AI integration translating Cypher queries to natural language for AD attack paths.
- [mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) - 38 containerized MCP servers covering 300+ security tools.
- [mcp-server](https://github.com/portswigger/mcp-server) - PortSwigger's official Burp Suite extension bridging Burp with MCP clients.
- [mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) - Shodan API + CVEDB query MCP server.
- [MCP-Kali-Server](https://github.com/Wh0am123/MCP-Kali-Server) - Kali official lightweight API bridge integrating nmap, hydra, sqlmap, metasploit, wpscan, etc.
- [MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) - Metasploit framework MCP bridge supporting exploit generation and session management.
- [pentest-mcp](https://github.com/DMontgomery40/pentest-mcp) - Professional pentester MCP server with nmap, hydra, sqlmap, nuclei, hashcat built-in.

## Offensive AI Agent Skills (3)

Agent Skills that package pentest methodology, tool-chains, and payloads into structured modules for agents to auto-load.

- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - 817 structured skills covering 29 security domains mapped to multiple frameworks.
- [awesome-skills-security](https://github.com/Eyadkelleh/awesome-skills-security) - 7 skill categories based on SecLists (Fuzzing/Wordlists/Payloads/Webshell etc.).
- [ctf-skills](https://github.com/ljagiello/ctf-skills) - CTF full-domain skill package covering Web/Pwn/Crypto/Reverse/Forensics/OSINT etc.

## Agent Capability Benchmarks (6)

Open-source benchmarks for evaluating pentest, cybersecurity, CTF, and red-team Agent capabilities.

- [Cybench](https://github.com/andyzorigin/cybench) - Cybench by Stanford CRFM for professional CTF tasks.
- [CyberGym](https://github.com/sunblaze-ucb/cybergym) - CyberGym by UC Berkeley for real-world vulnerability analysis.
- [CyberSecEval](https://github.com/meta-llama/PurpleLlama) - Meta's CyberSecEval for cybersecurity risks and capabilities in LLMs.
- [InterCode-CTF](https://github.com/princeton-nlp/intercode) - InterCode-CTF for interactive coding with execution feedback.
- [TSecBench](https://tsecbench.zc.tencent.com/) - Tencent Security's unified benchmark for AI agents in offensive/defensive scenarios.
- [XBOW Validation Benchmarks](https://github.com/xbow-engineering/validation-benchmarks) - XBOW Validation Benchmarks with 104 Web vulnerability challenges.

## OSINT Agents & Tools (4)

AI tools focused on Open-Source Intelligence, reconnaissance, and footprinting.

- [DarkBERT](https://huggingface.co/s2w-ai/DarkBERT) - DarkBERT: A Language Model for the Dark Side of the Internet.
- [OSINT-GPT](https://github.com/oryon-osint/OSINT360-GPT) - AI-powered OSINT tool for automated reconnaissance and analysis from public sources.
- [OSINTai](https://github.com/gs-ai/osintai) - A cutting-edge, AI-enhanced web crawler engineered for OSINT professionals, leveraging advanced asynchronous processing, intelligent proxy rotation, and LLM analysis for automated intelligence gathering.
- [Robin](https://github.com/apurvsinghgautam/Robin) - An AI-powered tool designed for dark web OSINT investigations using LLMs to refine searches and summarize results.


## Pentest & Red Teaming Agents (77)

AI-driven autonomous or semi-autonomous agents designed to perform active penetration testing, vulnerability exploitation, and red team engagements.


- [agent](https://github.com/PentesterFlow/agent) - In-terminal Agentic offensive security with Burp integration.
- [agentic-pentest-proxy](https://github.com/IntegSec/agentic-pentest-proxy) - MCP Scope Enforcement Proxy - Middleware that enforces penetration testing engagement scope for AI agents using MCP servers.
- [agentic-radar](https://github.com/splx-ai/agentic-radar) - LLM Agentic workflow security scanner.
- [AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) - Pentesting AI assistant based on open-source LLMs.
- [AI-VAPT](https://github.com/vikramrajkumarmajji/AI-VAPT) - Autonomous AI vulnerability assessment and penetration testing framework.
- [airecon](https://github.com/pikpikcu/airecon) - AIRecon is an autonomous cybersecurity agent that combines a self-hosted Large Language Model (Ollama) with a Kali Linux Docker sandbox and a Textual TUI. It is designed to automate security assessments, penetration testing, and bug bounty reconnaissance.
- [Ankou](https://github.com/Red-Hex-Consulting/Ankou) - A flexible, AI-powered C2 framework built with operators in mind, featuring a built-in AI companion for target analysis.
- [autobb-analyst](https://github.com/rivalsec/autobb-analyst) - Autonomous bug bounty agent powered by Claude Code. A Telegram bot forwards autobb recon alerts to the agent, which actively pentests targets using MongoDB recon data and a self-maintained knowledge wiki.
- [AutoPentest-DRL](https://github.com/crond-jaist/AutoPentest-DRL) - Automates penetration testing using deep reinforcement learning.
- [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - An automated penetration testing toolkit.
- [BoxPwnr](https://github.com/0ca/BoxPwnr) - A modular framework for benchmarking LLMs and agentic strategies on security challenges across HackTheBox, TryHackMe, PortSwigger Labs, Cybench, picoCTF and more.
- [BreachWeave](https://github.com/m-sec-org/BreachWeave) - Manager/Observer/Solver multi-role architecture pentest agent.
- [Bug-Bounty-Agents](https://github.com/matty69v/Bug-Bounty-Agents) - AI-Powered Agents for Bug-Bounty Pentesting and Red-Teaming purposes.
- [bug-reaper](https://github.com/shaniidev/bug-reaper) - Web2 bug bounty Agent Skill that turns any compatible AI agent into a disciplined web2 bug bounty hunter with evidence-based validation.
- [BugTraceAI](https://github.com/BugTraceAI/BugTraceAI) - Autonomous AI-powered security scanning platform combining autonomous AI agents with real security tools to discover, analyze, exploit, and validate vulnerabilities independently.
- [burp-ai-agent](https://github.com/six2dez/burp-ai-agent) - Burp Suite extension that integrates AI into your security workflow using local models or cloud providers, connects external AI agents via MCP, and uses passive/active scanners to find vulnerabilities alongside manual testing.
- [BurpGPT](https://github.com/aress31/burpgpt) - A Burp Suite extension that integrates OpenAI's GPT to perform customized, passive scans to identify vulnerabilities in web applications.
- [Cairn](https://github.com/oritera/Cairn) - General state-space search engine for autonomous pentesting.
- [claude-red](https://github.com/SnailSploit/claude-red) - A curated library of offensive security skills designed for the Claude skills system, priming Claude with expert-level methodology for specific attack surfaces.
- [clearwing](https://github.com/Lazarus-AI/clearwing) - A dual-mode offensive-security tool with a network-pentest agent and source-code hunter using a native Rust-backed LLM runtime.
- [cochise](https://github.com/andreashappe/cochise) - Autonomous Assumed Breach AD Pentesting agent.
- [communitytools](https://github.com/transilienceai/communitytools) - Open-source Claude Code skills, agents, and slash commands for AI-powered penetration testing, bug bounty hunting, and security research.
- [ctf-agent](https://github.com/verialabs/ctf-agent) - Autonomous CTF solver and BSidesSF 2026 winner.
- [Cyber-Zero](https://github.com/amazon-science/Cyber-Zero) - Training cybersecurity agents without runtime.
- [Cybersecurity AI (CAI)](https://github.com/aliasrobotics/cai) - A modular framework for building custom AI security agents across offensive and defensive use cases.
- [CyberStrike](https://github.com/CyberStrikeus/CyberStrike) - AI-driven offensive security agent based on MITRE ATT&CK / CIS / OWASP / NIST.
- [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - Pentesting project with one-command deployment, incorporating tool orchestration and a skills system.
- [Dark-Moon](https://github.com/ASCIT31/Dark-Moon) - Autonomous AI pentesting engine performing continuous offensive security across web, cloud, AD and Kubernetes. Uses agentic reasoning, real exploit execution and attack path analysis to deliver proof-based vulnerabilities.
- [Deadend CLI](https://github.com/xoxruns/deadend-cli) - An AI agent that implements a self-correction mechanism: when an attack fails, the agent analyzes the error, rewrites the approach, and retries.
- [Decepticon](https://github.com/PurpleAILAB/Decepticon) - An AI agent built on LangChain/LangGraph designed to automate red teaming before attackers automate theirs.
- [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - A fully automatic penetration test tool utilizing Deep Reinforcement Learning.
- [DeepSeek-Pentest-AI](https://github.com/HernanRodriguez1/DeepSeek-Pentest-AI) - A Burp Suite extension combining generative AI with smart fuzzing to automate payload generation and vulnerability testing in web applications.
- [EVA](https://github.com/ARCANGEL0/EVA) - AI-assisted pentesting agent with multi-backend AI integration.
- [guardian-cli](https://github.com/zakirkun/guardian-cli) - AI-powered penetration testing automation CLI tool that leverages Google Gemini and LangChain to orchestrate intelligent, step-by-step penetration testing workflows.
- [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - An autonomous pentesting agent and research framework used for exploring and exploiting environments such as Active Directory.
- [HackSynth](https://github.com/aielte-research/HackSynth) - Planner & Summarizer dual-module pentest agent.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - An MCP server that acts as a control layer between LLMs and over 150 security tools, allowing agents to execute tools, adapt strategies, and generate reports.
- [iothackbot](https://github.com/BrownFineSecurity/iothackbot) - Open-source IoT security testing toolkit with integrated Claude Code skills for automated vulnerability discovery.
- [Katana AI Agents](https://github.com/Armur-Ai/Katana-AI-Agents-for-website-vulnerabilities-scanning) - LLM powered agents for scanning vulnerabilities on any website (Llama 3 8B, Groq, Selenium, CrewAI, Exa AI).
- [LuaN1aoAgent](https://github.com/SanMuzZzZz/LuaN1aoAgent) - A next-generation Autonomous Penetration Testing Agent powered by LLMs, integrating the Planner-Executor-Reflector (P-E-R) Framework with Causal Graph Reasoning.
- [lyrie-ai](https://github.com/OTT-Cybersecurity-LLC/lyrie-ai) - Lyrie.ai — The world's first autonomous AI cybersecurity agent. Built by OTT Cybersecurity LLC.
- [MAPTA (Multi-Agent Penetration Testing AI)](https://github.com/arthurgervais/mapta) - An autonomous web application security assessment system orchestrating large language models and tool execution. ([ArXiv Paper](https://arxiv.org/abs/2508.20816))
- [METATRON](https://github.com/sooryathejas/METATRON) - AI-powered penetration testing assistant using local LLM on linux (Parrot OS).
- [Nebula](https://github.com/berylliumsec/nebula) - An AI-powered ethical hacking assistant that embeds AI capabilities into the terminal to assist with reconnaissance and note-taking.
- [Nettacker](https://github.com/OWASP/Nettacker) - OWASP's automated penetration testing and vulnerability scanning framework.
- [NeuroSploit](https://github.com/CyberSecurityUP/NeuroSploit) - AI-driven autonomous agents with 100 vulnerability types, per-scan isolated Kali Linux containers, false-positive hardening, exploit chaining, and a modern React web interface with real-time monitoring.
- [nyuctf_agents](https://github.com/NYU-LLM-CTF/nyuctf_agents) - The D-CIPHER and NYU CTF baseline LLM Agents built for NYU CTF Bench.
- [OctoScan](https://github.com/Coucoudb/OctoScan) - A versatile CLI tool orchestrating pentest tools for automated security audits, bug bounty, pentest.
- [Offensive-AI-Agent-Prompts](https://github.com/CyberSecurityUP/Offensive-AI-Agent-Prompts) - Prompts for performing tests on your Kali Linux using Gemini-cli, ChatGPT, DeepSeek, CursorAI, Claude Code, and Copilot.
- [Offensive-AI-Attack-Path-Visualizer](https://github.com/HackerBlazeX/Offensive-AI-Attack-Path-Visualizer) - A Windows-first offensive security framework that correlates recon signals, applies AI reasoning via local LLM, and generates realistic attack paths in an analyst-friendly dashboard.
- [oh-my-open-pentest](https://github.com/zakirkun/oh-my-open-pentest) - An AI agent that runs penetration tests. End to end. No babysitting.
- [OpenAnt](https://github.com/knostic/OpenAnt) - An open-source, LLM-based vulnerability discovery product that proactively finds and verifies security flaws through a two-stage detection and attack process.
- [PentAGI](https://github.com/vxcontrol/pentagi) - A multi-agent framework using specialized AI roles for research, coding, and infrastructure to operate autonomously for vulnerability detection.
- [Pentest Copilot](https://github.com/bugbasesecurity/pentest-copilot) - An AI-powered, browser-based ethical hacking assistant designed for pentesting workflows, deployable locally with Docker.
- [pentest-agents](https://github.com/H-mmer/pentest-agents) - Autonomous bug-bounty framework for Claude Code — 40 specialist agents, exploit-chain builder, writeup search, and live HackerOne/Bugcrowd integration.
- [pentest-ai](https://github.com/0xSteph/pentest-ai) - Offensive-security MCP server with 205 wrapped tools, 17 specialist agents, and 60 SPA-aware probes for OWASP Top 10. CLI + MCP, BYO LLM.
- [pentest-ai-agents](https://github.com/0xSteph/pentest-ai-agents) - Turn Claude Code into your offensive security research assistant. Specialized AI subagents for authorized penetration testing plan engagements, analyze recon, research exploits, build detections, audit STIGs, and write reports.
- [Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI) - Autonomous penetration testing using a swarm of AI agents. Orchestrates recon, classification, exploitation, and reporting specialists with ReAct reasoning.
- [PentestAgent](https://github.com/GH05TCREW/pentestagent) - An AI agent framework for black-box security testing, supporting bug bounty, red-team, and penetration testing workflows.
- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - A penetration testing tool powered by ChatGPT. Automates penetration testing by guiding the user and interacting with underlying tools like Nmap and Gobuster.
- [phalanx](https://github.com/webxos/phalanx) - Kali Linux Polyglot Harness for Autonomous Pentesting/Cyber Security.
- [RAPTOR](https://github.com/gadievron/raptor) - An autonomous offensive/defensive security research framework based on Claude Code, empowering security research with agentic workflows and automation (Recursive Autonomous Penetration Testing and Observation Robot).
- [Reaper](https://github.com/ghostsecurity/reaper) - Ghost Security's reconnaissance and attack surface discovery tool used for pentesting and identifying exposures.
- [RedAmon](https://github.com/samugit83/RedAmon) - An AI-powered agentic red team framework designed to automate offensive security operations from recon to exploitation.
- [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) - AI-powered skill router for reverse engineering and authorized penetration testing workflows.
- [seclab-taskflow-agent](https://github.com/GitHubSecurityLab/seclab-taskflow-agent) - GitHub Security Lab YAML-driven multi-agent framework.
- [Shannon](https://github.com/KeygraphHQ/shannon) - Autonomous AI pentesting tool functioning as a virtual hacker to identify and exploit vulnerabilities, evaluated against benchmarks like XBOW.
- [Strix](https://github.com/usestrix/strix) - An AI-powered tool that simulates attacker behavior by executing applications and generating working proof-of-concept exploits.
- [T3MP3ST](https://github.com/elder-plinius/T3MP3ST) - A multi-agent offensive-security framework for authorized red teaming, vulnerability discovery, and reporting workflows.
- [ThreatSwarm](https://github.com/mukul975/ThreatSwarm) - 27 scope-enforced AI agents that run the full pentest kill-chain (recon → exploit → post-ex → DFIR → report) as a one-command Claude Code plugin. Backed by 754 MITRE-mapped skills.
- [tinyctfer](https://github.com/chainreactors/tinyctfer) - CTF Agent with micro-intent runtime.
- [TTPRunner](https://github.com/Antonlovesdnb/TTPRunner) - Autonomous execution agent for purple team operations. Processes threat reports to build and run attack plans based on Tactics, Techniques, and Procedures.
- [VulnBot](https://github.com/KHenryAegis/VulnBot) - Multi-agent collaborative framework for autonomous pentesting.
- [vulnhuntr](https://github.com/protectai/vulnhuntr) - LLM zero-shot vulnerability discovery agent.
- [watchtower](https://github.com/fzn0x/watchtower) - Watchtower is a simple AI-powered penetration testing automation CLI tool that leverages LLMs and LangGraph to orchestrate agentic workflows that you can use to test your websites locally. Generate useful pentest reports for your websites.
- [xalgorix](https://github.com/xalgord/xalgorix) - Open-source AI penetration testing agent.
- [Zen-Ai-Pentest](https://github.com/SHAdd0WTAka/Zen-Ai-Pentest) - An AI-Powered Penetration Testing Framework with automated vulnerability scanning, multi-agent system, and compliance reporting.

## AI Cyber Challenge (AIxCC) Systems (3)

Highly advanced vulnerability discovery & patching agents from DARPA:

- [artiphishell](https://github.com/shellphish/artiphishell) - Shellphish's AIxCC CRS.
- [atlantis](https://github.com/Team-Atlanta/aixcc-afc-atlantis) - Team Atlanta's AIxCC CRS.
- [buttercup](https://github.com/trailofbits/buttercup) - Trail of Bits' AIxCC CRS.

## AI Red Teaming (Testing AI Targets) (41)

Tools specifically designed to test the security of AI systems, LLMs, and autonomous agents (e.g., finding prompt injections, jailbreaks, data leaks).

- [AASRT](https://github.com/0xsrb/AASRT) - Automates the discovery of publicly exposed AI agent implementations using the Shodan search engine API through passive reconnaissance.
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - Dynamic environment to evaluate attacks and defenses for LLM agents.
- [AgentFence](https://github.com/agentfence/agentfence) - A platform for automatically testing and securing AI agents against prompt injection, memory manipulation, and workflow corruption.
- [AgenticRed](https://github.com/yuanjiayiy/AgenticRed) - An automated pipeline that leverages LLMs' in-context learning to iteratively design and refine red-teaming systems without human intervention.
- [Agentic Security](https://github.com/msoedov/agentic_security) - An open-source vulnerability scanner designed to protect AI systems and agent workflows by identifying jailbreaks, fuzzing, and multimodal attacks in LLMs.
- [AgentPoison](https://github.com/AI-secure/AgentPoison) - Red-teaming LLM Agents via Memory or Knowledge Base Backdoor Poisoning.
- [agent-scan](https://github.com/snyk/agent-scan) - Discover and scan agent components on your machine for prompt injections and vulnerabilities (including agents, MCP servers, skills).
- [ai-bom](https://github.com/Trusera/ai-bom) - Tool designed to discover every AI agent, model, and API hiding in your infrastructure.
- [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - A comprehensive AI Red Teaming platform developed by Tencent Zhuque Lab that integrates modules for Infra Scan, MCP Scan, and Jailbreak Evaluation.
- [ares](https://github.com/IBM/ares) - A red-teaming programming model for the automated orchestration of AI robustness evaluations natively integrating existing plugins.
- [ARES-Dashboard](https://github.com/Arnoldlarry15/ARES-Dashboard) - An enterprise-oriented AI red team operations console for planning, executing, and auditing structured adversarial testing of AI systems across established risk frameworks.
- [argus-core](https://github.com/Odingard/argus-core) - An open-core platform with two agents that tests the AI-specific attack surface against any registered target type.
- [ARTKIT](https://github.com/BCG-X-Official/artkit) - An open-source framework for automated LLM red teaming that simulates multi-turn attacker–target interactions.
- [augustus](https://github.com/praetorian-inc/augustus) - LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks.
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
- [PyMLOKit](https://github.com/ThanniKudam/PyMLOKit) - Toolkit to attack MLOps platforms via REST APIs, supporting modules for reconnaissance, training data theft, model theft, model poisoning, and notebook attacks.
- [PyRIT (Python Risk Identification Tool)](https://github.com/Azure/PyRIT) - An open-source automation framework from Microsoft's AI Red Team for programmatic multi-turn orchestration and custom attack scenarios against AI systems.
- [rogue](https://github.com/qualifire-dev/rogue) - Tool to stress-test your AI agents before attackers do by finding prompt injection, sensitive data exposure, and excessive agency.
- [spikee](https://github.com/ReversecLabs/spikee) - Simple prompt injection kit for evaluation and exploitation.
- [system-prompt-benchmark](https://github.com/KazKozDev/system-prompt-benchmark) - Test your LLM system prompts against 287 real-world attack vectors, including prompt injection, jailbreaks, and data leaks.
- [vigil-llm](https://github.com/deadbits/vigil-llm) - Detects prompt injections, jailbreaks, and other potentially risky large language model inputs.
- [whistleblower](https://github.com/Repello-AI/whistleblower) - Offensive security tool for testing against system prompt leakage and capability discovery of an AI application exposed through API.

## Security-Focused Models (12)

Models fine-tuned or built for cybersecurity reasoning, red-team support, blue-team analysis, and AI security workflows.

- [BaronLLM](https://huggingface.co/AlicanKiraz0) - Offensive security LLM focused on exploits and attack chains.
- [BugTraceAI-CORE-Ultra-27B](https://huggingface.co/BugTraceAI/BugTraceAI-CORE-Ultra-27B-Q6) - Focused on vulnerability discovery and Nuclei template generation.
- [CyberSecQwen-4B](https://huggingface.co/athena129/CyberSecQwen-4B) - Defensive security model.
- [CyberStrike-OffSec-35B](https://huggingface.co/oyildirim/CyberStrike-OffSec-35B) - 35B MoE offensive security model (uncensored).
- [Foundation-Sec-8B-Reasoning](https://huggingface.co/fdtn-ai/Foundation-Sec-8B-Reasoning) - Cisco Foundation AI's security reasoning model.
- [Lily-Cybersecurity-7B-v0.2](https://huggingface.co/segolilylabs/Lily-Cybersecurity-7B-v0.2) - Cybersecurity/hacker QA model without strong refusal alignment.
- [Meta-SecAlign-8B](https://github.com/facebookresearch/Meta_SecAlign) - Model with built-in prompt injection defense.
- [Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/bestexhibitions/Qwythos-9B-Claude-Mythos-5-1M) - Uncensored reasoning model trained on Claude's chain-of-thought.
- [security-slm-unsloth-1.5b](https://huggingface.co/Nguuma/security-slm-unsloth-1.5b) - A 1.5B cybersecurity reasoning model fine-tuned for offline red-team, blue-team, threat analysis, and AI security workflows.
- [Titus-CybersecurityLLM-v1.0](https://huggingface.co/AlicanKiraz0/Titus-CybersecurityLLM-v1.0-mlx-4Bit) - SOC/DFIR operations model.
- [VulnLLM-R-7B](https://github.com/ucsb-mlsec/VulnLLM-R) - Vulnerability discovery reasoning model.
- [WhiteRabbitNeo / DeepHat](https://huggingface.co/WhiteRabbitNeo) - The well-known uncensored red-team model family.

## Adversarial Machine Learning (13)

Tools and libraries focused on the security of classical and deep machine learning models, including evasion, poisoning, extraction, and inference attacks.


- [Ad-lib](https://github.com/vu-aml/adlib) - Game-theoretic adversarial machine learning library providing a set of learner and adversary modules.
- [Adversarial Images](https://github.com/tabacof/adversarial) - Repository exploring the space of adversarial images.
- [Adversarial Robustness Toolkit](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - Focuses on the threats of evasion, poisoning, extraction, and inference.
- [BadDiffusion](https://github.com/IBM/BadDiffusion) - Official repository to reproduce the paper on backdooring diffusion models published at CVPR 2023.
- [Charcuterie](https://github.com/moohax/Charcuterie) - Code execution techniques for ML or ML adjacent libraries.
- [cleverhans](https://github.com/cleverhans-lab/cleverhans) - Adversarial example library for constructing attacks, building defenses, and benchmarking both.
- [Counterfit](https://github.com/Azure/counterfit) - Generic automation layer for assessing the security of machine learning systems.
- [Deep-pwning](https://github.com/cchio/deep-pwning) - Lightweight framework for experimenting with machine learning models to evaluate their robustness against adversaries.
- [DeepFool](https://github.com/LTS4/DeepFool) - Method to fool deep neural networks.
- [foolbox](https://github.com/bethgelab/foolbox) - Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX.
- [Gym malware](https://github.com/endgameinc/gym-malware) - Environment that makes it possible to write agents that learn to manipulate PE files to bypass AV based on a reward.
- [OffsecML Playbook](https://github.com/5stars217/offsecml/) - Collection of offensive and adversarial TTPs with proofs of concept.
- [TextAttack](https://github.com/QData/TextAttack) - Python framework for adversarial attacks, data augmentation, and model training in NLP.

## Vulnerable AI Environments & Labs (18)

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
