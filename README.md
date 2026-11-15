<p align="center">
  <a href="https://asccjr.github.io/portfolio/"><img alt="Portfólio" src="./assets/badges/portfolio-compact.svg" height="28" width="102"></a>
  <a href="https://asccjr.github.io/"><img alt="Currículo" src="./assets/badges/curriculo-compact.svg" height="28" width="108"></a>
  <a href="https://www.linkedin.com/in/asccjr/"><img alt="LinkedIn" src="./assets/badges/linkedin-compact.svg" height="28" width="105"></a>
  <a href="https://huggingface.co/asccjr"><img alt="Hugging Face" src="./assets/badges/hugging-face-compact.svg" height="28" width="144"></a>
</p>

<p align="center">
  <a href="./embedded-systems-iot.md"><img alt="Embedded Systems &amp; IoT" src="./assets/badges/iot-compact.svg" height="28" width="239"></a>
</p>

## AI Builder & Forward Deployed Engineering (FDE)

| Projeto | Stack | Entrega |
|---|---|---|
| [Copiloto de Entregas](https://github.com/ASCCJR/copiloto-de-entregas)<br><br>[link demo](https://portfolio-antonio-sergio.vercel.app/copiloto) | Next.js, TypeScript, OpenAI API, Vercel | Painel de pontualidade com dados da Olist. O chat usa os filtros do painel e abre os pedidos que sustentam a resposta. |
| [Revez](https://asccjr.github.io/portfolio/revez/) | Slack, Make, Google Sheets, IA generativa | Piloto de revisão, ajuste e aprovação de entregas no Slack. O teste com duas contas confirmou que só a pessoa vinculada à tarefa recebe seus detalhes. |
| [Monitor de Vagas](https://asccjr.github.io/portfolio/monitor-de-vagas/) | Make, Greenhouse API, Google Sheets, Gmail, IA generativa | Triagem automática de vagas públicas e resumo por e-mail. Separei o texto de cada trilha para evitar a mistura de requisitos e validei a extração em três anúncios reais. |
| [EvidentGraph](https://evidentgraph.github.io/evidence-graph/caso-stripe/) | FastAPI, SQLite, OpenTelemetry, OpenAPI | API de laboratório com dois contratos. Testei quais clientes simulados falhavam quando um campo era removido da resposta. |

## Analytics Engineering & BI

| Projeto | Stack | Entrega |
|---|---|---|
| Painel de SLAs de atendimento | Freshservice, Power BI, SQL, dbt | Indicadores de primeira resposta e resolução para a gestão avaliar o cumprimento de SLAs por prestadores terceirizados. As divergências de cálculo foram corrigidas em SQL e dbt e os resultados foram validados com a liderança e a TI do cliente. |

## Data Engineering

| Projeto | Stack | Entrega |
|---|---|---|
| [LH Nautical](https://github.com/ASCCJR/Indicium_LH_Nautical) | Databricks, PySpark, Delta Lake, Streamlit, API do Banco Central | Pipeline Bronze, Silver e Gold que integra vendas e câmbio PTAX. No cenário do desafio técnico da Indicium, o cálculo com câmbio histórico revelou margem de −5,3%. |

## Data Science

| Projeto | Stack | Entrega |
|---|---|---|
| [Antecipação de alertas críticos em frota de mineração](https://asccjr.github.io/portfolio/programa-desenvolver-vale/) | Python, Databricks, LightGBM | **1º lugar em Análise Avançada de Dados no Programa Desenvolver 2026 da Vale.** Pipeline de machine learning para estimar o risco de alertas críticos em frota de mineração em uma janela de até quatro horas. |
| [One Bank — Churn Prediction](https://github.com/ASCCJR/One_Bank_Churn_Prediction) | scikit-learn, XGBoost, SHAP, SMOTE | Comparação de três modelos de churn com validação cruzada, ajuste do limiar de decisão e simulação de retorno financeiro. |
| [Online Retail Analytics](https://github.com/ASCCJR/Online_Retail_EDA) | Python, pandas, seaborn, statsmodels | Análise exploratória de varejo com segmentação RFM, investigação de anomalias financeiras e análise de sazonalidade. |
| [Análise exploratória com Jupytext](https://asccjr.github.io/portfolio/analise-com-jupytext/) | Python, Matplotlib, Jupytext, Claude | O mesmo código gera o gráfico para revisão no notebook e uma descrição textual com os mesmos valores para o Claude consultar. |

## AI Engineering

| Projeto | Stack | Entrega |
|---|---|---|
| [Sentimento em Foco](https://github.com/ASCCJR/sentiment-analysis-mlops) | Python, MLflow, FastAPI, Gradio | Comparação de três modelos de sentimento com registro de métricas e predições, API de inferência em lote e interface bilíngue. |
| [Caderno de Visão Computacional](https://github.com/ASCCJR/caderno-visao-computacional) | YOLO11, OpenCV, CLIP, PyTorch, Gradio | Aplicação que processa vídeo para gerar indicadores de varejo, como fluxo de pessoas e ocupação. [Demo](https://huggingface.co/spaces/asccjr/cv-playground) |
| [Chatbot NLP — E-commerce](https://github.com/ASCCJR/Chatbot_NLP) | NLTK, scikit-learn, BERT, Gradio | Pipeline de classificação de intenções, reconhecimento de entidades, busca em FAQ e análise de sentimento. [Demo](https://huggingface.co/spaces/asccjr/Chatbot_NLP) |

<!-- Badges renderizados pelo Shields.io. Ícones: Lucide (assets/badges/LICENSE-Lucide.txt) e Simple Icons (LinkedIn 11.15.0 e Hugging Face). -->
