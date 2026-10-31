# 📊 Análise de Dados Sociais com Python

> Pipeline ETL em Python e Pandas para extração, transformação e análise de dados a partir de um arquivo CSV.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![ETL](https://img.shields.io/badge/ETL-Pipeline-orange)

## 🎯 Objetivo

Este projeto foi desenvolvido para praticar fundamentos de **engenharia de dados e análise de dados com Python**, construindo um pipeline simples e reproduzível de ETL.

A ideia é transformar dados brutos em um arquivo tratado, aplicando limpeza, transformação e uma análise básica durante o processo.

## 🔄 Pipeline de dados

```text
📄 dados.csv
     │
     ▼
🟦 EXTRACT
Leitura com Pandas
     │
     ▼
🟨 TRANSFORM
• Remoção de valores nulos
• Criação de Valor_Ajustado
     │
     ▼
🟩 ANALYZE
Cálculo da média
     │
     ▼
🟪 LOAD
dados_tratados.csv
```

## 🧠 O que pratiquei

- Leitura de arquivos CSV com Pandas
- Tratamento de valores ausentes
- Criação de novas colunas
- Cálculo de estatísticas básicas
- Separação do código em funções
- Organização de um pipeline ETL
- Exportação dos dados tratados

## 🛠️ Tecnologias

- **Python**
- **Pandas**
- **CSV**

## 📁 Estrutura do projeto

```text
analise-dados-sociais-python/
├── analise.py
├── dados.csv
├── dados_tratados.csv
├── requirements.txt
└── README.md
```

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SaioThech/analise-dados-sociais-python.git
cd analise-dados-sociais-python
```

### 2. Instale a dependência

```bash
pip install -r requirements.txt
```

### 3. Execute o pipeline

```bash
python analise.py
```

O programa lê `dados.csv`, realiza as transformações, calcula a média e gera o arquivo `dados_tratados.csv`.

## 💡 Próximos passos

Este projeto representa uma das etapas da minha evolução prática em **AI Engineering**. A partir daqui, estou avançando de dados e Python para Machine Learning, NLP, Transformers, LLMs e sistemas RAG.

```text
Dados
  ↓
Python + ETL
  ↓
Machine Learning
  ↓
NLP + Transformers
  ↓
LLMs + RAG
  ↓
MLOps
  ↓
Sistemas de IA em produção
```

## 👩🏽‍💻 Sobre mim

Sou estudante de **Inteligência Artificial e Machine Learning**, construindo minha trajetória como **AI Engineer** por meio de projetos práticos.

Meu foco atual é desenvolver fundamentos sólidos em Python, dados e Machine Learning e evoluir para a construção, avaliação e implementação de sistemas de IA.

🔗 **GitHub:** https://github.com/SaioThech

🔗 **LinkedIn:** https://www.linkedin.com/in/saionara-rufino-barros-frossard-53a1302a0/

---

⭐ Este projeto faz parte do meu portfólio de evolução em **Dados → Machine Learning → GenAI**.
