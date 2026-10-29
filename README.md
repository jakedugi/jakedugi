# Hi, I'm Jacob
 
ML engineer at Stats Perform. I build production LLM agents and the evaluation systems that decide what ships.
 
---
 
### Areas of Focus
 
- LLM agents and structured retrieval (tool use, GraphQL, entity resolution)
- Evaluation: benchmarks, deterministic checks plus LLM judges, regression gates
- Production LLM services: multi-provider routing, guardrails, observability
- Training and evaluation data design, with expert review in the loop
---
 
### Highlighted Work
 
**At work (private code)**
 
- **Evaluation platform for a pre-release LLM agent over sports data**
  - Evaluations on 54 service PRs informed model and provider decisions and caught regressions before release
  - Scoring stack of deterministic fact and entity checks plus an LLM judge; structured-output failures cut from 8.0% to 0 of 1,744
- **Structured GraphQL retrieval path for the agent**
  - Controlled A/B test: run errors −83%, input tokens −46%, median latency −30%
- **LLM service behind Opta Arena match summaries**
  - Multi-provider routing with fallbacks, circuit breakers and cost caps; 9 months in production at a 0.18% 5xx rate
**Public work**
 
- **Legal risk in corporate speech** ([modeling](https://github.com/jakedugi/corp-speech-modeling-repo) · [data pipeline](https://github.com/jakedugi/corp-speech-data-repo) · [dataset](https://github.com/jakedugi/corp_speech_risk_dataset)) · MSc dissertation (Edinburgh): a leakage audit falsified the quote-level hypothesis and led to a calibrated case-level legal-risk model; open dataset of 24K quotes across 125 federal cases, built from CourtListener
 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16934610.svg)](https://doi.org/10.5281/zenodo.16934610)
- Earlier research: stroke-care access mapping (first-author abstract, ISC 2024) · 3D VAE for neuroimaging synthesis
  [![DOI](https://img.shields.io/badge/DOI-10.1161%2Fstr.55.suppl__1.TMP41-blue)](https://doi.org/10.1161/str.55.suppl_1.TMP41)
---
 
### Connect with Me
[LinkedIn](https://www.linkedin.com/in/jakedugan) · [Email](mailto:jake@jakedugan.com) · [Website](https://jakedugan.com)
 
---
 
<details>
<summary>Additional Projects</summary>
<br>
Lightweight demos, class presentations, and collaborations:
 
- [`simulation_environments_guest_lecture`](https://github.com/jakedugi/simulation_environments_guest_lecture) – Guest lecture repo showing RL environments (DQN & SAC)
- [`AugmentedRecipeRecommendations`](https://github.com/sachinmloecher/AugmentedRecipeRecommendations) – Collaborator on extending RecipeRec, a heterogeneous graph neural network recommender, with tag nodes and nutrition features; beat the original and all baselines (HitRate@10 +4.9%, NDCG@10 +4.75%)
- [`Oxford-IIIT Pet segmentation`](https://github.com/SamLB9/Semantic-Segmentation-on-the-Oxford-IIIT-Pet-Dataset) – Collaborator on a benchmark of four segmentation models (UNet, autoencoder, CLIP-based, prompt-guided)
</details>
