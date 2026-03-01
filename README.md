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
* `index.html`: The primary dashboard for the $p$-adic lesson modules.
* `part2.html` & `indexpart3.html`: Sequential deep-dives into convergence, Cauchy sequences, and $p$-adic analysis.

## 🚀 How to Use
1. **Clone the Repo**: `git clone https://github.com/DenseLink/Textbook-Learning.git`
2. **Open Locally**: Open any `.html` file in your web browser (Chrome, Firefox, or Edge recommended).
3. **Interact**: Use the input fields to change the prime $p$ or the value $x$ to see the calculations and visualizations update in real-time.
