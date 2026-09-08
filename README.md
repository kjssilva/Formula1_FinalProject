# 🏎️ Além do Carro Mais Rápido
### Análise de Dados da Fórmula 1 com Python, Estatística, SQL e Power BI

## 📌 Sobre o Projeto

**Além do Carro Mais Rápido** é um projeto de análise de dados desenvolvido como projeto final de um bootcamp de Data Analytics.

O objetivo foi investigar quais fatores estão mais associados ao desempenho competitivo na Fórmula 1, indo além da ideia de que o resultado de uma corrida depende apenas da velocidade do carro.

O projeto percorre diferentes etapas de um fluxo de análise de dados, desde a exploração e preparação dos dados até testes estatísticos, consultas SQL e visualização dos principais resultados em Power BI.

---

## 🎯 Problema de Negócio

A análise foi orientada pela seguinte pergunta:

> **Quais fatores estão mais associados ao desempenho competitivo na Fórmula 1?**

A partir dessa questão principal, foram investigadas três perguntas:

1. **Como a posição de largada está associada ao desempenho durante a corrida?**
2. **Quais pilotos apresentam maior capacidade de ganhar posições durante as corridas?**
3. **Qual é a relação entre o desempenho no treino classificatório e o resultado final da corrida?**

---

## 🛠️ Tecnologias Utilizadas

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - SciPy

- **Jupyter Notebook**
  - Análise exploratória
  - Preparação dos dados
  - Testes estatísticos

- **MySQL**
  - Modelagem relacional
  - JOINs
  - Agregações
  - Consultas analíticas

- **Power BI**
  - Visualização dos resultados
  - Construção dos painéis

- **PowerPoint**
  - Comunicação dos resultados e insights

---

## 🔄 Fluxo do Projeto

```text
Dados
  ↓
Python / EDA
  ↓
Análise Estatística
  ↓
MySQL / SQL
  ↓
Power BI
  ↓
Insights e Recomendações
```

Cada etapa foi utilizada para responder uma parte diferente do problema, mantendo uma sequência entre exploração, validação, análise e comunicação.

---

## 📊 Dados

O projeto utiliza dados históricos da Fórmula 1 disponibilizados publicamente no Kaggle.

A base contém informações relacionadas a:

- corridas;
- pilotos;
- construtores;
- resultados;
- posições de largada;
- classificação;
- pit stops;
- voltas;
- temporadas;
- entre outras informações históricas da competição.

Os dados foram organizados em tabelas relacionais e posteriormente utilizados nas análises em Python e SQL.

---

## 🔍 Metodologia

### 1. Python e Análise Exploratória

A primeira etapa foi dedicada à compreensão e preparação dos dados.

Foram realizadas atividades como:

- importação dos datasets;
- análise da estrutura das tabelas;
- verificação de tipos de dados;
- tratamento de valores ausentes;
- criação de variáveis necessárias para as análises;
- análise exploratória;
- investigação da relação entre posição de largada e resultado final.

---

### 2. Análise Estatística

Após a exploração inicial, foram aplicados testes estatísticos para verificar se as diferenças observadas entre os grupos eram estatisticamente significativas.

A análise comparou pilotos que largaram:

- **Grid 1–10**
- **Grid > 10**

Foram utilizados testes como:

- **Teste de Levene**
- **Teste t de Welch**
- **Teste de Mann-Whitney**

Essa etapa permitiu complementar a análise exploratória com evidências estatísticas.

---

### 3. SQL e Modelagem Relacional

Os dados foram estruturados em um banco MySQL para responder às perguntas de negócio por meio de consultas SQL.

Entre os principais recursos utilizados estão:

- `JOIN`
- `GROUP BY`
- `AVG`
- `COUNT`
- `SUM`
- `CASE WHEN`
- `ORDER BY`
- `LIMIT`

A tabela `results` foi utilizada como uma das principais tabelas da análise, relacionando informações de pilotos, construtores e corridas.

---

### 4. Power BI

Os principais resultados foram transformados em visualizações no Power BI.

Os painéis foram desenvolvidos para apoiar visualmente as três perguntas de negócio:

- posição de largada × resultado;
- pilotos com maior média de posições ganhas;
- qualifying × resultado final.

As visualizações foram mantidas objetivas para facilitar a comunicação dos principais insights.

---

## 📈 Principais Resultados

A análise encontrou uma associação clara entre a posição de largada e o desempenho durante a corrida.

Entre os resultados observados:

- Pilotos que largaram da **pole position venceram 58,24%** das corridas analisadas.
- **86,10% das vitórias** foram conquistadas por pilotos que largaram entre as três primeiras posições.
- Pilotos que largam entre as primeiras posições apresentam, em média, melhores posições finais e maior pontuação.
- O desempenho no treino classificatório apresenta uma associação consistente com o resultado final da corrida.
- Apesar da importância da posição de largada, alguns pilotos demonstram maior capacidade de recuperação de posições durante as provas.

Os resultados reforçam que o desempenho competitivo na Fórmula 1 não depende de um único fator, mas a posição conquistada antes da corrida representa uma vantagem relevante.

---

## 💡 Recomendações

Com base nos resultados, duas áreas se destacam:

**Desempenho no qualifying**

Investir em estratégias que aumentem a competitividade durante o treino classificatório pode gerar uma vantagem significativa, considerando a forte associação entre posição de largada e resultado final.

**Execução durante a corrida**

Além da posição inicial, estratégias relacionadas à recuperação de posições, consistência e tomada de decisão durante a prova continuam relevantes para maximizar o desempenho.

---

## 📁 Estrutura do Repositório

```text
formula1-data-analysis/
│
├── README.md
│
├── notebooks/
│   ├── python/
│   ├── statistics/
│   └── sql/
│
├── data/
│
├── sql/
│
├── dashboard/
│
├── presentation/
│
└── images/
```

A organização poderá ser ajustada conforme os arquivos finais forem adicionados ao repositório.

---

## ⚠️ Limitações

Algumas limitações foram consideradas durante o desenvolvimento:

- diferenças de disponibilidade de informações entre temporadas;
- registros históricos com dados ausentes;
- limitações de algumas ferramentas utilizadas na representação da modelagem;
- simplificações visuais realizadas nos dashboards para melhorar a legibilidade.

Os resultados devem ser interpretados dentro do contexto da base analisada.

---

## 🚀 Próximos Passos

Possíveis extensões deste projeto incluem:

- análise do impacto de pit stops;
- comparação entre desempenho de pilotos e construtores;
- análise por circuitos;
- evolução do desempenho ao longo das temporadas;
- análise de estratégias de corrida;
- desenvolvimento de modelos preditivos para resultados futuros.

---

## 📚 Fonte dos Dados

Dataset histórico da Fórmula 1 disponível no Kaggle:

**Formula 1 World Championship (1950–2020)**  
Rohan Rao — Kaggle
Link: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=status.csv
