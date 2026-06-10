# Consumo de Energia Industrial: Aplicação de Regressão Linear

## Contexto do Projeto

O consumo de energia é um dos principais indicadores operacionais em ambientes industriais, estando diretamente relacionado à produtividade, eficiência dos processos e custos de produção.

A compreensão dos fatores que influenciam o consumo energético permite identificar padrões de comportamento, otimizar recursos e apoiar a tomada de decisão baseada em dados.

Neste projeto, foi aplicada a técnica de **Regressão Linear** para investigar a relação entre variáveis explicativas e o consumo de energia industrial, avaliando a capacidade do modelo em representar o fenômeno observado e gerar previsões consistentes.

---

## Problema de Negócio

O monitoramento e a previsão do consumo de energia são atividades fundamentais para organizações industriais que buscam melhorar sua eficiência operacional e reduzir custos.

Entretanto, nem sempre é evidente quais fatores exercem maior influência sobre o consumo energético. Dessa forma, torna-se necessário utilizar métodos estatísticos capazes de quantificar essas relações e fornecer modelos interpretáveis para apoio à tomada de decisão.

Diante desse cenário, surge a seguinte questão:

> É possível explicar e prever o consumo de energia industrial utilizando um modelo de Regressão Linear?

---

## Objetivo do Projeto

Desenvolver um modelo de **Regressão Linear** capaz de analisar a relação entre variáveis explicativas e o consumo de energia industrial, avaliando seu desempenho por meio de métricas estatísticas e da análise dos resíduos.

Além disso, busca-se verificar se as principais premissas da regressão linear são atendidas, garantindo a validade estatística das inferências produzidas pelo modelo.

---

## Base de Dados

A base de dados utilizada contém informações relacionadas ao consumo de energia industrial e variáveis potencialmente associadas ao seu comportamento.

O conjunto de dados foi utilizado para:

* Identificar padrões de consumo;
* Avaliar relações entre variáveis explicativas e a variável resposta;
* Construir modelos preditivos;
* Interpretar fatores que influenciam o consumo energético;
* Validar estatisticamente os resultados obtidos.

---

## Metodologia

O desenvolvimento do projeto seguiu as principais etapas de um fluxo de Ciência de Dados.

### 1. Compreensão dos Dados

* Importação da base de dados;
* Identificação das variáveis;
* Verificação dos tipos de dados;
* Avaliação inicial da qualidade das informações.

### 2. Análise Exploratória de Dados

Foram realizadas análises exploratórias com o objetivo de compreender o comportamento das variáveis.

As análises incluíram:

* Estatísticas descritivas;
* Histogramas;
* Boxplots;
* Matriz de correlação;
* Identificação de possíveis outliers;
* Relação entre variáveis explicativas e variável resposta.

### 3. Pré-Processamento

* Tratamento de dados ausentes (quando necessário);
* Seleção das variáveis relevantes;
* Organização dos dados para modelagem;
* Separação entre variáveis independentes e variável dependente.

### 4. Construção do Modelo

Foi utilizado um modelo de **Regressão Linear** para estimar o consumo de energia a partir das variáveis explicativas disponíveis.

As etapas envolveram:

* Ajuste dos coeficientes do modelo;
* Treinamento da regressão;
* Interpretação dos parâmetros estimados.

### 5. Avaliação do Modelo

O desempenho do modelo foi avaliado utilizando:

* Coeficiente de Determinação (R²);
* Comparação entre valores observados e previstos;
* Análise gráfica dos resíduos;
* Avaliação da qualidade geral do ajuste.

---

## Premissas da Regressão Linear

Para garantir a validade estatística do modelo, foram avaliadas as principais premissas da regressão linear.

### Linearidade

Verifica se existe uma relação aproximadamente linear entre as variáveis explicativas e a variável resposta.

### Independência dos Erros

Avalia se os resíduos são independentes entre si.

### Homocedasticidade

Verifica se a variância dos resíduos permanece aproximadamente constante ao longo das previsões realizadas pelo modelo.

### Normalidade dos Resíduos

Avalia se os resíduos apresentam distribuição aproximadamente normal.

### Ausência de Multicolinearidade

Verifica se não existem relações excessivamente fortes entre as variáveis explicativas.

---

## Resultados Principais

Os resultados obtidos demonstraram que o modelo foi capaz de capturar parte significativa da variabilidade observada no consumo de energia.

As análises realizadas permitiram:

* Identificar variáveis com maior influência sobre o consumo energético;
* Avaliar a qualidade do ajuste por meio do coeficiente de determinação (R²);
* Verificar o comportamento dos resíduos;
* Interpretar os coeficientes estimados;
* Identificar limitações e oportunidades de melhoria do modelo.

A análise residual indicou comportamento compatível com as principais premissas da regressão linear, reforçando a confiabilidade das estimativas produzidas.

---

## Linguagem de Programação

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)

---

## Bibliotecas Utilizadas

### Manipulação e Tratamento de Dados

[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)](https://pandas.pydata.org/)

[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)](https://numpy.org/)

### Visualização de Dados

[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)](https://matplotlib.org/)

[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)

### Machine Learning e Estatística

[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)](https://scikit-learn.org/)

[![Statsmodels](https://img.shields.io/badge/Statsmodels-2E5EAA?style=for-the-badge)](https://www.statsmodels.org/)

---

## Ambiente de Desenvolvimento

[![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge\&logo=visualstudiocode\&logoColor=white)](https://code.visualstudio.com/)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org/)

---

## Estrutura do Projeto

```text
Consumo_de_Energia_Industrial_Regressao_Linear
│
├── RegressaoLinear.ipynb
│
├── README.md
│
└── imagens/
```

---

## Fluxo do Projeto

```text
Base de Dados
      │
      ▼
Análise Exploratória
      │
      ▼
Pré-Processamento
      │
      ▼
Regressão Linear
      │
      ▼
Avaliação do Modelo
      │
      ▼
Análise dos Resíduos
      │
      ▼
Interpretação dos Resultados
```

---

## Considerações Finais

Este projeto demonstra a aplicação prática de técnicas estatísticas e de Ciência de Dados na modelagem de problemas relacionados ao consumo de energia industrial.

A utilização da Regressão Linear permitiu compreender a influência das variáveis explicativas sobre o consumo energético, além de fornecer uma base sólida para análises preditivas e apoio à tomada de decisão.

Os resultados obtidos evidenciam a importância da modelagem estatística como ferramenta para interpretação de fenômenos reais e geração de conhecimento a partir dos dados.

---

## Autor: **Felipe A. Camargo**

* Licenciado em Matemática – UNESP
* Mestre em Biometria – UNESP
* Doutor em Biometria – UNESP

LinkedIn: https://www.linkedin.com/in/felipeacamargo
