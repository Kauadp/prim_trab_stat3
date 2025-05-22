# 📊 Análise de Regressão Linear Simples - Predição Salarial

Este repositório contém um projeto desenvolvido como parte da disciplina **Estatística III**, com foco na aplicação de **regressão linear simples** para modelar e prever salários com base em variáveis explicativas como **experiência, idade** e **escolaridade**.

---

## 🔍 Objetivo

O objetivo do trabalho foi construir, avaliar e interpretar um modelo de regressão linear simples que seja capaz de prever o salário de indivíduos a partir de uma única variável preditora. Além disso, foi proposta uma análise separada por gênero, com o intuito de verificar possíveis diferenças entre os modelos ajustados para homens e mulheres.

---

## 📁 Estrutura do Projeto

- `dados.csv` — Base de dados com informações de salário, experiência, idade, escolaridade e gênero.
- `trabalho.Rmd` — Código-fonte da análise estatística realizada em R.
- `Trabalho.pdf` — Relatório final com os gráficos, interpretações e conclusões.
- `README.md` — Este arquivo.

---

## ⚙️ Metodologia

As etapas do projeto foram as seguintes:

### 1. Exploração Inicial dos Dados  
- Estatísticas descritivas das variáveis.
- Verificação de possíveis valores extremos ou inconsistentes.

### 2. Escolha da Variável Explicativa  
- Análise gráfica da relação entre salário e cada uma das variáveis explicativas.
- Escolha da variável **experiência** como preditora por apresentar:
  - Maior significância estatística,
  - Menores resíduos,
  - Melhor poder explicativo (R²).

### 3. Ajuste do Modelo de Regressão Linear Simples  
- Modelo geral ajustado:  
  \[
  \hat{salário} = \theta_1 + \theta_2 \cdot experiência
  \]
- Interpretação dos coeficientes.

### 4. Avaliação do Modelo  
- Cálculo das métricas de erro:
  - **EQM** (Erro Quadrático Médio)
  - **MAE** (Erro Absoluto Médio)
  - **MAPE** (Erro Percentual Absoluto Médio)
- Avaliação da qualidade do modelo com base nas métricas.

### 5. Análise por Gênero  
- Modelos separados para homens e mulheres.
- Comparação dos coeficientes e métricas de erro.
- Interpretação das diferenças entre os grupos.

### 6. Conclusão  
- O modelo apresentou bom desempenho preditivo (MAPE ≈ 10%).
- A experiência se mostrou uma variável explicativa relevante.
- Diferenças sutis observadas entre os gêneros.
- Sugestão de melhorias: incluir mais variáveis e observações.

---

## 📈 Resultados

| Gênero    | EQM       | MAE       | MAPE    |
|-----------|-----------|-----------|---------|
| Masculino | 45.056.668 | 5.451,54 | 10,11 % |
| Feminino  | 49.644.071 | 5.715,30 | 10,65 % |

---

## 🛠️ Tecnologias

- Linguagem: **R**
- Ambiente: **RStudio**
- Pacotes utilizados: `ggplot2`, `ggthemes`, `cowplot`

---

## 📚 Créditos

Trabalho desenvolvido por **Kauã Dias** como parte da disciplina **Estatística III**.