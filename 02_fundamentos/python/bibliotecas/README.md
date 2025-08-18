# 📚 Bibliotecas Essenciais para Ciência de Dados

Este diretório contém cadernos de estudo e notebooks práticos sobre as principais bibliotecas de Python utilizadas em Ciência de Dados.  
O objetivo é demonstrar **domínio completo** de cada ferramenta, desde conceitos básicos até aplicações avançadas em análise, manipulação, visualização de dados e Machine Learning.

---

## 💻 Conteúdo Abordado

### 🐼 Pandas
- Manipulação e análise de dados tabulares (DataFrames e Series)
- Limpeza, filtragem e transformação de dados
- Operações de agregação, junções e merge
- Trabalhando com datas, índices e dados categóricos
- Exportação e importação de dados (CSV, Excel, SQL)
- 📓 Notebooks: `pandas/`

### 🔢 NumPy
- Arrays multidimensionais e operações vetoriais
- Indexação, slicing e broadcasting
- Funções matemáticas e estatísticas
- Álgebra linear e manipulação de matrizes
- Base para bibliotecas como Pandas, Scikit-learn e Matplotlib
- 📓 Notebooks: `numpy/`

### 📊 Matplotlib
- Criação de gráficos básicos (linha, barra, dispersão, pizza)
- Personalização de cores, estilos e legendas
- Subplots, eixos e escalas
- Visualizações estáticas para análise exploratória
- 📓 Notebooks: `matplotlib/`

### 🌈 Seaborn
- Gráficos estatísticos avançados (boxplot, violin, pairplot, heatmap)
- Integração com Pandas para análise de datasets
- Estética de gráficos e paletas de cores
- Simplificação de visualizações complexas com menos código
- 📓 Notebooks: `seaborn/`

### 🤖 Scikit-learn
- Pré-processamento de dados (normalização, encoding, feature scaling)
- Divisão de dados em treino e teste
- Algoritmos de Machine Learning:
  - Regressão: Linear, Ridge, Lasso
  - Classificação: Logistic, Random Forest, SVM
  - Agrupamento: KMeans, DBSCAN
- Avaliação de modelos (métricas, cross-validation)
- Pipelines e integração com outras bibliotecas
- 📓 Notebooks: `scikit-learn/`

---

## 📂 Estrutura de Pastas Recomendada

```bash
bibliotecas/
│
├── README.md                     # Este arquivo
├── pandas/                       # Notebooks e exercícios Pandas
│   ├── introducao.ipynb
│   ├── limpeza_transformacao.ipynb
│   └── agregacoes_merge.ipynb
├── numpy/                        # Notebooks e exercícios NumPy
│   ├── arrays_basicos.ipynb
│   ├── algebra_linear.ipynb
│   └── funcoes_estatisticas.ipynb
├── matplotlib/                    # Notebooks de visualização básica
│   ├── graficos_linha_barra.ipynb
│   ├── personalizacao.ipynb
│   └── subplots_eixos.ipynb
├── seaborn/                       # Notebooks de visualização estatística
│   ├── graficos_estatisticos.ipynb
│   ├── mapas_calor.ipynb
│   └── pairplot_corr.ipynb
└── scikit-learn/                  # Notebooks de ML
    ├── preprocessing.ipynb
    ├── regressao_classificacao.ipynb
    └── clustering_e_pipelines.ipynb
