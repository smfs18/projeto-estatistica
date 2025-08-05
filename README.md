# Análise de Saúde e Hábitos: Um Estudo Preditivo e Prescritivo

## 📑 Visão Geral do Projeto

Este projeto apresenta uma análise de dados completa de um conjunto de dados sintético sobre saúde e hábitos de vida. O objetivo principal foi explorar os dados para entender o perfil dos pacientes, construir um modelo preditivo para identificar o risco de hipertensão e, finalmente, gerar recomendações prescritivas para a melhoria da saúde cardiovascular.

O estudo abrange três pilares da análise de dados:
* **Análise Descritiva:** Para entender as características fundamentais da amostra.
* **Análise Preditiva:** Para prever a probabilidade de um paciente desenvolver hipertensão.
* **Análise Prescritiva:** Para fornecer recomendações acionáveis baseadas nos achados.

## 🚀 Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas de Análise de Dados:**
    * `R` para manipulação e tratamento dos dados e operações numéricas.
* **Bibliotecas de Visualização:**
    * `readr` , `dplyr` , `ggplot2` , para a criação de gráficos e visualizações.
* **Bibliotecas de Machine Learning:**
    * `scikit-learn` para pré-processamento, modelagem preditiva (`RandomForestClassifier`) e avaliação de performance.

## 📂 Estrutura do Repositório

```
.
├── dados_tratados.csv      # Conjunto de dados utilizado na análise
├── Relatorio.pdf           # Relatório final detalhado da análise exploratória
├── Relatório.rmd           # Relatório final .rmd
├── AnaliseBivariada.ipynb  # Jupyter Notebook com todo o código da análise bivariada
├── gráficor.py             # Gráficos utilizados em R para os insights.
└── README.md               
```

## 📈 Análise Realizada

### 1. Análise Descritiva

Uma investigação inicial foi conduzida para caracterizar a amostra de 1.000 pacientes. Os principais achados incluem:
* **Demografia:** Distribuição de sexo equilibrada (50.6% homens, 49.4% mulheres) com idade média de 49 anos.
* **Hábitos:** A maioria dos pacientes é não fumante (69%) e pratica atividade física de nível moderado (40%).
* **Métricas de Saúde:** Pressão arterial média de 120/80 mmHg, com 7 horas de sono em média.


### 2. Análise Preditiva

O principal desafio foi construir um modelo para prever se um paciente é hipertenso (Pressão Sistólica ≥ 140 mmHg ou Pressão Diastólica ≥ 90 mmHg).

* **Modelo:** Foi utilizado um classificador `RandomForestClassifier`.
* **Performance:** O modelo final alcançou uma acurácia de **77.7%**.
* **Principais Preditores:** As variáveis mais influentes na previsão do risco de hipertensão foram, em ordem de importância:
    1.  Altura (cm)
    2.  Peso (kg)
    3.  Consumo Semanal de Álcool (ml)
    4.  Idade
    5.  Horas de Sono


### 3. Análise Prescritiva

Com base nos resultados do modelo preditivo, foram formuladas as seguintes recomendações para mitigar o risco de hipertensão:

1.  **Gerenciamento de Peso:** Manter um Índice de Massa Corporal (IMC) saudável, visto que o peso é um dos principais preditores.
2.  **Moderação no Álcool:** Reduzir o consumo semanal de álcool, outro fator de alto impacto.
3.  **Monitoramento com a Idade:** Pacientes mais velhos devem intensificar o monitoramento da pressão arterial.
4.  **Higiene do Sono:** Garantir uma rotina de sono adequada, pois demonstrou ser um fator relevante.
5.  **Incentivo à Atividade Física:** Aumentar o nível de atividade física, especialmente para sedentários.
6.  **Cessação do Tabagismo:** Abandonar o fumo para reduzir os riscos cardiovasculares associados.

## 🏁 Conclusões

A análise demonstrou que a hipertensão é uma condição multifatorial, fortemente influenciada por características físicas (peso, altura), demográficas (idade) e hábitos de vida (consumo de álcool, sono). As recomendações prescritivas fornecem um caminho claro para a intervenção e promoção da saúde, com foco nos fatores de risco modificáveis mais impactantes.

Para uma análise exploratória mais aprofundada, consulte o arquivo [`Relatorio.pdf`](./Relatorio.pdf).

## ✍️ Autores

* **Silas Manoel, Bernardo Siqueira, Fabrício Aranha e Pedro Henrique** 

---
