# 📊 Telecom X - Análise de Evasão de Clientes (Churn)

## 📌 Descrição do Projeto

Você foi contratada como **Assistente de Análise de Dados** na **Telecom X** para integrar o projeto **"Churn de Clientes"**.
A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.

O objetivo deste desafio é **coletar, tratar e analisar dados** de clientes, utilizando **Python** e suas principais bibliotecas, a fim de gerar **insights estratégicos**.
Esses insights servirão de base para que a equipe de **Data Science** avance para **modelos preditivos** e desenvolva **estratégias para reduzir a evasão**.

---

## 🎯 Objetivos

* Coletar dados a partir de uma **API**.
* Realizar **ETL** (Extração, Transformação e Carga) dos dados.
* Criar **visualizações estratégicas** para identificar padrões e tendências.
* Executar uma **Análise Exploratória de Dados (EDA)**.
* Gerar um **relatório com insights** sobre os fatores de churn.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas Principais:**

  * `pandas` → Manipulação e limpeza de dados
  * `numpy` → Operações numéricas e estatísticas
  * `matplotlib` e `seaborn` → Visualização de dados
  * `requests` e `json` → Consumo de API
  * `scipy` → Estatísticas e testes
  * `scikit-learn` → Pré-processamento e codificação de variáveis

---

## 📂 Estrutura do Projeto

```
📁 telecom-x-churn
│
├── Telecom_X1.ipynb   # Notebook com todo o processamento e análise
├── README.md          # Documentação do projeto
└── requirements.txt   # Dependências do projeto
```

---

## 🔍 Etapas da Solução

1. **Importação das bibliotecas** necessárias.
   
2. **Configurações visuais** para gráficos e DataFrames.

3. **Extração de dados** diretamente de uma API (com backup local).
   
4. **Pré-processamento e tratamento de dados**:

   * Padronização de colunas
   * Tratamento de valores ausentes
   * Conversão de tipos de dados
   * Codificação de variáveis categóricas
     
5. **Análise Exploratória de Dados (EDA)**:

   * Estatísticas descritivas
   * Distribuições e correlações
   * Comparações entre clientes que cancelaram e que permaneceram
     
6. **Visualizações estratégicas** para identificar padrões de churn.
   
7. **Geração de relatório final** com conclusões.

---

## 📊 Exemplos de Insights Encontrados

* Identificação de **variáveis mais associadas ao churn** (ex.: tempo de contrato, tipo de plano, consumo de dados).
* Diferenças de comportamento entre **clientes ativos** e **clientes cancelados**.
* Possíveis **perfis de clientes em risco**.

---

## 🚀 Como Executar

1. **Clone este repositório**

```bash
git clone https://github.com/seu-usuario/Telecom-X.git
cd Telecom-X
```

2. **Crie e ative um ambiente virtual**

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. **Instale as dependências** usando o `requirements.txt`

```bash
pip install -r requirements.txt
```

4. **Abra o notebook no Jupyter**

```bash
jupyter notebook Telecom_X1.ipynb
```

---

## 📄 Licença

Este projeto é de uso educacional e não possui fins comerciais.
