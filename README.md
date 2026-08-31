# Gabriel Braga

**Data science aplicada a finanças e operações de empresas brasileiras** — do fechamento contábil a modelos de machine learning em produção.

Trabalho na interseção entre dados e negócio: FP&A e análise de DREs, detecção de fraude, people analytics e agentes de IA generativa. Meu foco é o ciclo completo — dados, modelo, validação, deploy — com o resultado explicado na língua de quem decide.

📫 [LinkedIn](https://www.linkedin.com/in/gabrielfebraga) · [gafebraga@gmail.com](mailto:gafebraga@gmail.com) · [Instagram](https://www.instagram.com/gaab.braga/)

---

## Projetos em destaque

### concept_fpa — plataforma de FP&A 🔒 *(repositório privado)*

Plataforma de análise financeira para uma média empresa brasileira: consolida os dados de fechamento e transforma DREs em visões gerenciais navegáveis, apoiando o ciclo mensal de planejamento e análise financeira.

*Python · Pandas · visualização interativa*

### [AML-Ops-Engine](https://github.com/gaab-braga/AML-Ops-Engine) — detecção de lavagem de dinheiro

**Problema:** identificar fraude em mais de 5 milhões de transações com apenas 0,12% de casos positivos.
**Abordagem:** XGBoost com feature engineering e validação temporal, otimização com Optuna, explicabilidade com SHAP; empacotado com Docker, 37 testes automatizados e 85% de cobertura.
**Resultado:** 95,6% ROC-AUC — captura 87% das fraudes com 1,3% de falsos positivos, F1 235× superior ao benchmark de GNN da IBM e inferência abaixo de 50ms.

*Python · XGBoost · LightGBM · Optuna · SHAP · Polars · Docker · Pytest*

### [mds-agent-partner](https://github.com/gaab-braga/mds-agent-partner) — agente de análise de dados

**Problema:** a maioria das PMEs brasileiras decide marketing sem análise de dados — contratar um cientista de dados sênior custa dezenas de milhares de reais por mês.
**Abordagem:** sistema multi-agente (Planner → Executor → Evaluator → Responder) com Gemini 2.0 Flash e Google ADK, interface Chainlit e deploy no Vertex AI Agent Engine.
**Resultado:** análises com narrativa de negócio geradas de ponta a ponta a partir de um CSV e uma pergunta em português. [▶️ Demo em vídeo (6 min)](https://www.youtube.com/watch?v=8IW4VXle3JQ)

*Python · Gemini · Vertex AI · Google ADK · Chainlit · Plotly*

### [Turnover-Analysis](https://github.com/gaab-braga/Turnover-Analysis) — people analytics

**Problema:** o RH tratava turnover como um número isolado; faltava entender quem estava saindo e por quê.
**Abordagem:** análise em três camadas — impacto financeiro, diagnóstico com ML explicável (SHAP) e análise de sobrevivência (lifelines) — com base preparada para consumo em Power BI.
**Resultado:** a discussão migrou de "perdemos pessoas" para "estamos perdendo a parte errada da força de trabalho?", com priorização de retenção por risco e contribuição.

*Python · scikit-learn · SHAP · lifelines · Seaborn · Power BI*

### [case-wiz](https://github.com/gaab-braga/case-wiz) — pipeline de dados de DRE

Pipeline financeiro de ponta a ponta: ingestão e tratamento com Pandas, persistência em PostgreSQL via SQLAlchemy, API com FastAPI e ambiente conteinerizado com testes.

*Python · Pandas · PostgreSQL · SQLAlchemy · FastAPI · Docker*

---

## Ferramentas do dia a dia

- **Análise e ML:** Python (Pandas, NumPy, Polars, scikit-learn), XGBoost, LightGBM, Optuna, SHAP
- **Visualização e BI:** Plotly, Matplotlib, Seaborn, Streamlit, Power BI, Excel/VBA
- **Engenharia:** SQL/PostgreSQL, FastAPI, SQLAlchemy, Docker, Pytest, GitHub Actions
- **IA generativa:** Gemini, Vertex AI, Google ADK

Formação complementar: Machine Learning e Deep Learning Specializations (Coursera).
