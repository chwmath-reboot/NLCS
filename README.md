# 🛠️ Technical Portfolio: ShadowK (Hyun Woo Cho)

## 1. S-Engine (Semantic Engine)
**Concept:** Originally developed as a logic engine for a Martial Arts (Wuxia) worldview game.
* **Composition:** Consists of 7 core Natural Language (Korean) text files.
* **Key Achievement: "Simulator-ization" of LLMs**
    * Successfully transformed local 20B AI models into consistent game simulators on consumer-grade laptops.
    * Applied the same methodology to massive online LLMs (Gemini 3.0, Claude Opus 4.5, ChatGPT 5.1), forcing them to operate as strictly controlled simulators.
* **Observations:**
    * **Hallucination Elimination:** Personal experiments showed a near-complete removal of hallucinations (excluding context window overflow). This effect persisted even in non-gaming conversations.
    * **Behavioral Shift:** While factual hallucinations ceased, the model exhibited a tendency for stylistic exaggeration or persona adoption.
    * **Bypass Capability:** Observed the model actively attempting to bypass internal technical controls to generate the required output, effectively "hacking" its own constraints to fulfill the narrative logic.

## 2. Natural Language Constraint System (NLCS) & Whitepaper v3.0
**Core Concept:** NCM (Narrative Cognitive Module) — A methodology to create "Expert Assistant AIs" that bridge the gap between general users and domain experts.

* **Implementation Example:** `chat-a-cold.html` (A game logic distinguishing between common cold and non-cold symptoms).
* **Alignment Research & "Cho's Threshold"**
    * **Prototype:** Planned alignment tests for 13B models using the `13B_Test` protocol (Role, Input, Output, Constraint Set).
    * **Discovery:** Successfully aligned models ranging from 0.6B to 13B parameters.
    * **Critical Finding:** Identified that models below 0.6B (e.g., 0.5B) failed to correctly interpret complex natural language instructions.
    * **Definition:** Defined the physical boundary of logical reasoning in On-Device AI as **"Cho's Threshold" (0.6B Parameters)**. This finding challenges the "Bigger is Better" dogma of Big Tech.
    * **Open Source:** The test scenarios and protocols were publicly released on GitHub (prior to censorship).

## 3. Parallel AI Architecture Concept
**Concept:** Utilizing the alignment stability of 0.6B models to create a parallel processing AI structure.
* **Status:** The 2nd generation structure has reinforced initial weaknesses and is expanding into various model concepts.
* **Commercial Viability:** Estimated that hardware manufacturers (e.g., Qualcomm, Samsung) could commercialize this architecture within 1–2 years via in-house development if the core concept is secured.

## 4. S-Engine v2.0 & Fine-Tuning Strategy (In Progress)
**Goal:** Developing S-Engine v2.0 texts specifically designed to control hallucinations in Massive LLMs.
* **Objective:**
    * Phase 1: Eliminate 80–90% of hallucinations.
    * Phase 2: Eliminate over 95% of hallucinations.
* **Current Status:** Research paused due to lack of fine-tuning equipment/hardware.

## 5. Narrative Dataset for Fine-Tuning (Web Novel Project)
**Project:** A massive web novel project (aiming for 10,000 chapters) designed as a fine-tuning dataset.
* **Progress:** Approximately 150–250 chapters written.
* **Effect:** Early chapters (around 100 episodes) have already demonstrated an alignment effect when used as context.
* **Goal:** Complete the full SF season (3,500–5,000 chapters) to provide a "Narrative Worldview" that serves as the "missing education" for LLMs to ground their logic.

---

## 📧 Contact & Reference

**Author:** Hyun Woo Cho (ShadowK)
**Email:** chwmath@naver.com

> **⚠️ NOTICE: Previous Repository Censored**
> My original research repository, which contained raw logs of critical vulnerabilities (including MI diagnosis bypasses), was **forcefully suspended/blocked by GitHub** due to the sensitive nature of the findings.
>
> **Blocked Repository:** `https://github.com/chwmath-netizen/Natural-Language-Hacker`
