# 📊 Portfólio: Python para Controladoria e FP&A

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Finance](https://img.shields.io/badge/Domain-Finance_%26_FP%26A-green?style=for-the-badge&logo=money)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

> **Resolução de problemas reais de finanças corporativas através de automação, análise de dados e inteligência artificial.**

---

## 👨‍💼 Sobre Mim

Olá! Sou **Douglas Macedo Silva**, Coordenador de Controladoria e Especialista em Finanças Digitais.
Minha carreira combina uma sólida base em **Controladoria, Custos e Planejamento Financeiro** com habilidades avançadas em tecnologia.

Este repositório documenta minha jornada aplicando Python para transformar a área financeira, saindo do Excel tradicional para soluções escaláveis de **Engenharia de Dados e Machine Learning**.

* **LinkedIn:** [Douglas Macedo Silva](https://www.linkedin.com/in/douglasmacedosilva)
* **Foco:** Automação de Processos, FP&A, Machine Learning e Business Intelligence.

---

## 🎯 Objetivos deste Repositório

O objetivo central é demonstrar como a programação pode resolver "dores" clássicas da área financeira:
1.  **Eliminar o trabalho manual** e repetitivo (o famoso "Excel Hell").
2.  **Aumentar a precisão** das projeções financeiras (Forecasting).
3.  **Agilizar o fechamento** mensal e a geração de relatórios gerenciais.

---

## 🛠 Tech Stack e Bibliotecas

Utilizo um conjunto robusto de ferramentas mapeadas para cada necessidade da área financeira:

| Categoria | Bibliotecas Principais | Utilização em Finanças |
| :--- | :--- | :--- |
| **ETL & Manipulação** | `Pandas`, `NumPy`, `Polars` | Tratamento de grandes bases contábeis, consolidação de razões e balancetes. |
| **Automação Excel** | `OpenPyXL`, `XlsxWriter` | Criação automática de relatórios formatados, leitura e edição de planilhas complexas. |
| **Visualização** | `Matplotlib`, `Seaborn`, `Plotly` | Gráficos de Waterfall (DRE), evolução de custos e dashboards interativos. |
| **Machine Learning** | `Scikit-Learn`, `Statsmodels` | Forecasting de receita, detecção de anomalias em lançamentos (auditoria) e Clusterização. |
| **Web Apps** | `Streamlit` | Criação de interfaces para usuários finais visualizarem KPIs sem precisar de código. |

---

## 📂 Projetos Destacados

Aqui estão alguns dos estudos de caso e ferramentas desenvolvidas neste portfólio:

### 1. Automação de DRE e Consolidação Contábil
* **Problema:** Processo manual de consolidação de 50+ arquivos de Excel de centros de custo diferentes.
* **Solução:** Script Python que lê todos os arquivos, padroniza as colunas e gera uma base consolidada pronta para análise.
* **Stack:** `Pandas`, `OS`, `OpenPyXL`.
* [📂 Ver Código](./01_Automacao_Rotinas)

### 2. Forecast de Receita com Machine Learning
* **Problema:** As projeções baseadas apenas em média móvel não capturavam a sazonalidade do negócio.
* **Solução:** Aplicação de modelos de Regressão Linear e ARIMA para prever o faturamento dos próximos 6 meses.
* **Stack:** `Scikit-Learn`, `Statsmodels`.
* [📂 Ver Código](./03_Forecasting_Orcamento)

### 3. Análise Budget vs. Actual (Orçado x Realizado)
* **Problema:** Dificuldade em visualizar rapidamente onde ocorreram os estouros de orçamento.
* **Solução:** Dashboard automatizado que cruza o ERP com a planilha de orçamento e gera alertas de desvios acima de 5%.
* **Stack:** `Pandas`, `Plotly`.
* [📂 Ver Código](./03_Forecasting_Orcamento)

---

## 🚀 Como Executar os Projetos

Para rodar os scripts deste repositório na sua máquina local:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/douglas-ms/fpna-python-portfolio.git](https://github.com/douglas-ms/fpna-python-portfolio.git)
    ```
2.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Execute os Notebooks:**
    Navegue até a pasta do projeto desejado e abra o arquivo `.ipynb` via Jupyter Notebook ou VS Code.

---

## ⚠️ Nota sobre Dados

Todos os dados utilizados nestes projetos são **fictícios** ou anonimizados, respeitando as normas de LGPD e confidencialidade corporativa. A lógica de negócio, entretanto, reflete desafios reais do dia a dia de uma controladoria.

---

Feel free to connect or contribute!
