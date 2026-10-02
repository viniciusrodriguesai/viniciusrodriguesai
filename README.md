<div align="center">

# Hi, I'm Vinicius 👋

### Data Science & AI student · Python developer · UFPB, Brazil

Building applications, exploring machine learning, and making data useful.

**Seeking international internships in AI/ML, Data & Software Engineering**

[Explore my projects](#-selected-projects) · [Open-source work](#-open-source-work) · [Get in touch](#-lets-connect)

</div>

---

## About me

I'm studying **Data Science and Artificial Intelligence at the Federal University of Paraíba (UFPB)**. My projects span resume/job matching, full-stack applications, classification experiments, and economic data dashboards.

I care about clear APIs, useful tests, and understanding what an experiment actually demonstrates. Each featured repository documents its implementation, setup, and current limitations.

## 🧰 Technologies used in my projects

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,js,mysql,git,githubactions&perline=8" alt="Python, FastAPI, React, TypeScript, JavaScript, MySQL, Git and GitHub Actions" />
</p>

| Area | Tools and focus |
| --- | --- |
| AI & data | Python, pandas, NumPy, scikit-learn · classification and evaluation |
| Applications | FastAPI, Streamlit, React, TypeScript · APIs and interfaces |
| Persistence & engineering | SQL, SQLAlchemy, MySQL, pytest, Git, GitHub Actions |
| Foundations | C/C++ · algorithms and data structures |

## 🚀 Selected projects

**Choose a project below, then expand its technical notes.**

### Resume Match AI
**Applied AI · Python · Streamlit · FastAPI**

Match resumes to job requirements with requirement-level evidence and optional retrieval/reranking.

[Explore repository →](https://github.com/viniciusrodriguesai/resume-agent-system) · [Recorded lexical demo](https://github.com/viniciusrodriguesai/resume-agent-system/blob/main/docs/DEMO.md)

<details>
<summary><strong>Explore the engineering and evaluation</strong></summary>

- Inspect evidence-based matching and the default lexical demo.
- Explore optional retrieval/reranking components and the API/UI.
- Review automated tests and the documented evaluation boundaries.
- Read the [36-case optional-model ablation](https://github.com/viniciusrodriguesai/resume-agent-system/blob/main/docs/MODEL_ABLATION.md): lexical, E5-small and reranking produced identical labels; independent annotation remains pending.
- Review the [external SkillSpan component benchmark](https://github.com/viniciusrodriguesai/resume-agent-system/blob/main/docs/SKILLSPAN_RESULTS.md): 3,569 human-annotated sentences / 65 posting clusters; the fixed catalog has limited coverage (token precision 0.7742, recall 0.0420). Full-pipeline independent labels are still pending.
- Treat matching outputs as assistance for reviewing a resume, rather than a validated hiring decision.

</details>

### Creator Growth Feedback Loop
**Full-stack software · FastAPI · React · SQLAlchemy**

An application for creator feedback, analytics, and external API workflows.

[Explore repository →](https://github.com/viniciusrodriguesai/creator-growth-feedback-loop) · [Try the live demo](https://creator-growth-feedback-loop.onrender.com/) · [Product walkthrough](https://www.youtube.com/watch?v=r_Dtv8fwnhw)

<details>
<summary><strong>Explore the application architecture</strong></summary>

- Follow the flow from React interfaces to FastAPI endpoints and persistence.
- Inspect external API integration and backend/frontend tests.
- Read the setup instructions and deployment/demo limitations.

</details>

### Credit Risk Classification
**Machine learning · scikit-learn · Neural networks**

An academic Home Credit classification study comparing a neural network and a regularized decision tree, developed with Gustavo Pereira.

[Explore repository →](https://github.com/viniciusrodriguesai/credit-risk-classification) · [Results provenance](https://github.com/viniciusrodriguesai/credit-risk-classification/blob/main/docs/RESULTS_PROVENANCE.md)

<details>
<summary><strong>Explore the experiments and their limitations</strong></summary>

- Reproduce a [preregistered UCI replication](https://github.com/viniciusrodriguesai/credit-risk-classification/blob/main/docs/UCI_RESULTS.md) on a new cohort: models and thresholds frozen before one held-out test pass, paired uncertainty, and poor-calibration analysis. This is a new-model replication, not transfer validation of the Home Credit model.
- Examine class imbalance, decision thresholds, and model comparisons.
- Consult the provenance document before interpreting historical results.
- Historical reports and saved notebook outputs come from different experiment configurations.
- A [new fixed-protocol MLP run](https://github.com/viniciusrodriguesai/credit-risk-classification/blob/main/docs/NEURAL_RESULTS.md) records AUC 0.7443, AP 0.2129 and F1 0.2887; calibration and historical test-exposure limits remain explicit.
- A separate, reproducible raw-feature tree run records ROC AUC 0.7227, average precision 0.1972, and F1 0.2694 against a prior baseline.
- Read the [real-data run and reproduction guide](https://github.com/viniciusrodriguesai/credit-risk-classification/blob/main/docs/HOMECREDIT_RESULTS.md); historical test exposure and independent-validation limits are explicit.

</details>

### Worldbank Economic Dashboard
**Data workflows · FastAPI · Time series**

An economic data dashboard with forecasting baselines and automated API/dashboard tests.

[Explore repository →](https://github.com/viniciusrodriguesai/worldbank-economic-dashboard) · [Real-data backtest](https://github.com/viniciusrodriguesai/worldbank-economic-dashboard/blob/main/docs/BACKTEST_RESULTS.md)

<details>
<summary><strong>Explore the data and forecasting workflow</strong></summary>

- Inspect economic data processing and time-series forecasting baselines.
- Reproduce [six GDP-growth/inflation backtests](https://github.com/viniciusrodriguesai/worldbank-economic-dashboard/blob/main/docs/EXPANDED_BACKTEST_RESULTS.md) across Brazil, the US and Germany: eight origins per series, every prediction and baseline, and revised-vintage limitations.
- Review backend/frontend tests and continuous integration.
- Consult the documented assumptions before interpreting forecasts.

</details>

## 🤝 Open-source work

Contributions submitted to projects outside my own repositories:

| Project | Contribution | Review |
| --- | --- | --- |
| CS2 RouteFilter | Dependency lockfile correction | [PR #4](https://github.com/Daotie/CS2-RouteFilter/pull/4) |
| CS2 RouteFilter | Asset filtering, sorting, and interface improvements | [PR #5](https://github.com/Daotie/CS2-RouteFilter/pull/5) |
| TransitTimetables | Multiple-terminal support | [PR #19](https://github.com/AmicusDeus/TransitTimetables/pull/19) |

These pull requests were open during the portfolio audit. Their review links show the current status.

<details>
<summary><strong>More learning projects</strong></summary>

My repositories also include C/C++ exercises, data structures, exploratory data analysis, and historical course projects.

[Browse all repositories →](https://github.com/viniciusrodriguesai?tab=repositories)

</details>

## 📬 Let's connect

I'm interested in internship opportunities where I can contribute to Python applications, data workflows, and machine learning projects while learning from an engineering team.

**[LinkedIn](https://www.linkedin.com/in/viniciusrodriguesai/) · [Kaggle](https://www.kaggle.com/viniciustrajano) · [Email](mailto:viniciusmangueira04@gmail.com)**

<div align="center">

*Thanks for visiting — the repositories above are the best place to explore my work.*

</div>
