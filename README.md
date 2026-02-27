# Awesome LLM-based Human Simulation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/Persdre/awesome-llm-human-simulation/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A curated list of research papers and resources on **LLM-based Human Simulation** — the use of Large Language Models to simulate human behavior, cognition, and social interactions. This rapidly growing field spans psychology, economics, education, political science, and AI safety.

Contributions are welcome! If you would like to add a paper, please open a [pull request](https://github.com/Persdre/awesome-llm-human-simulation/pulls).

---

## Table of Contents

- [1. Foundations & Surveys](#1-foundations--surveys)
- [2. LLM for Human Behavior Simulation](#2-llm-for-human-behavior-simulation)
- [3. LLM Agent](#3-llm-agent)
- [4. LLM Bias & Value](#4-llm-bias--value)
- [5. LLM Simulation Applications](#5-llm-simulation-applications)
  - [5.1 Economics & Finance](#51-economics--finance)
  - [5.2 Politics & Society](#52-politics--society)
  - [5.3 Education](#53-education)
  - [5.4 Recommendation System & User Simulation](#54-recommendation-system--user-simulation)
  - [5.5 Customer & Consumer Simulation](#55-customer--consumer-simulation)
  - [5.6 Others](#56-others)
- [6. LLM Evaluation](#6-llm-evaluation)
- [7. Cognition & Psychology](#7-cognition--psychology)
- [8. Social Simulation](#8-social-simulation)
- [9. Conference](#9-conference)
- [10. Others](#10-others)
- [Acknowledgement](#acknowledgement)
- [Citation](#citation)

---

## 1. Foundations & Surveys

- **From Persona to Personalization: A Survey on Role-Playing Language Agents** (arXiv, 2024.04) [[Paper](https://arxiv.org/pdf/2404.18231)]
- **Can Large Language Models Transform Computational Social Science?** (Computational Linguistics, 2024.03) [[Paper](https://direct.mit.edu/coli/article-pdf/doi/10.1162/coli_a_00502/2191886/coli_a_00502.pdf)]
- **Exploring the Frontiers of LLMs in Psychological Applications: A Comprehensive Review** (arXiv, 2024.01) [[Paper](https://arxiv.org/pdf/2401.01519)]
- **Towards a Psychological Generalist AI: A Survey of Current Applications of Large Language Models and Future Prospects** (arXiv, 2023.12) [[Paper](https://arxiv.org/abs/2312.04578)]
- **Using Large Language Models in Psychology** (Nature Reviews Psychology, 2023.10) [[Paper](https://static1.squarespace.com/static/53d29678e4b04e06965e9423/t/6566e06ac95b0b61f8810a99/1701240942374/2023+--+LLMs+psychology.pdf)]
- **Emergent Abilities of Large Language Models** (arXiv, 2022.06) [[Paper](https://arxiv.org/pdf/2206.07682)]

## 2. LLM for Human Behavior Simulation

- **Lost in Simulation: LLM-Simulated Users are Unreliable Proxies for Human Users in Agentic Evaluations** (arXiv, 2026.01) [[Paper](https://arxiv.org/abs/2601.17087)]
- **Consistently Simulating Human Personas with Multi-Turn Reinforcement Learning** (NeurIPS, 2025) [[Paper](https://arxiv.org/abs/2511.00222)] [[Code](https://github.com/abdulhaim/consistent-LLMs)]
- **A Mega-Study of Digital Twins Reveals Strengths, Weaknesses and Opportunities for Further Improvement** (arXiv, 2025.09) [[Paper](https://arxiv.org/abs/2509.19088)]
- **How Many Human Survey Respondents is a Large Language Model Worth? An Uncertainty Quantification Perspective** (arXiv, 2025.02) [[Paper](https://arxiv.org/abs/2502.17773)] [[Code](https://github.com/yw3453/uq-llm-survey-simulation)]
- **Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations** (EMNLP, 2025) [[Paper](https://arxiv.org/abs/2509.16457)] [[Code](https://github.com/HATS-ICT/PEBA-ASI)]
- **Generative Agent Simulations of 1,000 People** (arXiv, 2024.11) [[Paper](https://arxiv.org/pdf/2411.10109)]
- **Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers** (arXiv, 2024.09) [[Paper](https://arxiv.org/pdf/2409.04109)] [[Code](https://github.com/NoviScl/AI-Researcher)]
- **Language Models Show Stable Value Orientations Across Diverse Role-Plays** (arXiv, 2024.08) [[Paper](https://arxiv.org/pdf/2408.09049)]
- **PsychoGAT: A Novel Psychological Measurement Paradigm through Interactive Fiction Games with LLM Agents** (ACL, 2024) [[Paper](https://aclanthology.org/2024.acl-long.779.pdf)]
- **Limited Ability of LLMs to Simulate Human Psychological Behaviours: A Psychometric Analysis** (arXiv, 2024.05) [[Paper](https://arxiv.org/abs/2405.07248)]
- **Is Cognition and Action Consistent or Not: Investigating Large Language Model's Personality** (arXiv, 2024.02) [[Paper](https://arxiv.org/abs/2402.14679)]
- **LLM Agents for Psychology: A Study on Gamified Assessments** (arXiv, 2024.02) [[Paper](https://arxiv.org/pdf/2402.12326)]
- **Quantifying the Persona Effect in LLM Simulations** (arXiv, 2024.02) [[Paper](https://arxiv.org/abs/2402.10811)] [[Code](https://github.com/cambridgeltl/persona_effect)]
- **"Kelly Is a Warm Person, Joseph Is a Role Model": Gender Biases in LLM-Generated Reference Letters** (arXiv, 2023.10) [[Paper](https://arxiv.org/pdf/2310.09219)] [[Code](https://github.com/uclanlp/biases-llm-reference-letters)]
- **Personality Traits in Large Language Models** (arXiv, 2023.07) [[Paper](https://arxiv.org/pdf/2307.00184)] [[Code](https://github.com/google-research/google-research/tree/master/psyborgs)]
- **Role Play with Large Language Models** (Nature, 2023.11) [[Paper](https://arxiv.org/pdf/2305.16367)]
- **The Challenge of Using LLMs to Simulate Human Behavior: A Causal Inference Perspective** (arXiv, 2023.12) [[Paper](https://arxiv.org/abs/2312.15524)]
- **Meet Your Favorite Character: Open-Domain Chatbot Mimicking Fictional Characters with Only a Few Utterances** (arXiv, 2022.04) [[Paper](https://arxiv.org/pdf/2204.10825)]

## 3. LLM Agent

- **An LLM-based Simulation Framework for Embodied Conversational Agents in Psychological Counseling** (arXiv, 2024.10) [[Paper](https://arxiv.org/pdf/2410.22041v1)] [[Code](https://github.com/AIR-DISCOVER/ECAs-Dataset)]
- **MegaAgent: A Practical Framework for Autonomous Cooperation in Large-Scale LLM Agent Systems** (arXiv, 2024.08) [[Paper](https://arxiv.org/pdf/2408.09955)]
- **Hello Again! LLM-powered Personalized Agent for Long-term Dialogue** (arXiv, 2024.06) [[Paper](https://arxiv.org/abs/2406.05925)] [[Code](https://github.com/leolee99/LD-Agent)]
- **Towards Lifelong Learning of Large Language Models: A Survey** (arXiv, 2024.06) [[Paper](https://arxiv.org/pdf/2406.06391)] [[Code](https://github.com/qianlima-lab/awesome-lifelong-learning-methods-for-llm)]
- **Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents** (arXiv, 2024.05) [[Paper](https://arxiv.org/pdf/2405.02957)]
- **MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-Oriented Coordination via Collaborative Generative Agents** (arXiv, 2023.10) [[Paper](https://arxiv.org/pdf/2310.06500)]
- **Agents: An Open-Source Framework for Autonomous Language Agents** (arXiv, 2023.09) [[Paper](https://arxiv.org/pdf/2309.07870)] [[Code](https://github.com/aiwaves-cn/agents)]
- **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework** (arXiv, 2023.08) [[Paper](https://arxiv.org/pdf/2308.08155)] [[Code](https://github.com/microsoft/autogen)]
- **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** (arXiv, 2023.08) [[Paper](https://arxiv.org/pdf/2308.00352)] [[Code](https://github.com/geekan/MetaGPT)]
- **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents** (arXiv, 2023) [[Paper](https://cz5waila03cyo0tux1owpyofgoryroob.itic-sci.com/9C/54/B4/9C54B47616795A320E36FCB1EA595C91.pdf)] [[Code](https://github.com/OpenBMB/AgentVerse)]

## 4. LLM Bias & Value

- **Gender Bias of LLM in Economics: An Existentialism Perspective** (arXiv, 2024.10) [[Paper](https://arxiv.org/pdf/2410.19775)]
- **Measuring Human and AI Values based on Generative Psychometrics with Large Language Models** (arXiv, 2024.09) [[Paper](https://arxiv.org/pdf/2409.12106)] [[Code](https://github.com/Value4AI/gpv)]
- **United in Diversity? Contextual Biases in LLM-Based Predictions of the 2024 European Parliament Elections** (arXiv, 2024.08) [[Paper](https://arxiv.org/pdf/2409.09045)]
- **Representation Bias in Political Sample Simulations with Large Language Models** (arXiv, 2024.07) [[Paper](https://arxiv.org/pdf/2407.11409)]
- **New Job, New Gender? Measuring the Social Bias in Image Generation Models** (MM, 2024) [[Paper](https://arxiv.org/pdf/2401.00763)]
- **Whose Opinions Do Language Models Reflect?** (ICML, 2023) [[Paper](https://proceedings.mlr.press/v202/santurkar23a/santurkar23a.pdf)]
- **Not All Countries Celebrate Thanksgiving: On the Cultural Dominance in Large Language Models** (arXiv, 2023.10) [[Paper](https://arxiv.org/pdf/2310.12481)]
- **Probing Explicit and Implicit Gender Bias through LLM Conditional Text Generation** (arXiv, 2023.11) [[Paper](https://arxiv.org/pdf/2311.00306)]
- **Evaluating the Moral Beliefs Encoded in LLMs** (NeurIPS, 2023) [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/a2cf225ba392627529efef14dc857e22-Paper-Conference.pdf)] [[Code](https://github.com/ninodimontalcino/moralchoice)]
- **When to Make Exceptions: Exploring Language Models as Accounts of Human Moral Judgment** (NeurIPS, 2022) [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/b654d6150630a5ba5df7a55621390daf-Paper-Conference.pdf)] [[Code](https://github.com/feradauto/MoralCoT)]

## 5. LLM Simulation Applications

### 5.1 Economics & Finance

- **AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions** (arXiv, 2026.02) [[Paper](https://arxiv.org/abs/2602.06008)] [[Code](https://github.com/SafeRL-Lab/AgenticPay)]
- **Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?** (ACM EC, 2024) [[Paper](https://arxiv.org/abs/2301.07543)]
- **Measuring Bargaining Abilities of LLMs: A Benchmark and A Buyer-Enhancement Method** (Findings of ACL, 2024) [[Paper](https://arxiv.org/abs/2402.15813)]
- **CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading** (arXiv, 2024.06) [[Paper](https://arxiv.org/abs/2407.09546)] [[Code](https://anonymous.4open.science/r/CryptoTrade-Public-92FC/)]
- **Simulating Financial Market via Large Language Model Based Agents** (arXiv, 2024.06) [[Paper](https://arxiv.org/pdf/2406.19966)]
- **EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities** (ACL, 2024) [[Paper](https://aclanthology.org/2024.acl-long.829.pdf)] [[Code](https://github.com/tsinghua-fib-lab/ACL24-EconAgent)]
- **Designing Heterogeneous LLM Agents for Financial Sentiment Analysis** (ACM TMIS, 2024.08) [[Paper](https://dl.acm.org/doi/pdf/10.1145/3688399)]

### 5.2 Politics & Society

- **Auditing Political Exposure Bias: Algorithmic Amplification on Twitter/X Approaching the 2024 US Presidential Election** (arXiv, 2024.11) [[Paper](https://arxiv.org/pdf/2411.01852)]
- **GermanPartiesQA: Benchmarking Commercial Large Language Models for Political Bias and Sycophancy** (arXiv, 2024.07) [[Paper](https://arxiv.org/pdf/2407.18008)]
- **Simulating The U.S. Senate: An LLM-Driven Agent Approach to Modeling Legislative Behavior and Bipartisanship** (arXiv, 2024.06) [[Paper](https://arxiv.org/pdf/2406.18702)]
- **Trump, Twitter, and Truth Social: How Trump Used Both Mainstream and Alt-Tech Social Media to Drive News Media Attention** (Journal of Information Technology & Politics, 2024.03) [[Paper](https://doi.org/10.1080/19331681.2024.2328156)]
- **War and Peace (WarAgent): Large Language Model-Based Multi-Agent Simulation of World Wars** (arXiv, 2023.11) [[Paper](https://arxiv.org/pdf/2311.17227)] [[Code](https://github.com/agiresearch/WarAgent)]

### 5.3 Education

- **Large Language Model as an Assignment Evaluator: Insights, Feedback, and Challenges in a 1000+ Student Course** (arXiv, 2024.07) [[Paper](https://arxiv.org/abs/2407.05216)]
- **Simulating Classroom Education with LLM-Empowered Agents** (arXiv, 2024.06) [[Paper](https://arxiv.org/pdf/2406.19226)]
- **Generative Students: Using LLM-Simulated Student Profiles to Support Question Item Evaluation** (arXiv, 2024.05) [[Paper](https://arxiv.org/pdf/2405.11591)]
- **MathVC: An LLM-Simulated Multi-Character Virtual Classroom for Mathematics Education** (arXiv, 2024.04) [[Paper](https://arxiv.org/pdf/2404.06711)]
- **PhysicsAssistant: An LLM-Powered Interactive Learning Robot for Physics Lab Investigations** (arXiv, 2024.03) [[Paper](https://arxiv.org/pdf/2403.18721)]

### 5.4 Recommendation System & User Simulation

- **PUB: An LLM-Enhanced Personality-Driven User Behaviour Simulator for Recommender System Evaluation** (SIGIR, 2025) [[Paper](https://arxiv.org/abs/2506.04551)]
- **LLM as User Simulator: Towards Training News Recommender without Real User Interactions** (SIGIR, 2025) [[Paper](https://dl.acm.org/doi/10.1145/3726302.3730224)]
- **Agentic Feedback Loop Modeling Improves Recommendation and User Simulation** (SIGIR, 2025) [[Paper](https://arxiv.org/abs/2410.20027)] [[Code](https://github.com/Lanyu0303/AFL)]
- **SimUSER: Simulating User Behavior with Large Language Models for Recommender System Evaluation** (ACL Industry, 2025) [[Paper](https://arxiv.org/abs/2504.12722)]
- **A LLM-based Controllable, Scalable, Human-Involved User Simulator Framework for Conversational Recommender Systems** (WWW, 2025) [[Paper](https://arxiv.org/abs/2405.08035)]
- **RecUserSim: A Realistic and Diverse User Simulator for Evaluating Conversational Recommender Systems** (WWW Companion, 2025) [[Paper](https://arxiv.org/abs/2507.22897)]
- **LLM-Powered User Simulator for Recommender System** (AAAI, 2025) [[Paper](https://arxiv.org/abs/2412.16984)]
- **RecAgent: User Behavior Simulation with Large Language Model-based Agents** (ACM TOIS, 2024) [[Paper](https://arxiv.org/abs/2306.02552)] [[Code](https://github.com/RUC-GSAI/YuLan-Rec)]
- **BASES: Large-scale Web Search User Simulation with Large Language Model based Agents** (Findings of EMNLP, 2024) [[Paper](https://arxiv.org/abs/2402.17505)]
- **Reliable LLM-based User Simulator for Task-Oriented Dialogue Systems** (SCI-CHAT Workshop, 2024) [[Paper](https://arxiv.org/abs/2402.13374)]
- **A Survey on Large Language Models for Recommendation** (arXiv, 2024.08) [[Paper](https://arxiv.org/pdf/2305.19860)] [[Code](https://github.com/WLiK/LLM4Rec-Awesome-Papers)]
- **LLM-Rec: Personalized Recommendation via Prompting Large Language Models** (arXiv, 2024.07) [[Paper](https://arxiv.org/pdf/2307.15780)]
- **Generating Personalized Recommendations via Large Language Models (LLMs)** (Technical Disclosure Commons, 2022.12) [[Paper](https://www.tdcommons.org/cgi/viewcontent.cgi?article=6685&context=dpubs_series)]

### 5.5 Customer & Consumer Simulation

- **ShopSimulator: Evaluating and Exploring RL-Driven LLM Agent for Shopping Assistants** (arXiv, 2026.01) [[Paper](https://arxiv.org/abs/2601.18225)]
- **Customer-R1: Personalized Simulation of Human Behaviors via RL-based LLM Agent in Online Shopping** (arXiv, 2025.10) [[Paper](https://arxiv.org/abs/2510.07230)]
- **See, Think, Act: Online Shopper Behavior Simulation with VLM Agents** (NeurIPS, 2025) [[Paper](https://arxiv.org/abs/2510.19245)]
- **Shop-R1: Rewarding LLMs to Simulate Human Behavior in Online Shopping via Reinforcement Learning** (NeurIPS SEA Workshop, 2025) [[Paper](https://arxiv.org/abs/2507.17842)]
- **LLMs Reproduce Human Purchase Intent via Semantic Similarity Elicitation of Likert Ratings** (arXiv, 2025.10) [[Paper](https://arxiv.org/abs/2510.08338)] [[Code](https://github.com/pymc-labs/semantic-similarity-rating)]
- **LLM Agent Meets Agentic AI: Can LLM Agents Simulate Customers to Evaluate Agentic-AI-based Shopping Assistants?** (arXiv, 2025.09) [[Paper](https://arxiv.org/abs/2509.21501)]
- **What Is Your AI Agent Buying? Evaluation, Biases, Model Dependence, & Emerging Implications for Agentic E-Commerce** (arXiv, 2025.08) [[Paper](https://arxiv.org/abs/2508.02630)]
- **ShoppingBench: A Real-World Intent-Grounded Shopping Benchmark for LLM-based Agents** (arXiv, 2025.08) [[Paper](https://arxiv.org/abs/2508.04266)]
- **LLM-Based Multi-Agent System for Simulating and Analyzing Marketing and Consumer Behavior** (IEEE ICEBE, 2025) [[Paper](https://arxiv.org/abs/2510.18155)]
- **Predicting Behaviors with Large Language Model (LLM)-Powered Digital Twins of Consumers** (MSI Working Paper, 2025) [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5256223)]
- **AI-Human Hybrids for Marketing Research: Leveraging Large Language Models (LLMs) as Collaborators** (Journal of Marketing, 2025) [[Paper](https://journals.sagepub.com/doi/abs/10.1177/00222429241276529)]
- **Large Language Models for Market Research: A Data-augmentation Approach** (arXiv, 2024.12) [[Paper](https://arxiv.org/abs/2412.19363)]
- **Can Large Language Models Capture Human Preferences?** (Marketing Science, 2024) [[Paper](https://arxiv.org/abs/2305.02531)]
- **Can LLM Agents Simulate Multi-Turn Human Behavior? Evidence from Real Online Customer Behavior Data** (arXiv, 2025.03) [[Paper](https://arxiv.org/abs/2503.20749)]
- **Using LLMs for Market Research** (Harvard Business School Working Paper, 2025) [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4395751)]
- **Challenges and Opportunities of LLM-Based Synthetic Personae and Data in HCI** (CHI EA, 2024) [[Paper](https://dl.acm.org/doi/10.1145/3613905.3636293)]

### 5.6 Others

- **Improve Temporal Awareness of LLMs for Sequential Recommendation** (arXiv, 2024.05) [[Paper](https://arxiv.org/pdf/2405.02778)]
- **How Far Are We on the Decision-Making of LLMs? Evaluating LLMs' Gaming Ability in Multi-Agent Environments** (arXiv, 2024.03) [[Paper](https://arxiv.org/pdf/2403.11807)] [[Code](https://github.com/CUHK-ARISE/GAMABench)]
- **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** (arXiv, 2023.09) [[Paper](https://arxiv.org/pdf/2309.04658)]
- **The SocialAI School: Insights from Developmental Psychology towards Artificial Socio-Cultural Agents** (arXiv, 2023.07) [[Paper](https://arxiv.org/pdf/2307.07871)] [[Code](https://sites.google.com/view/socialai-school)]

## 6. LLM Evaluation

- **Benchmarking LLMs' Judgments with No Gold Standard** (arXiv, 2024.11) [[Paper](https://arxiv.org/pdf/2411.07127)]
- **Cognitive Overload Attack: Prompt Injection for Long Context** (arXiv, 2024.10) [[Paper](https://arxiv.org/abs/2410.11272)]
- **Moral Alignment for LLM Agents** (arXiv, 2024.10) [[Paper](https://arxiv.org/pdf/2410.01639)]
- **Revealing the Challenge of Detecting Character Knowledge Errors in LLM Role-Playing** (arXiv, 2024.09) [[Paper](https://arxiv.org/pdf/2409.11726)] [[Code](https://github.com/WYRipple/rp_kw_errors)]
- **InCharacter: Evaluating Personality Fidelity in Role-Playing Agents through Psychological Interviews** (ACL, 2024) [[Paper](https://aclanthology.org/2024.acl-long.102.pdf)] [[Code](https://incharacter.github.io/)]
- **Regurgitative Training: The Value of Real Data in Training Large Language Models** (arXiv, 2024.07) [[Paper](https://arxiv.org/pdf/2407.12835)]
- **Evaluating the Performance of Large Language Models via Debates** (arXiv, 2024.06) [[Paper](https://arxiv.org/abs/2406.11044)]
- **Auto-Arena: Automating LLM Evaluations with Agent Peer Battles and Committee Discussions** (arXiv, 2024.05) [[Paper](https://arxiv.org/abs/2405.20267)] [[Code](https://auto-arena.github.io/)]
- **AgentClinic: A Multimodal Agent Benchmark to Evaluate AI in Simulated Clinical Environments** (arXiv, 2024.05) [[Paper](https://arxiv.org/pdf/2405.07960)] [[Code](https://agentclinic.github.io/)]
- **How Reliable is Your Simulator? Analysis on the Limitations of Current LLM-based User Simulators for Conversational Recommendation** (arXiv, 2024.03) [[Paper](https://arxiv.org/pdf/2403.16416)] [[Code](https://github.com/RUCAIBox/iEvaLM-CRS/)]
- **Humans or LLMs as the Judge? A Study on Judgement Bias** (arXiv, 2024.02) [[Paper](https://arxiv.org/pdf/2402.10669)] [[Code](https://github.com/FreedomIntelligence/Humans_LLMs_Judgement_Bias)]
- **LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games** (CoRR, 2023.09) [[Paper](https://publications.cispa.de/articles/journal_contribution/LLM-Deliberation_Evaluating_LLMs_with_Interactive_Multi-Agent_Negotiation_Games_/25233028/1/files/44571847.pdf)]
- **AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback** (NeurIPS, 2023) [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/5fc47800ee5b30b8777fdd30abcaaf3b-Paper-Conference.pdf)] [[Code](https://github.com/tatsu-lab/alpaca_farm)]
- **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** (arXiv, 2023.08) [[Paper](https://arxiv.org/pdf/2308.04026)] [[Code](https://agentsims.com)]

## 7. Cognition & Psychology

- **Grounded Cognition** (Annual Review of Psychology, 2008) [[Paper](http://barsaloulab.org/Online_Articles/2008-Barsalou-ARP-grounded_cognition.pdf)]
- **Language and Simulation in Conceptual Processing** (Symbols, Embodiment, and Meaning, 2008) [[Paper](https://barsaloulab.org/Online_Articles/2008-Barsalou_et_al-chap-language_situated_simulation.pdf)]
- **Dual Coding Theory: Retrospect and Current Status** (Canadian Journal of Psychology, 1991) [[Paper](https://psycnet.apa.org/fulltext/1992-07881-001.html)]
- **How and Why Thoughts Change: Foundations of Cognitive Psychotherapy** (Oxford University Press, 2015) [[Paper](https://books.google.com.sg/books?hl=en&lr=&id=jf0VBgAAQBAJ&oi=fnd&pg=PP1&dq=+How+and+why+thoughts+change:+Foundations+of+cognitive+psychotherapy+&ots=uTy0KNHCGI&sig=3Epi3FELiTRKtV5k8m17mjUphQo&redir_esc=y#v=onepage&q&f=false)]
- **Emotion and Social Theory: Corporeal Reflections on the (Ir)rational** (Sage, 2000) [[Paper](https://www.torrossa.com/en/resources/an/4913553)]
- **Neural Dynamics of Decision Making Under Risk: Affective Balance and Cognitive-Emotional Interactions** (Psychological Review, 1987) [[Paper](https://psycnet.apa.org/doi/10.1037/0033-295X.94.3.300)]
- **A Cognition-Based View of Decision Processes in Complex Social-Ecological Systems** (Ecology and Society, 2007.06) [[Paper](https://www.jstor.org/stable/26267857)]
- **Information, Incentives, and Proenvironmental Consumer Behavior** (Journal of Consumer Policy, 1999) [[Paper](https://link.springer.com/article/10.1023/a:1006211709570)]
- **Human Incentives** (The Greek Economy and the Crisis, 2012) [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-21175-1_9)]

## 8. Social Simulation

- **AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society** (arXiv, 2025.02) [[Paper](https://arxiv.org/abs/2502.08691)] [[Code](https://github.com/tsinghua-fib-lab/AgentSociety)]
- **OASIS: Open Agent Social Interaction Simulations with One Million Agents** (arXiv, 2024.11) [[Paper](https://arxiv.org/abs/2411.11581)] [[Code](https://github.com/camel-ai/oasis)]
- **Multi-Agents Are Social Groups: Investigating Social Influence of Multiple Agents in Human-Agent Interactions** (CSCW, 2025) [[Paper](https://dl.acm.org/doi/abs/10.1145/3757633)]
- **Unpacking a Black Box: A Conceptual Anatomy Framework for Agent-Based Social Simulation Models** (JASSS, 2023) [[Paper](http://research.sdpublishers.net/id/eprint/2686/1/4.pdf)]
- **Simulation: A Tool for System Design and Analysis** (GPH-IJSSHR, 2023) [[Paper](https://gphjournal.org/index.php/ssh/article/download/1147/818)]
- **Analysing the Combined Health, Social and Economic Impacts of the Coronavirus Pandemic Using Agent-Based Social Simulation** (Minds and Machines, 2020.06) [[Paper](https://doi.org/10.1007/s11023-020-09527-6)]
- **The Termination Risks of Simulation Science** (Erkenntnis, 2020) [[Paper](https://philpapers.org/archive/GRETTR-5.pdf)]
- **Simulating Societies: The Computer Simulation of Social Phenomena** (2018) [[Paper](https://books.google.com.sg/books?hl=en&lr=&id=cT33DwAAQBAJ&oi=fnd&pg=PP1&dq=Simulating+societies:+the+computer+simulation+of+social+phenomena+&ots=WqRTvFhVLV&sig=WQLJj9D48Lfy18znAngvOHrvD3o&redir_esc=y#v=onepage&q=Simulating%20societies%3A%20the%20computer%20simulation%20of%20social%20phenomena&f=false)]
- **Computer Simulations of Space Societies** (2018) [[Paper](https://link.springer.com/content/pdf/10.1007/978-3-319-90560-0.pdf)]
- **Can Robots Be Lawyers? Computers, Lawyers, and the Practice of Law** (Georgetown Journal of Legal Ethics, 2017) [[Paper](https://papers.ssrn.com/sol3/Delivery.cfm?abstractid=2701092)]
- **Ethics in Planning** (2017) [[Paper](https://books.google.com.sg/books?hl=en&lr=&id=npcuDwAAQBAJ&oi=fnd&pg=PT9&dq=Ethics+in+planning&ots=5qv6p7E9mm&sig=5wcKq1NV0O3iUV8qvIrkfQ50O3c&redir_esc=y#v=onepage&q=Ethics%20in%20planning&f=false)]
- **Social Self-Organization: Agent-Based Simulations and Experiments to Study Emergent Social Behavior** (2012) [[Paper](https://books.google.com.sg/books?hl=en&lr=&id=Jzm6BQAAQBAJ&oi=fnd&pg=PR3&dq=Social+self-organization:+Agent-based+simulations+and+experiments+to+study+emergent+social+behavior&ots=5w_4V7kIzu&sig=iD3BWwVoNOvTpMT-OgTRQ_PjKmE&redir_esc=y#v=onepage&q=Social%20self-organization%3A%20Agent-based%20simulations%20and%20experiments%20to%20study%20emergent%20social%20behavior&f=false)]
- **Analyzing and Modeling Real-World Phenomena with Complex Networks: A Survey of Applications** (Advances in Physics, 2011.03) [[Paper](https://arxiv.org/pdf/0711.3199)]
- **A Simulation System of Social Economic** (Computer and Information Science, 2011.07) [[Paper](https://ccl.northwestern.edu/2011/Zhao2011.pdf)]
- **A Methodology for Complex Social Simulations** (JASSS, 2010) [[Paper](https://papers.ssrn.com/sol3/Delivery.cfm?abstractid=2291156)]
- **Agent-Based Modeling: A New Approach for Theory Building in Social Psychology** (Personality and Social Psychology Review, 2007) [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=0dd27d293a4ceae047ee8d1af6529f4fa6297bf0)]
- **Simulated Experiments: Methodology for a Virtual World** (Philosophy of Science, 2003.01) [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=447b355e96611eb53548cad2218c7ada179c0d4a)]
- **Understanding Climate Policy Using Participatory Agent-Based Social Simulation** (MABS, 2000) [[Paper](https://link.springer.com/chapter/10.1007/3-540-44561-7_15)]
- **System Dynamics: Simulation for Policy Analysis from a Feedback Perspective** (Qualitative Simulation Modeling and Analysis, 1991) [[Paper](https://link.springer.com/chapter/10.1007/978-1-4613-9072-5_7)]
- **Policy Exploration through Microanalytic Simulation** (1976) [[Paper](https://books.google.com.sg/books?hl=en&lr=&id=4g44Qr51NEwC&oi=fnd&pg=PR3&dq=Policy+exploration+through+microanalytic+simulation&ots=oA3vWq59Q9&sig=ev9fI3DnllnZdNj1P6zK8YBj2ik&redir_esc=y#v=onepage&q=Policy%20exploration%20through%20microanalytic%20simulation&f=false)]

## 9. Conference

- **The Multi-hub Academic Conference: Global, Inclusive, Culturally Diverse, Creative, Sustainable** (Frontiers in Research Metrics and Analytics, 2021.07) [[Paper](https://www.frontiersin.org/journals/research-metrics-and-analytics/articles/10.3389/frma.2021.699782/full)]
- **Ten Simple Rules to Host an Inclusive Conference** (PLOS Computational Biology, 2022.07) [[Paper](https://doi.org/10.1371/journal.pcbi.1010164)]
- **Transitioning to Sustainable Academic Conferences Needs More Experimentation and Reflection** (Global Sustainability, 2023.09) [[Paper](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/4096E12F88FD6B1C3E7D247086933B60/S2059479823000157a.pdf/transitioning_to_sustainable_academic_conferences_needs_more_experimentation_and_reflection.pdf)]
- **Creative Destruction in Academia: A Time to Reimagine Practices in Alignment with Sustainability Values** (Sustainability Science, 2023.07) [[Paper](https://link.springer.com/content/pdf/10.1007/s11625-023-01357-6.pdf)]

## 10. Others

- **Can Generative AI Improve Social Science?** (PNAS, 2024.03) [[Paper](https://www.pnas.org/doi/pdf/10.1073/pnas.2314021121)]
- **Do LLMs Exhibit Human-like Response Biases? A Case Study in Survey Design** (TACL, 2024) [[Paper](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00685/124261/Do-LLMs-Exhibit-Human-like-Response-Biases-A-Case)] [[Code](https://github.com/lindiatjuatja/BiasMonkey)]
- **Employing Large Language Models in Survey Research** (NLP Journal, 2023.09) [[Paper](https://doi.org/10.1016/j.nlp.2023.100020)]
- **Sequential Modeling Enables Scalable Learning for Large Vision Models** (CVPR, 2024) [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Bai_Sequential_Modeling_Enables_Scalable_Learning_for_Large_Vision_Models_CVPR_2024_paper.pdf)] [[Code](https://github.com/ytongbai/LVM)]
- **"You Are Not the Expert Here": How Large Language Models Impact Help-Seeking in Online Communities** (CHI, 2024) [[Paper](https://arxiv.org/abs/2404.01748)]

## Acknowledgement

This repository is initially built and maintained by [Qian Wang](https://persdre.github.io/) ([persdre@gmail.com](mailto:persdre@gmail.com)).

## Citation

If you find this repository useful, please consider citing our papers:

```bibtex
@inproceedings{wang2025canllmsimulations,
  author    = {Wang, Qian and Tang, Zhenheng and He, Bingsheng},
  title     = {Can LLM Simulations Truly Reflect Humanity? A Deep Dive},
  booktitle = {ICLR Blogposts 2025},
  year      = {2025},
  url       = {https://iclr-blogposts.github.io/2025/blog/rethinking-llm-simulation/}
}
```

```bibtex
@misc{wang2025llmbasedhumansimulationsreliable,
  title         = {LLM-based Human Simulations Have Not Yet Been Reliable},
  author        = {Qian Wang and Jiaying Wu and Zichen Jiang and Zhenheng Tang and Bingqiao Luo and Nuo Chen and Wei Chen and Bingsheng He},
  year          = {2025},
  eprint        = {2501.08579},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2501.08579}
}
```
