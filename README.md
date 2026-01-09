# churn-prediction-credit-card

# 📉 Churn Prediction - Credit Card

> Projeto de análise preditiva para identificar padrões de cancelamento de cartões de crédito e propor recomendações estratégicas de retenção.

## 🎯 Objetivo do Projeto
Analisar o comportamento da base de clientes para entender os gatilhos do Churn e oferecer soluções práticas para o negócio.

* Identificar correlações entre o nível de engajamento e a retenção de clientes.
* Analisar o impacto do volume de contatos no suporte técnico sobre a taxa de cancelamento.
* Propor planos de ação baseados em dados (Business Recommendations).

---


## 🏗️ Estrutura do Projeto

```json
{
  "churn-prediction-credit-card/": {
    "notebooks/": "churn_prediction_credit_card.ipynb",
    "documentação/": "README.md"
  }
}


🛠️ Tecnologias Utilizadas
Python 3.10

Pandas (Manipulação e tratamento de dados)

Matplotlib & Seaborn (Visualização de dados e gráficos)

Jupyter Notebook / Google Colab

✅ Conclusões e Insights Estratégicos
A análise identificou padrões claros que permitem ações preventivas imediatas:

Engajamento é a Chave: A maioria dos cancelamentos está ligada à baixa frequência de transações. Clientes que utilizam o cartão mais de 60 vezes apresentam uma taxa de retenção altíssima.

Atenção ao Atendimento: Existe uma correlação direta entre o volume de contatos com a central e o cancelamento, indicando que a resolução ineficiente de problemas é um gatilho para o churn.

Portfólio de Produtos: Clientes com menor quantidade de produtos contratados são estatisticamente mais propensos à evasão.

💡 Recomendações para o Negócio (Business Recommendations)
Incentivo ao Uso: Implementar programas de fidelidade ou metas de gastos mensais para incentivar o cliente a atingir a marca de 60 transações.

Plano de Resgate Preventivo: Criar um alerta automático para clientes que reduzem drasticamente o uso do cartão, permitindo agir antes do pedido de cancelamento.

Otimização do Suporte: Focar o time de atendimento na resolução definitiva de problemas no primeiro contato.
