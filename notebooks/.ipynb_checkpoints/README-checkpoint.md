#  Olist — Análise de Entregas e Satisfação do Cliente

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Visualization](https://img.shields.io/badge/Visualization-Seaborn-lightgrey)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License](https://img.shields.io/badge/License-MIT-green)

##  Sobre o Projeto
Este projeto tem como objetivo analisar o impacto dos **atrasos de entrega** sobre a **satisfação do cliente** (notas de avaliação) na base de dados pública da **Olist**.  
Além disso, busca-se evidenciar diferenças regionais e estaduais no cumprimento dos prazos de entrega.

##  Estrutura da Análise
1. **Carregamento e Preparação dos Dados**
2. **Qualidade dos Dados** (nulos e duplicados)
3. **Criação da Variável de Atraso**
4. **Análises Descritivas**
5. **Relação entre Atraso e Nota**
6. **Correlação e Regressão Linear**
7. **Análise Geográfica** (Estado e Região)
8. **Conclusões e Recomendações**

## Principais Resultados
- Pedidos atrasados recebem, em média, **notas muito mais baixas** (≈ 2.27) do que pedidos entregues no prazo (≈ 4.29).
- A **correlação de Pearson** entre atraso (em dias) e nota é **-0.267**, indicando relação negativa significativa.
- Cada dia de atraso reduz a nota média em aproximadamente **0.034 pontos**.
- O **Nordeste** apresentou o maior percentual de atrasos (~12,5%), enquanto o **Sul** teve o menor (~5,8%).

## Tecnologias Utilizadas
- **Python 3.7+**
- **Pandas** para manipulação de dados
- **Seaborn / Matplotlib** para visualização
- **SciPy** (correlação estatística)
- **Scikit-learn** (regressão linear)
- **Jupyter Notebook** para exploração

## 📂 Estrutura do Repositório
