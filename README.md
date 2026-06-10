# 🏎️ Forza Horizon: Classificador Probabilístico de Veículos

Bem-vindo ao repositório do projeto final da disciplina de **Estatística e Probabilidade**. Este projeto aplica conceitos de análise de dados e probabilidade para prever a tração de veículos com base em seus atributos físicos, utilizando dados reais do simulador automobilístico Forza Horizon.

## 📌 Sobre o Projeto

O objetivo principal deste sistema é classificar a variável alvo `Drive_Type` (Tração: FWD, RWD ou AWD) a partir dos seguintes atributos preditores:
* `Speed` (Velocidade)
* `Handling` (Dirigibilidade)
* `Acceleration` (Aceleração)
* `Launch` (Arrancada)

Para isso, construímos o **Teorema de Bayes Gaussiano matematicamente do zero**, sem depender de bibliotecas prontas para o cálculo probabilístico. Também implementamos algoritmos de Machine Learning auxiliares para fins de comparação e encapsulamos tudo em um **Dashboard Interativo** moderno.

## 📊 Estrutura e Funcionalidades

O projeto foi desenvolvido em formato de *Notebook* (Python) e contempla as seguintes etapas:
1. **Limpeza e Tratamento de Dados:** Remoção de valores nulos e prevenção de indeterminações matemáticas na variância.
2. **Análise Exploratória de Dados (EDA):** Gráficos interativos mostrando a distribuição das classes e correlações espaciais.
3. **Classificador Bayesiano:** Implementação "from scratch" de Probabilidade *A Priori*, Verossimilhança e Probabilidade *A Posteriori*.
4. **Algoritmos Comparativos:** Treinamento de modelos *Decision Tree* (Árvore de Decisão) e *K-Nearest Neighbors* (KNN).
5. **Dashboard Web:** Interface gráfica gerada com `Dash` e `Plotly` com simulador em tempo real.

## 💾 Base de Dados (Dataset)

* **Arquivo utilizado no projeto:** `Forza_Horizon_Cars_Tratado.csv` (já limpo e estruturado para execução direta).
* **Fonte Original do Dataset:** O dataset bruto foi obtido através de fontes abertas. Você pode acessar a fonte original aqui: [COLE_AQUI_O_LINK_DO_KAGGLE]

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Manipulação de Dados:** Pandas, Math
* **Machine Learning:** Scikit-Learn
* **Visualização e Interface:** Dash, Dash Bootstrap Components (Tema Cyborg), Plotly Express

## 🚀 Como Executar o Projeto

Para testar o Dashboard Interativo e ver o código em funcionamento:

1. Faça o download dos arquivos deste repositório (`.ipynb` e `.csv`).
2. Abra o **Google Colab** (ou ambiente Jupyter de sua preferência) e faça o upload do arquivo de código (`.ipynb`).
3. Faça o upload do dataset `Forza_Horizon_Cars_Tratado.csv` para a raiz do seu ambiente virtual no Colab.
4. Execute todas as células do Notebook.
5. Na última célula, o Colab irá gerar um link seguro azul (ex: `https://[...]-colab.googleusercontent.com/`). Clique nele para abrir o Dashboard em uma nova aba.

---
**Desenvolvido por:** Carlos Alonso e Hermes Tupinambá
