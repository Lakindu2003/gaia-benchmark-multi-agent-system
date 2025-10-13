# **A Multi-Agent System for the GAIA Benchmark**
*by Jayawardana Wickramasinghe Pathiranage Lakindu Ransika*
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16hp8cv7jyd3tFZI05sPb_D_7gKPa7uNM?usp=sharing)

#### 1.1. Background
The recent advancement of Large Language Models (LLMs) has enabled the development of autonomous agents capable of solving various tasks. However, base LLM systems often struggle with multi-step reasoning problems that require real-time information. With the development of tool-use single-agent systems, the capabilities of LLMs have increased. Despite these advancements, they often struggle with long-horizon tasks that require multi-step reasoning. This has led to a growing interest in multi-agent systems, where many tool-use agents collaborate with each other.
This project is an implementation of the optional open problem in COMP3361 Natural Language Processing course assignment 3<a name="cite_ref-1"></a>[<sup>[1]</sup>](#cite_note-1). Provided code templates and helper functions were used.
#### 1.2. Problem Statement
However, for smaller locally runnable models such as Qwen-2.5-7b-Instruct that have undergone 4-bit quantization, their performance remains limited. This creates a need for more sophisticated LLM systems to circumvent these limitations. The central problem this project addresses is to determine whether these more sophisticated multi-agent systems increase the LLM's performance. To investigate this, this project evaluated the performance of a multi-agent system with tool calls on the GAIA benchmark, which assesses real-time information retrieval, multi-step reasoning, and tool-use.
#### 1.3. Objectives
To investigate the efficacy of the proposed multi-agent approach, this project accomplished the following objectives:
 1. Establish a baseline using the base LLM and the single-agent system on the GAIA benchmark.
 2. Design and implement a custom multi-agent architecture composed of specialized agents for planning, reasoning, information extraction, synthesis, and final answer validation.
 3. Empirically benchmark and compare the multi-agent system's performance to the baselines.
#### 1.4. Outline
This report is organized into five main sections. Section 2 details the methodology, highlighting the project setup, single-agent system failure point analysis, system architecture design, and implementation. Section 3 presents a comparison between the different versions of the multi-agent system, the single-agent system, and the base LLM. Section 4 provides a concluding summary of this project while highlighting the key lessons. Finally, section 5 outlines potential future work.

<br>

---

<br>

<a name="cite_note-1"></a><sup>[1]</sup> The assignment materials, including the notebook and PDF, can be found at the course GitHub repository: [https://github.com/ranpox/comp3361-spring2025/tree/main/assignments/A3](https://github.com/ranpox/comp3361-spring2025/tree/main/assignments/A3)
