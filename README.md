# 📊 Projeto: Inteligência Comercial em Vendas de Suplementos (MYK Nutri)

Este projeto analisa dados semanais de vendas de suplementos alimentares (2020–2025), com foco em identificar padrões robustos de lucratividade, prever demanda, segmentar canais e gerar recomendações estratégicas. A entrega é estruturada com base no modelo CRISP-DM e apresenta abordagem consultiva no estilo McKinsey.

---

## 🧠 Objetivo do Projeto

- Diagnosticar as categorias e regiões com maior retorno comercial após o período de pandemia
- Identificar os fatores que impulsionam vendas rentáveis
- Prever demanda futura com base no histórico
- Agrupar lojas por perfil de performance
- Criar visualizações acionáveis para decisão executiva

---

## 📦 Dataset Utilizado

- Fonte: [Kaggle - Supplement Sales Data VC](https://www.kaggle.com/datasets/zahidmughal2343/supplement-sales-datavc)
- Período: Jan/2020 a Abr/2025
- Localidades: 🇺🇸 EUA, 🇬🇧 Reino Unido, 🇨🇦 Canadá
- Plataformas: Amazon, Walmart, iHerb
- Observação: Análises priorizam dados **pós-2022** para evitar viés da pandemia.

---

## 📈 Técnicas Estatísticas e de Machine Learning Aplicadas

| Técnica                       | Aplicação                                              |
|------------------------------|--------------------------------------------------------|
| Information Value (IV)       | Identificação de variáveis explicativas               |
| Random Forest Regressor      | Previsão de receita                                   |
| K-Means Clustering           | Segmentação de lojas por comportamento de vendas      |
| STL Decomposition / Rolling  | Análise de sazonalidade e tendência temporal          |
| Regressão Linear             | Interpretação do impacto das variáveis numéricas      |
| Visualizações com Seaborn/Matplotlib | Dashboards estáticos para decisão comercial |

---

## 🧱 Estrutura do Projeto (Cookiecutter Data Science)

sales-insights/
│
├── data/
│ ├── raw/ # Dados brutos originais
│ ├── processed/ # Dados limpos e transformados
│
├── notebooks/
│ ├── Sales.ipynb # Notebook principal com storytelling
│
├── src/
│ ├── features/ # Scripts de engenharia de variáveis
│ ├── models/ # Scripts de modelagem (RF, KMeans, etc.)
│ ├── visualizations/ # Gráficos finais e utilitários
│
├── reports/
│ ├── figures/ # Visualizações geradas
│ ├── executive_summary.md # Versão executiva das conclusões
│
├── README.md
├── LICENSE
└── requirements.txt


---

## 📌 Aprendizados e Diferenciais

- Uso crítico dos dados (controle de viés da pandemia)
- Aplicação de técnicas explicativas e preditivas
- Comunicação orientada a negócios
- Projeto 100% em Python, sem necessidade de apps externos

---

## 📜 Licença


Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.

---

## ✒️ Autor

**Mayerikson Pereira**  
🔗 [LinkedIn](https://www.linkedin.com/in/mayerikson)  
💻 [GitHub](https://github.com/Mayerikson)
