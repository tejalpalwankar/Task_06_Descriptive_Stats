
# Task_05_Descriptive_Stats: SU Women’s Lacrosse 2025 — AI-Assisted Sports Data Analysis

## Overview

This project explores the capabilities and limitations of Large Language Models (LLMs) in descriptive sports analytics using the 2025 Syracuse University Women’s Lacrosse season dataset. The same set of advanced, scenario-based statistical questions were posed to multiple AI models (ChatGPT, Claude, Gemini). Their responses were evaluated and compared against each other as well as against ground-truth Python calculations.


## Key Questions (Examples)

- Which player showed the largest improvement in goals or assists in the second half versus the first half of the season?
- Against which opponent did Syracuse record the highest single-game goals?
- Which player had the highest ground ball to turnover ratio?
- Who contributed the largest share of team points in wins? (limitations explained)
- Who led in two-way impact combining ground balls, draw controls, and caused turnovers per game?
- If Syracuse shot 5% better, how many more goals would result?
- …and more scenario, comparison, and correlation questions.


## Comparative LLM Results

- **Direct fact queries:** All AI models performed highly accurately.
- **Computation/filter queries:** Accuracy varied, with some hallucinations or misreading of stats, especially with ratios or multi-step calculations.
- **Missing/split data:** Claude and Gemini reliably recognized data limitations; ChatGPT sometimes filled gaps by estimating or hallucinating.
- **Scenario/numeric simulations:** All models correctly handled straightforward numeric estimations based on provided summary data.

## Lessons Learned

- LLMs differ in their handling of ambiguous or incomplete data.
- More complex analytics and multi-column queries are error-prone across all LLMs; manual validation is essential.
- Clear, explicit prompt engineering dramatically improves answer quality.
- Transparent reporting of LLMs’ failures and successes is critical for trustworthy analytic workflows.

