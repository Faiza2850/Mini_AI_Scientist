# Mini-AI Scientist: Autonomous Discovery of Quantum Optical Circuits

A JAX-based closed-loop system that autonomously discovers photonic circuit configurations matching target quantum interference patterns — inspired by AI-driven scientific discovery research.

> **Motivation:** Built to demonstrate alignment with Prof. Mario Krenn's Artificial Scientist Lab research directions.

---

## 🎥 Demo

**Manual control — live interference pattern as sliders move:**

https://github.com/user-attachments/assets/d0fa11b5-a9c2-496d-b4e4-637317c46692

**Autonomous discovery — AI searching for a user-defined target in real time:**

https://github.com/user-attachments/assets/a037f78d-b60b-4f08-a98f-de83a29df46f

---

## 🔬 What it does

1. **Differentiable Simulator** — A JAX-based simulator of a Mach-Zehnder interferometer (beam-splitters + phase shifter), fully differentiable end-to-end.
2. **Closed-Loop Discovery** — Combines evolutionary exploration (multiple random initializations) with gradient-based optimization (Adam via `optax`) to autonomously discover circuit parameters that reproduce an arbitrary target interference pattern.
3. **Interpretability Layer** — Parameter-sensitivity and ablation analysis to identify which circuit components are essential to a discovered solution.
4. **Interactive Interface** — `ipywidgets`-based sliders and a "Run AI Discovery" button let you explore the search process live, directly in the notebook.

## 🧠 Why this project

This is a small-scale, self-contained version of the kind of AI-driven experiment discovery pursued by the Artificial Scientist Lab — using differentiable physics simulation and optimization to let an AI system search for novel experimental configurations, paired with tools to interpret *why* a discovered solution works.

## 🛠️ Tech Stack

`JAX` · `optax` · `ipywidgets` · `matplotlib` · `numpy`

## 🚀 Run it yourself

The notebook is fully self-contained and runs in Google Colab with no setup:

1. Open `Mini_AI_Scientist_Interactive.ipynb` in Colab
2. Run all cells top to bottom
3. Scroll to the interactive interface at the end and play with the sliders

## 📄 Notebook

See [`Mini_AI_Scientist.ipynb`](./Mini_AI_Scientist.ipynb) for the full implementation.

---

*Independent project by Faiza Fatima, 2026.*

 
