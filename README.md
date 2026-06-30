<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00695C,100:40E0D0&height=180&section=header&text=Valerie%20Jerono&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=ML%20Engineer%20%7C%20Actuarial%20Analyst%20%7C%20AI%20Researcher%20in%20InsurTech,%20Risk%20%26%20Behaviour&descAlignY=58&descSize=16" width="100%"/>

<a href="https://www.linkedin.com/in/valerie-jerono"><img src="https://img.shields.io/badge/LinkedIn-Connect-00695C?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:kipropvalerie@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hello-00695C?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://medium.com/@Vondetta"><img src="https://img.shields.io/badge/Medium-Read%20My%20Work-00695C?style=for-the-badge&logo=medium&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=VAL-Jerono&style=for-the-badge&color=00695C&label=Profile+Views" />

</div>

<br>

## Kwa Ufupi — In Short

I started in actuarial science, where I learned to be exact: a mortality table does not forgive a careless assumption, and a premium that is wrong by two percent is a promise the company cannot keep. That precision never left me. What changed is where I point it.

Today I build machine learning systems for insurance, risk, and human behaviour, work that lives at iLabAfrica, Strathmore University as a Research Scholar, and at Vondetta, the AI decision systems firm I founded. I write about what I build, because a model nobody understands is a model nobody trusts, and trust is the actual product in risk and insurance work.

If you are here for a list of frameworks, you will find one. But the frameworks are not the point. The point is what they were built to decide.

<br>

<div align="center">
<table>
<tr>
<td align="center" width="33%">

### Risk
Pricing, claims, fraud, and the quiet mathematics of "what could go wrong"

</td>
<td align="center" width="33%">

### Behaviour
Why people lapse, churn, default, or stay, and what the data says before they tell you

</td>
<td align="center" width="33%">

### Systems
Models that ship, with APIs, dashboards, and people who actually use them

</td>
</tr>
</table>
</div>

<br>

## How I Work

A pipeline is not magic. It is a sequence of honest decisions, and I would rather show you mine than perform mystique.

```mermaid
graph LR
    A[Understand the Decision] --> B[Respect the Data]
    B --> C[Model with Intent]
    C --> D[Explain the Why]
    D --> E[Ship It]
    E --> F[Watch What Happens]

    style A fill:#00695C,stroke:#003D33,stroke-width:2px,color:#fff
    style B fill:#00897B,stroke:#003D33,stroke-width:2px,color:#fff
    style C fill:#26A69A,stroke:#003D33,stroke-width:2px,color:#fff
    style D fill:#4DB6AC,stroke:#003D33,stroke-width:2px,color:#000
    style E fill:#80CBC4,stroke:#003D33,stroke-width:2px,color:#000
    style F fill:#B2DFDB,stroke:#003D33,stroke-width:2px,color:#000
```

I do not start with a model. I start with the question of who is going to act on the answer, an underwriter, a policymaker, a logistics manager, and what they need to trust before they will. Everything downstream, the feature engineering, the model family, the explainability layer, gets shaped by that one constraint.

<br>

## Selected Work

Each of these began as a real question, not a dataset I found interesting. I have grouped them by the kind of decision they were built to support.

<br>

### Insurance & Risk

**Karbima Care** — *Kenya's AI-driven auto insurance brokerage*
Four production ML models (AUC up to 0.88) sitting on top of a 105,000-document FAISS retrieval system, with automated OCR reading logbooks, licenses, and IDs at intake. The result: quote time dropped 83%, and the projected annual ROI sits at KES 4.4M. This is the project that taught me that a RAG system is only as good as the latency a human will tolerate before giving up; under 50ms became the line I would not cross.
`Python` `FAISS` `Sentence-Transformers` `FastAPI` `Ollama` `Tesseract OCR`

**UnderwriteGPT** — *Explainable underwriting for African insurers*
58,592 real policy records, reduced to 41,012 structured narratives an underwriter could actually read and challenge. The risk scoring framework achieves 8.15% score separation between claim and no-claim cases, and the system reaches 89% alignment with expert underwriter decisions. Live at `underwritegpt.streamlit.app`.
`Sentence-BERT` `FAISS` `Scikit-learn` `Streamlit` `Explainable AI`

**Intelligent Insurance Customer Analytics Platform** — *Five layers, one portfolio*
Built across a €25.8M, 53,502-policy portfolio: churn (89.26% ROC-AUC), claims frequency (92.25% ROC-AUC), a leakage-corrected severity model, and a ten-year customer lifetime value engine. The finding that mattered most was not technical, it was that agent-channel customers carried a €483 CLV advantage over broker-channel customers, a gap nobody had quantified before. Pilot deployment across 20 agents cut churn by 12.3%.
`XGBoost` `TensorFlow` `MLflow` `Docker Compose` `Prometheus` `Grafana`

<br>

### Quantitative Finance

**WorldQuant BRAIN Alpha Research** — *What actually drives a Sharpe ratio*
I built and tested multiple systematic equity alpha strategies, eventually landing on an architecture I call X2: a size-neutralized blend of earnings yield, return on equity, and short-term reversion, reaching Sharpe ratios between 2.15 and 2.27. The more interesting result was negative: after controlled testing, I permanently flagged a popular volatility-grouping variable as unreliable, because a single anomalous date was quietly corrupting every bucket downstream. Knowing what not to trust turned out to matter as much as the strategy itself.
`Systematic Equity Strategy` `Factor Modeling` `Risk-Adjusted Returns`

**GARCH Volatility Forecasting** — *Bitcoin does not behave like equities*
A full econometric pipeline across 1,082 daily returns of the ProShares Bitcoin Strategy ETF. GARCH(1,1) won on AIC/BIC, with a persistence parameter of 0.9044 and a shock half-life of 6.9 trading days. The headline finding: Bitcoin shows no leverage effect, the asymmetric volatility response that defines equity markets simply is not there, which has real implications for anyone pricing crypto derivatives with equity-market intuition.
`Python` `arch` `statsmodels` `Time Series Econometrics`

<br>

### Public Policy & Human Systems

**Housing Financial Vulnerability Score** — *My MSc dissertation, built to be used, not shelved*
A composite vulnerability index across five dimensions, financial stress, tenure insecurity, physical hazard, dwelling quality, and utility deprivation, built from Kenya's 2023/24 Housing Survey covering 21,347 households across all 47 counties. The construction model reaches a PR-AUC of 0.9315; the field-deployable proxy model holds up at 0.65 to 0.78 AUC on unseen data, which matters more, because a model nobody can run in the field is a model nobody will use. SHAP analysis surfaced land ownership as the single strongest predictor of vulnerability, ahead of income. Deployed as an interactive choropleth dashboard with a bilingual, Groq-powered policy advisor.
`XGBoost` `SHAP` `Survey-Weighted Modeling` `GeoPandas` `Spatial CV`

**HARAKA MED** — *Clinical triage for the community health worker, not the hospital*
Built at the Harvard HSIL Hackathon at CMU Africa in Kigali, where it earned an Honorable Mention. A trilingual AI triage assistant, English, Kiswahili, Kinyarwanda, that follows WHO IMCI protocols and runs over USSD, meaning it works on a basic feature phone with no data connection. The hardest design constraint was not the model, it was accepting that the best AI system in the world is useless to a community health worker without signal.
`Next.js` `Groq` `Africa's Talking USSD` `WHO IMCI Protocols`

**Miraa Transportation Optimization** — *Logistics for a crop that spoils by the hour*
Applied Vogel's Approximation Method and linear programming to route miraa from Meru County to four markets, with a four-component cost model that weighs distance against road quality, vehicle type, and a perishability penalty that increases by the hour. Validated against SciPy's LP solver, landing on an optimal total cost of KES 101,700. Prototyped as MiraaMover, a React app matching producers to transporters in real time.
`Python` `SciPy` `Linear Programming` `React`

<br>

## Technical Toolkit

<div align="center">

**Machine Learning & Statistics**
![Python](https://img.shields.io/badge/Python-00695C?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-00695C?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-00695C?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-00695C?style=flat-square&logo=tensorflow&logoColor=white)
![R](https://img.shields.io/badge/R-00695C?style=flat-square&logo=r&logoColor=white)

**NLP, RAG & AI Systems**
![FAISS](https://img.shields.io/badge/FAISS-00695C?style=flat-square&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-00695C?style=flat-square&logo=spacy&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain%20concepts-00695C?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-00695C?style=flat-square&logo=fastapi&logoColor=white)

**Quant, Risk & Time Series**
![GARCH](https://img.shields.io/badge/GARCH%20Modeling-00695C?style=flat-square&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-00695C?style=flat-square&logo=postgresql&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-00695C?style=flat-square&logoColor=white)

**Deployment & Visualization**
![Docker](https://img.shields.io/badge/Docker-00695C?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-00695C?style=flat-square&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-00695C?style=flat-square&logo=powerbi&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-00695C?style=flat-square&logo=plotly&logoColor=white)

</div>

<br>

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VAL-Jerono&show_icons=true&hide_border=true&bg_color=00000000&title_color=00695C&icon_color=00897B&text_color=333333&border_radius=10&count_private=true" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=VAL-Jerono&hide_border=true&background=00000000&stroke=00695C&ring=00897B&fire=00695C&currStreakLabel=00695C&border_radius=10" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VAL-Jerono&hide_border=true&bg_color=00000000&title_color=00695C&text_color=333333&layout=compact&border_radius=10&langs_count=8" width="49%" />

</div>

<br>

## Where This Is Going

I am candid about the shape of my career right now: early, fast-moving, and built on project depth rather than a decade of enterprise titles. I think that is a fair trade for someone who has gone from actuarial underwriting to claims analytics to research scholarship to founding a company in under three years, and I would rather show you the trajectory than oversell the present tense.

The throughline across all of it, actuarial science, underwriting, claims, customer analytics, research, is one question asked in different rooms: *what does this number mean for the person who has to live with the decision it produces?* That question is what I am building a career around, and InsurTech, risk AI, and explainable ML are simply where it is currently most useful to ask it.

<br>

<div align="center">

*Numbers tell the truth. I try to make sure they tell it well.*

<a href="https://www.linkedin.com/in/valerie-jerono"><img src="https://img.shields.io/badge/Let's%20Connect-00695C?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:40E0D0,100:00695C&height=100&section=footer" width="100%"/>

</div>