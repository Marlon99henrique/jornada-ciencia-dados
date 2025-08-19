# 📚 Projetos Práticos com Pandas

Esta pasta é uma coleção de projetos de dados que demonstram o domínio de habilidades essenciais na biblioteca pandas. Cada notebook foi desenvolvido para abordar um aspecto fundamental da análise de dados, da limpeza inicial à preparação para a modelagem.

---

## 📓 Os Notebooks

### [1. **Análise Exploratória de Dados (EDA): Limpeza e Visualização**](https://github.com/Marlon99henrique/jornada-ciencia-dados/blob/main/02_fundamentos/python/bibliotecas/pandas/projetos_pandas/01_eda_limpeza_visualizacao.ipynb)

**Descrição:** Este projeto foca na primeira e mais importante etapa da análise de dados. Ele demonstra como inspecionar, limpar e tratar dados brutos, incluindo o manuseio de valores ausentes e a identificação de outliers, usando as ferramentas poderosas do pandas.

**Habilidades:** `pd.read_csv()`, `df.info()`, `df.isnull()`, `df.dropna()`, `df.describe()`, `df.pivot_table()`.

<br>

---

### [2. **Análise de Séries Temporais**](https://github.com/Marlon99henrique/jornada-ciencia-dados/blob/main/02_fundamentos/python/bibliotecas/pandas/projetos_pandas/02_analise_series_temporais.ipynb)

**Descrição:** Este notebook é dedicado ao trabalho com dados baseados em tempo. Ele mostra como extrair insights de colunas de data, realizar reamostragem de dados para diferentes frequências e usar médias móveis para suavizar tendências e identificar sazonalidade.

**Habilidades:** `pd.to_datetime()`, `.dt` acessor, `df.resample()`, `df.rolling()`.

<br>

---

### 3. **Engenharia de Atributos (Feature Engineering)**

**Descrição:** Este projeto faz a ponte entre a análise de dados e a modelagem de Machine Learning. Ele ilustra como criar novas variáveis a partir de dados existentes (feature engineering), converter dados categóricos para um formato numérico (`get_dummies()`) e combinar múltiplos conjuntos de dados usando `merge()` e `join()`.

**Habilidades:** `pd.get_dummies()`, `pd.merge()`, `df.corr()`.

---

## 🚀 Como Usar

Para executar os notebooks, você pode:

1. **Clonar o repositório**
2. **Ter o Jupyter Notebook ou JupyterLab instalado**
3. **Instalar as bibliotecas necessárias:**

```bash
pip install pandas numpy matplotlib seaborn
