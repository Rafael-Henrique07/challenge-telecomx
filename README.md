# 📉 Case: Inteligência de Dados Aplicada à Retenção de Clientes (Churn)

Este repositório apresenta uma investigação analítica focada em **Churn Rate** (evasão de clientes) para o setor de prestação de serviços. O objetivo central é decodificar os padrões de comportamento que precedem o cancelamento, utilizando ciência de dados para transformar registros brutos em decisões estratégicas de negócio.

A análise explora as intersecções entre dados demográficos, modalidades contratuais e métricas de faturamento para mitigar a perda de receita e aumentar o LTV (*Lifetime Value*).

---

## 🛠️ Stack Tecnológica

O ecossistema de ferramentas utilizado para o desenvolvimento deste projeto inclui:

* **Linguagem:** Python 3.11
* **Manipulação de Dados:** `pandas`
* **Visualização de Dados:** `matplotlib` e `seaborn`
* **Ambiente de Desenvolvimento:** Jupyter Notebook

---

## 🚀 Ciclo de Desenvolvimento

O projeto foi estruturado seguindo as melhores práticas de análise exploratória (EDA):

1.  **Ingestão e Diagnóstico:** Carregamento do dataset e auditoria inicial da integridade dos dados.
2.  **Data Wrangling:** Normalização de colunas (Snake Case), tratamento de tipos de variáveis e limpeza de inconsistências.
3.  **Análise de Distribuição:** Estudo da proporção volumétrica entre clientes ativos e churn.
4.  **Estudo de Correlações Categóricas:** Avaliação do impacto do tipo de contrato, métodos de pagamento e perfil demográfico na retenção.
5.  **Análise Quantitativa:** Uso de gráficos de dispersão e densidade para entender a relação entre o *Tenure* (tempo de casa) e o *Total Charges* (valor gasto).
6.  **Síntese Estratégica:** Extração de insights para suporte à tomada de decisão.

---

## 📊 Insights Extraídos

* **Vulnerabilidade Inicial:** Identificou-se que o maior índice de evasão ocorre nos meses iniciais de contrato (*Early Churn*).
* **Sensibilidade Financeira:** Clientes com menor gasto acumulado apresentam maior volatilidade, sugerindo baixa percepção de valor ou barreiras de saída reduzidas.
* **Neutralidade de Perfil:** Variáveis como gênero não apresentaram relevância estatística na probabilidade de cancelamento.
* **Gatilhos Contratuais:** Modelos específicos de faturamento e prazos contratuais funcionam como preditores de risco de saída.

---

## 💡 Recomendações de Negócio

* **Onboarding Direcionado:** Implementar réguas de relacionamento intensivas para novos clientes nos primeiros 90 dias.
* **Programas de Loyalty:** Estruturar benefícios progressivos baseados na longevidade do contrato para incentivar a permanência.
* **Revisão de Portfólio:** Ajustar condições comerciais ou processos em métodos de pagamento que apresentam alta taxa de atrito.
* **Modelagem Preditiva:** Utilizar este estudo como base para o treinamento de modelos de classificação (Machine Learning) para antecipar o risco de churn.

---

## 📬 Contato
**Rafael Henrique**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/rafael-henrique-de-oliveira-da-silva)
