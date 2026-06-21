# Textbook-Learning: Interactive Math Aides

Welcome to **Textbook-Learning**. This repository contains a collection of interactive HTML lesson aides designed to visualize and experiment with complex mathematical concepts. 

## 📖 Current Source Material
The current modules are based on the following text:
* **Title**: $p$-adic Numbers: An Introduction
* **Authors**: Fernando Q. Gouvêa
* **Version**: Third Edition

## 🧮 Featured Topic: $p$-adic Numbers ($\mathbb{Q}_p$)
These interactive tools are designed to help students and enthusiasts explore the unique properties of $p$-adic numbers as outlined in Gouvêa's text:

* **$p$-adic Valuations**: Interactive calculators to find $v_p(x)$, the exponent of the highest power of $p$ dividing $x$.
* **The $p$-adic Metric**: Visualizing the non-Archimedean absolute value $|x|_p = p^{-v_p(x)}$ and how it changes our definition of "close".
* **$p$-adic Expansions**: Tools to convert rational numbers into their unique series representation $\sum a_i p^i$.
* **Hensel's Lemma**: A step-by-step visualizer for lifting solutions from $\mathbb{Z}/p\mathbb{Z}$ to $\mathbb{Z}_p$.
* **Ultrametric Triangle Inequality**: Demonstrating why $|x+y|_p \leq \max(|x|_p, |y|_p)$.

## 📂 Repository Structure
All modules live under `P-Adic-Numbers/`:
* `index_chapter_2.html`: **Chapter 2 — Foundations.** Full interactive platform covering §2.1 Absolute Values, §2.2 Basic Properties, §2.3 Topology, and §2.4 Algebra (valuation ring, residue field), with practice problems, section quizzes, and a comprehensive exam.
* `index_chapter_3.html`: **Chapter 3 — The $p$-adic Numbers.** Covers §3.1 Absolute Values on $\mathbb{Q}$ (equivalence, Ostrowski's theorem, the product formula) and §3.2 Completions (Cauchy sequences, the ring $\mathcal{C}$, null ideal $\mathcal{N}$, and the construction $\mathbb{Q}_p = \mathcal{C}/\mathcal{N}$), with the same full treatment.
* `index_chapter_4.html`: **Chapter 4 — Exploring $\mathbb{Q}_p$.** Covers §4.1 What We Know, §4.2 $p$-adic Integers $\mathbb{Z}_p$, §4.3 Elements of $\mathbb{Q}_p$ (p-adic expansions), §4.5 Hensel's Lemma (root lifting). Interactive visualizations for p-adic valuations, approximation in $\mathbb{Z}_p$, p-adic expansions, and Hensel lifting for square roots.
* `index_chapter_5.html`: **Chapter 5 — Elementary Analysis in $\mathbb{Q}_p$.** Covers §5.1 Sequences and Series (ultrametric convergence test), §5.4 Power Series (radius of convergence, Strassman's theorem), §5.7 Exponential and Logarithm (restricted domains), §5.8 Structure of $\mathbb{Z}_p^\times$ (roots of unity, principal units). Interactive tools for series convergence, radius computation, exp/log, and roots of unity.
* `(first draft)/`: The earlier prototype files (`original_index.html`, `part2.html`, `indexpart3.html`) kept for reference.

All chapter files are **cross-linked**: each has a chapter switcher dropdown in the top bar and a "jump to another chapter" link in the sidebar. The links work as long as all files sit in the same folder when downloaded.

## 🚀 How to Use
1. **Clone the Repo**: `git clone https://github.com/DenseLink/Textbook-Learning.git`
2. **Open Locally**: Open any chapter file (e.g., `P-Adic-Numbers/index_chapter_2.html`) in your web browser (Chrome, Firefox, or Edge recommended). Keep all chapter files in the same folder so cross-chapter navigation works.
3. **Interact**: Use the input fields to change the prime $p$ or the value $x$ to see the calculations and visualizations update in real-time. Each chapter is fully self-contained (no internet or dependencies required).
