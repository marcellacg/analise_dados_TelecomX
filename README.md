# 📉 Análise de Evasão de Clientes - TelecomX

Este projeto tem como objetivo identificar os principais fatores que levam à rotatividade de clientes (churn) em uma empresa fictícia de telecomunicações, a **TelecomX**, e propor **estratégias de retenção** baseadas em dados.

Todo o trabalho foi desenvolvido no **Google Colab**, utilizando Python e bibliotecas de análise e modelagem como Pandas, Scikit-Learn e Matplotlib.

---

## 🚀 Objetivos

- Analisar os dados de clientes da TelecomX.
- Identificar os principais fatores relacionados à evasão de clientes.
- Construir modelos preditivos de churn.
- Propor estratégias de retenção baseadas em dados e resultados dos modelos.

---

## 🛠️ Tecnologias e Ferramentas

- **Python 3.10+**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn (sklearn)**

---

## 📊 Etapas da Análise

### 1. Exploração e Limpeza dos Dados
- Análise exploratória (EDA) com visualizações para entender a distribuição e correlação das variáveis.
- Tratamento de valores nulos e conversão de variáveis categóricas.

### 2. Modelagem
Foram utilizados dois modelos de Machine Learning:
- **Regressão Logística**
- **Random Forest**

> A **Regressão Logística** teve melhor desempenho, com uma acurácia de **80,3%**.

### 3. Principais Fatores Identificados
- Tipo de contrato (mensal = maior evasão).
- Tempo de serviço (clientes novos evadem mais).
- Ausência de serviços de segurança online e suporte técnico.
- Faturamento mensal alto.
- Faturamento digital (clientes mais propensos a trocar de provedor).

---

## 💡 Estratégias de Retenção Sugeridas

- **Incentivar contratos longos:** descontos e benefícios em planos de 1 ou 2 anos.
- **Oferecer serviços de valor agregado:** como segurança online e suporte técnico gratuito no início.
- **Ofertas personalizadas:** descontos temporários, upgrades de plano, etc.
- **Aprimorar o onboarding:** garantir que novos clientes saibam usar todos os recursos desde o início.

---

## 📁 Estrutura do Projeto

```
📂 TelecomX-Churn
├── 📘 evasao_churn_TelecomX.ipynb  # Notebook com toda a análise
├── 📄 README.md                    # Documentação do projeto
```

---

## ▶️ Como Executar

Este projeto foi desenvolvido no **Google Colab**, então não é necessário configurar nada localmente. Basta clicar no botão abaixo para abrir o notebook e executar online:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Se preferir rodar localmente:
1. Clone este repositório:
   ```bash
   git clone https://github.com/marcellacg/analise_dados_TelecomX.git
   cd analise_dados_TelecomX
   ```
2. Execute o notebook `evasao_churn_TelecomX.ipynb` em um ambiente Jupyter.

---

## 📌 Contribuições

Contribuições são bem-vindas! Sinta-se livre para abrir issues, sugerir melhorias ou enviar pull requests.
