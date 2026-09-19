# Awesome-ML-Experiment-Tracking

## Top ML Experiment Tracking Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Experiment Logging, Metric Visualization, Hyperparameter Tracking, Run Comparison & Reproducibility*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **ML Experiment Tracking**. These tools log parameters, metrics, artifacts, and code versions so teams can compare runs, reproduce results, and collaborate on model development.



**Examples** include Weights & Biases, MLflow, Comet ML, Neptune.ai, Aim, ClearML, DVC Studio, Sacred, Guild AI, and Polyaxon (the category leaders).



**Open-source emphasis**: Experiment tracking has an especially strong open-source ecosystem. **MLflow**, **Aim**, **ClearML**, **Sacred**, **Guild AI**, **Polyaxon**, and **DVC** all provide capable self-hosted solutions. Commercial platforms excel at polished UIs, real-time collaboration, and managed infrastructure. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Weights & Biases](https://wandb.ai/)**  

  Leading experiment tracking and collaboration platform with excellent visualizations, hyperparameter sweeps, reports, and growing LLM support via Weave.



- **[MLflow (managed offerings)](https://mlflow.org/)**  

  Open-source experiment tracking and model registry widely available as managed services (e.g., Databricks) in addition to self-hosted deployments.



- **[Comet ML](https://www.comet.com/)**  

  Experiment tracking and MLOps platform offering run comparison, model registry, collaboration features, and production monitoring.



- **[Neptune.ai](https://neptune.ai/)**  

  Metadata-centric experiment tracker known for flexible querying, clean UI, and strong organization of large numbers of runs and artifacts.



- **[Aim (hosted options)](https://aimstack.io/)**  

  Open-source experiment tracker with optional hosted offerings; focused on a fast, beautiful UI for exploring runs.



- **[ClearML Hosted](https://clear.ml/)**  

  Managed version of the ClearML platform covering experiment tracking, orchestration, and MLOps workflows.



- **[DVC Studio](https://dvc.org/)**  

  Hosted collaboration and visualization layer for DVC-based data and experiment versioning workflows.



- **[Sacred + hosted dashboards](https://github.com/IDSIA/sacred)**  

  Lightweight experiment organization framework often paired with hosted or self-hosted observers and UIs (e.g., Omniboard).



- **[Guild AI (hosted/enterprise options)](https://guild.ai/)**  

  Experiment tracking tool that works with existing scripts; commercial support and hosting options available.



- **[Polyaxon Cloud / Enterprise](https://polyaxon.com/)**  

  Managed and enterprise offerings of the Polyaxon platform for experiment tracking, orchestration, and ML lifecycle management.



## Open-Source GitHub Projects

- **[MLflow](https://github.com/mlflow/mlflow)**  

  The most widely used open-source platform for logging experiments, tracking metrics/parameters/artifacts, and managing a model registry. Fully self-hostable.



- **[Aim](https://github.com/aimhubio/aim)**  

  Open-source, self-hosted experiment tracking tool with a fast web UI optimized for exploring and comparing large numbers of runs.



- **[ClearML](https://github.com/allegroai/clearml)**  

  Full open-source MLOps suite with powerful experiment tracking, automatic logging, orchestration, and remote execution capabilities.



- **[Sacred](https://github.com/IDSIA/sacred)**  

  Lightweight Python framework for configuring, organizing, logging, and reproducing experiments; pairs with observers and dashboards.



- **[Guild AI](https://github.com/guildai/guildai)**  

  Open-source experiment tracking and run management that requires minimal code changes and works with existing training scripts.



- **[Polyaxon](https://github.com/polyaxon/polyaxon)**  

  Open-source platform for managing deep-learning and ML experiments, tracking, scheduling, and hyperparameter optimization.



- **[DVC](https://github.com/iterative/dvc)**  

  Data and model version control system with experiment tracking features; integrates tightly with Git workflows.



- **[TensorBoard](https://github.com/tensorflow/tensorboard)**  

  Open-source visualization toolkit originally for TensorFlow; still widely used for metric logging and run comparison across frameworks.



- **[Katib (Kubeflow)](https://github.com/kubeflow/katib)**  

  Kubernetes-native open-source hyperparameter tuning and experiment tracking component within the Kubeflow ecosystem.



- **[Hydra + joblib / custom loggers](https://github.com/facebookresearch/hydra)**  

  Configuration and experiment management tools often combined with simple open logging solutions for research workflows.



### Additional Strong Open-Source Options

- Starting with **MLflow** for maximum ecosystem compatibility and a built-in model registry.

- Choosing **Aim** when a fast, modern UI for run exploration is the top priority.

- Using **ClearML** if you want tracking plus remote execution and orchestration in one open stack.

- Adopting **Sacred** or **Guild AI** for lightweight, low-intrusion tracking of existing scripts.

- Pairing **DVC** with Git for data + experiment versioning in research-oriented teams.

- Accepting that real-time collaboration, advanced report sharing, managed scaling, and enterprise SSO still favor commercial platforms (Weights & Biases, Neptune, Comet, etc.).

- Focusing open-source efforts on reproducibility, local/offline tracking, and full ownership of experiment data.



**Frameworks for building custom systems**: Instrument training code with MLflow, Aim, or ClearML clients → log parameters, metrics, and artifacts → compare runs in the UI → register promising models → optionally sync to a commercial platform for team visibility. Suitable for research labs, startups, and enterprises that need data residency or cost control. Many teams run open-source trackers in production while using hosted tools for broader collaboration.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Experiment tracking systems store model parameters, metrics, and sometimes sensitive datasets or proprietary results. Self-hosted deployments require appropriate access controls, encryption, and retention policies. This list is not security or compliance advice.



---

**Made for ML engineers, researchers, and data scientists who need reliable, reproducible experiment tracking.**

Let's keep experiment history transparent, comparable, and as open as practical.
